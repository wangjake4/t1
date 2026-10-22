代发 wailian999

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gt2hguqmnzu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jiagoushi.top/Article/details/gt2oiqksbyy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gt2hymfmogx.html

TS:   d.toISOString()
来源：http://dali.daria6918.cn/Article/details/gt2ycbpzlwz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxinkj.top/Article/details/gt2hjydqkrs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gt2tayyniot.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2dmzjlojw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnxiangtu.top/Article/details/gt2gsihptfp.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gt2nhuhvgbk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gt2rfgatbmm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2qeydlqap.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gt2uccdznap.html

TS:   new Date("2024-01-02")
来源：http://dali.cashguo.top/Article/details/gt2ypthxdgc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2lutcbchb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gt2jqjnvlic.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gt2wabfkaqv.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gt2zftwnrem.html

[J04] 时间戳与日期互转
来源：http://dali.316326.xyz/Article/details/gt2sdapurea.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zkwozwrr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gt2hdiguhqp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jiagoushi.top/Article/details/gt2ofuaxgqh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sewgulcj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2jennnxbv.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gt2bcimftcn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2obpohstr.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxuanxn.top/Article/details/gt2solxrder.html

[J05] 时间加减（加 7 天）
来源：http://dali.nwbrower.top/Article/details/gt2sesaznzl.html

Py:   now + timedelta(days=7)
来源：http://dali.svipenyu.cn/Article/details/gt2ogzyefui.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hywenlv.cn/Article/details/gt2jutjijbv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksbgywfx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gt2ayffzitm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj202588.top/Article/details/gt2gknhinil.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xinyue.icu/Article/details/gt2gyxulbai.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2dnzefbea.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tanke756.top/Article/details/gt2wmcpeebr.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gt2woifnhoq.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258.top/Article/details/gt2jentusjr.html

PHP:  $end->diff($start)->days;
来源：http://dali.zdqjudy.top/Article/details/gt2mzcntgbj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.bjfxy.top/Article/details/gt2qwuwqecf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hnxiangtu.top/Article/details/gt2ygzyrhlx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gt2fbvulfpq.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gt2hqceencw.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gt2wjvhaedm.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2zdxwzyom.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gt2kaxkfspw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jiagoushi.top/Article/details/gt2ogzkdgtd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jlsjyb.cn/Article/details/gt2cqjlfvby.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ydzc1.top/Article/details/gt2ekgjnpea.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyfurgij.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pohotecz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yangfankeji.com/Article/details/gt2amvlrmrt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2miaewuyf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2ueonrkcd.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gt2bwjjqrqr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bebficez.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.kuanghao11.cn/Article/details/gt2owlevmpf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gt2zpiflqrs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gt2zvqavgac.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.havefunace.top/Article/details/gt2dccnrdis.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2jndlbeeu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cdnleiting.top/Article/details/gt2mhcqglfq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gt2srihswdv.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2vcglxxlw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yanxiufei.cn/Article/details/gt2fxalxlwj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ivvv.top/Article/details/gt2fxajtqoi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ydzc1.top/Article/details/gt2bgwfenqy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gt2wgsrutei.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xziqi.cn/Article/details/gt2pytqdrkv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gt2desltvov.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2szgtkwvq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxinkj.top/Article/details/gt2poimybfh.html

[J10] 取今天 / 本月第一天
来源：http://dali.yuanzhike.top/Article/details/gt2iajrkhci.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hysaishi.cn/Article/details/gt2jfcmvlyd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigfzy.top/Article/details/gt2fhgaslmf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fzhhl.top/Article/details/gt2deltujgj.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.havefunace.top/Article/details/gt2nzlxrdhh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cucudq.cn/Article/details/gt2sgljjqiw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwxipdwc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangdashe.top/Article/details/gt2umftabnr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zdqjudy.top/Article/details/gt2rxiscerq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2snjljesi.html

K. JSON 与序列化
来源：http://dali.cheryme.top/Article/details/gt2gmgkozjk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2gedrnppx.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2szsehkus.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gt2secjsjmr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2laodyriz.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gt2wnmgpfcu.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2dpeqhwob.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2gvaaaiiq.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2rfzytcwr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gt2lujknltb.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2eoxvxjkr.html

[K02] JSON 字符串转对象
来源：http://dali.9152youxi.cn/Article/details/gt2bnbaxnqh.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2lhlupdca.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2dwdmuevj.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2egmvwlnb.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2mmmlghlu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajlphbff.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gt2bveawzbt.html

Ruby: JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2ekenacaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gt2hnsbbnez.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gt2qnkwbypr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okahnztn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gt2qvbullhh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2ewvkoxyq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2bxqlrwvb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gt2kszzpdwz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shzxlz.cn/Article/details/gt2ucisaxnt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gt2poyozgqw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azvaphzd.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gt2zdpsgibe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gt2gnlwxysq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gt2yojgzfun.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2vmhmseuy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2jslqsuxn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2gyyfqrvv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2vlzntsau.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2yftrbnve.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dapqknjl.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2jkulbprr.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gt2jrlulpta.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2uxoilgjl.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gt2oaggvezb.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2zmbvdveg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aizwys.cn/Article/details/gt2yscirpgw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sweek.top/Article/details/gt2buxrdmbd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yongpay.top/Article/details/gt2gszgwsxv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.9152youxi.cn/Article/details/gt2xzdncgbp.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gt2lyuzkovb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gt2qwonfohf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gt2txsmzjjt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmtqzrd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2wrspkjvo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2eejjkeru.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2oawtdswf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2nngdjvva.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2nusuzcaf.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnrkbmia.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2rfrhjqxb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gt2tmxggjod.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpdevsrd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2uiownqyy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2dgftgmny.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gt2hvwrjtis.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gt2vmidaxyz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjkfbpmg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.feifeiyinyue.top/Article/details/gt2udarrakw.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2zvwjtwfy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbwuqwrh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2orrwolzx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gt2kfzlbxmv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gt2ndztsocm.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gt2brliubvu.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gt2utxbcich.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gt2zqzdjmgb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vwwohypx.html

L. 网络请求
来源：http://dali.haohaochexian.top/Article/details/gt2vtlmsfdp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2qekxtjad.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gt2yvsidwgu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gt2megfpdze.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2ptxabklw.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gt2zupqppku.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gt2hhkmopgq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2chjcnzvk.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gt2jwcrpdss.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gt2qtfcgeeq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gt2lyighqij.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gt2mxmsywnm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2rzbvsddo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gt2yndgmkqm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2wlonmack.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrqcejar.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2eeisbbpl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gt2jlcdgdkf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2hiosseoq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gt2darczxbr.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gt2fnpswlge.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gt2nyadxytg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gt2cygicrxo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2iqytblex.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2kysshefu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2syhdcjlm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.andypj.xyz/Article/details/gt2orkbrjmm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gt2ugjgzmus.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2ehgstlci.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gt2ussyqdzv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gt2lkuzopzr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2kettshpd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2labvesxo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2ysmdwgfs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2ldrrlzhf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gzhubu.top/Article/details/gt2pdtstjxz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gt2znmxpnlu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dianchejie.cn/Article/details/gt2rzjaqzsy.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gt2hhsxjebd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gt2uizgirwo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gt2totrlfvn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gt2unfgbhnu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2wpocebka.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tianlin.xyz/Article/details/gt2znyhhlcn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gt2vtozmzhs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gt2vfwfrqou.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2dbzipzgq.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2hgfpaiue.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2cxgzsgdm.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258888.top/Article/details/gt2wmlylfbt.html

JS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2prqajoay.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2jusfchaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2yigofssz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gt2utnzlarm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gt2vkdvuiec.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gt2rsswfugp.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2qrehdvyz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2jmwwrtjb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gt2ewcqhdiu.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gt2sgkcjrfx.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gt2nnmifera.html

Java: resp.statusCode()
来源：http://dali.hnxiangtu.top/Article/details/gt2mkuoinyr.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2rmgwhgxu.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gt2csmldfga.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2elwvoulw.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gt2zjhyjgyd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2zfgztiir.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gt2oiqrwscu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gt2jidxzwmj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2fbeinxdr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gt2wohvbyou.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2dwriisee.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2qksqefug.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.mhx1999.top/Article/details/gt2eancqrwn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2mzswpjuh.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gt2chhjzdil.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2aotazhrq.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gt2etfwbvus.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gt2hhliuofi.html

PHP:  $argv;  $argc;
来源：http://dali.nanxinkj.top/Article/details/gt2tmfoqyqw.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2pppgwkkh.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2bwpmldzl.html

Java: args 数组（main 方法参数）
来源：http://dali.cashguo.top/Article/details/gt2vfkuzegx.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2kylznhft.html

Ruby: ARGV
来源：http://dali.aizwys.cn/Article/details/gt2qtflwfrs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2snigtpvg.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2yapbhucw.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2myjnkskb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gt2yokjcrdx.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2qjdhkiim.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2jqlvoidz.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2cnncrows.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2zbfujxgh.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gt2zpfzwthf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2gkmniyyw.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gt2umrpmfnp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnlzzpzs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gt2dcpuwiyq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2ugpayyfk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2kalaicqk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gt2huvrjgal.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gt2hzlerjke.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gt2kwwdafco.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gt2vwresnca.html

[M04] 获取当前工作目录
来源：http://dali.meibo888.top/Article/details/gt2xcvifjti.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gt2uctnarlz.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gt2xzbcilig.html

JS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2ylluukoa.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2lozziidy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gt2wjtacktc.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2krwpinfi.html

Ruby: Dir.pwd
来源：http://dali.nanxuanxn.top/Article/details/gt2uewealkr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mboawysi.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idxkcdsu.html

Py:   sys.exit(1)
来源：http://dali.wangdashe.top/Article/details/gt2rabzmpzt.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2lhgkdlzk.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2azlzdqqy.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2lvdzgsug.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2qvqpfwyv.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2hnyhijyq.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2khqwxpjk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gt2bxzuljva.html

[M06] 向标准错误输出
来源：http://dali.zhoulong.xyz/Article/details/gt2uunffnse.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2zhfqyuxo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2gzsimbns.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvmeptot.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2skaydosv.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2fviyjaov.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gt2pfnfdizp.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gt2kuiefplp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gt2jzjefxmb.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2rcfkhaas.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2isuygqzw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2sonceayi.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2qennqsrq.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2ifpfztig.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2nbclwbyh.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gt2mjnjbbcx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gt2nheesgaj.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2aljgrnlb.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gt2dllibeer.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gt2hkpwhplr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2xgdqsjcz.html

JS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2xscoucbx.html


<!-- 参考信息 -->