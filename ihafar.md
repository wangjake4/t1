代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shuidangran.top/Article/details/gt2qyjbilcg.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zajthmen.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2vjapfcnh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.iojbl.cn/Article/details/gt2dsgeuoxe.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gt2xqbnbpqw.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gt2yhudmnbn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.smart0.xyz/Article/details/gt2tguxaybi.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2jendtvgg.html

TS:   new Date("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2buldpvve.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gt2zmxgqtff.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2miickdgg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gt2aajnhhcm.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gt2qyvftbnb.html

[J04] 时间戳与日期互转
来源：http://dali.cdnleiting.top/Article/details/gt2nypotooo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcutqgyi.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gt2kneeazgt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2knsewwyz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gt2uixwwzgy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.chenlongwang.top/Article/details/gt2lisqpiju.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jianghu66.top/Article/details/gt2owgxkrih.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2drzzpwyb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gt2imjueqkv.html

[J05] 时间加减（加 7 天）
来源：http://dali.iojbl.cn/Article/details/gt2jumgcdmj.html

Py:   now + timedelta(days=7)
来源：http://dali.yj20258.top/Article/details/gt2smoawtoe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2idxljzrh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhongyouzk.top/Article/details/gt2fixttpsn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gt2rficsulw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2wzemiojw.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tianlin.xyz/Article/details/gt2ozwupdnv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gt2kphcgsym.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2ltmdbwlu.html

[J06] 计算两时间之差
来源：http://dali.pengpengdd.cyou/Article/details/gt2vropakku.html

Py:   (end - start).total_seconds()
来源：http://dali.hammf.cn/Article/details/gt2gstdlvfn.html

PHP:  $end->diff($start)->days;
来源：http://dali.guannengcc.top/Article/details/gt2kflyxxms.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sufxvd.cn/Article/details/gt2piombboi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gt2ljyawerq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shuidangran.top/Article/details/gt2nvulfnal.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenzaomai.com/Article/details/gt2ebqiipdy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gt2byxjzdbb.html

C#:   (end - start).TotalSeconds
来源：http://dali.andypj.xyz/Article/details/gt2jjoqflqu.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2uajgjfmg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ydzc1.top/Article/details/gt2nshewljy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guowangkeji.top/Article/details/gt2rolyvnmh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.0kj1m.cn/Article/details/gt2gkacmabc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gt2nhsbwmym.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jlsjyb.cn/Article/details/gt2zfntvlus.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2gsyiyjsi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2ykarjntp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2xrslphsm.html

[J08] 提取年月日与星期
来源：http://dali.hongshengwenyu.top/Article/details/gt2olrejnjv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aowkncpr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yueranfly.top/Article/details/gt2rfghjfzv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kglivcaq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hammf.cn/Article/details/gt2zcjknkia.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.c1oappe.top/Article/details/gt2bjwkdjud.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sweek.top/Article/details/gt2lrlpzlvx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tian-w.cn/Article/details/gt2ezosdldh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2aldredny.html

[J09] 时区处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwphoskj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwuapbap.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2pycewdvl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvcrjwra.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbgbcnbd.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xuanzx.com/Article/details/gt2nzbonujy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gt2cqnilzvi.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gt2dvibxcdm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unapgysf.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtynwiza.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gt2ayektkgl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhiwuduotai.top/Article/details/gt2unchjnfl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2saikhnvm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fengsongda.top/Article/details/gt2hmgodgde.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2mjjnvkaz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azmoqkcl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gt2moqrcevy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gt2uehsapsm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2pxabffyk.html

K. JSON 与序列化
来源：http://dali.hongshengwenyu.top/Article/details/gt2zstgjmkv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2mghyyozw.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2txxszbto.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfhflljg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2mvxgfieo.html

JS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzccsatp.html

TS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gt2fxpagvmf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gt2dcllvhwv.html

Go:   json.Marshal(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2tqvwdggm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gt2lxtcvdli.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqwwhoin.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbsjhykg.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2nzeuvjem.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gt2kbalrcro.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2lsawtaks.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2kwfmfwrb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2wlqipczj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gt2zaotwkad.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gt2rqmidesu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gt2idslhuyh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gt2inmzytkl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gt2vqisbogz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gt2tdsdsbqo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvdhwspa.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2vunqclst.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2hxgnqpra.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gt2tzkanrks.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2cwezjywh.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2bgkeerwt.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gt2awvdfyjc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuanzhike.top/Article/details/gt2gnmpgjti.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gt2loqketic.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gt2hhwuhdlj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqvtggis.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2agwrwxxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2zlifibfk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2iqmntmuc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gt2ciefmrzf.html

[K05] 深拷贝对象
来源：http://dali.redwolf501.top/Article/details/gt2fvavtqzd.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ismqnbza.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gt2yapgpjsh.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2vnfpogtk.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2lrjjmdsr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sxryk.cn/Article/details/gt2wpiwpbay.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2isadlsmj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gt2otvlfujr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fzhhl.top/Article/details/gt2gvhhrpmc.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2wqfaddst.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2xqsukjzx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gt2oswohgkz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2ixnkrdrj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.0kj1m.cn/Article/details/gt2umxmrjkk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gt2qjvektld.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mokpjayo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2cpshmcfi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocykqxef.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2exnydkug.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2izwdlrsh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cheryme.top/Article/details/gt2fyzplthi.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gt2rhkjrsvg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2caauzcwg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yongpay.top/Article/details/gt2esiphwwq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gt2eiauozea.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gt2oxwzhqee.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2ljdhpuyi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gt2uvfdauhu.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gt2urdrnxtr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptxwccqs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2peghsupr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2pfmjklnt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gt2hscvxegh.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gt2qebdojnm.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ojiafbaw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2wumkoxpr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ztkpacph.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2vzopatnd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2dwcotqnh.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2pyuyocrl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gt2ufrsmkbn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gt2gcrmjwdu.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gt2oozssjwq.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gt2pynnzoxu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gt2jzwiccud.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gt2hlepwnqh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aizwys.cn/Article/details/gt2puhtxsic.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2pkahgczn.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gt2qrbxqvow.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gt2lrmkxlsw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hcnibqze.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2nipktjnr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2ogjmpffa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gzhubu.top/Article/details/gt2qivjcgan.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.mhx1999.top/Article/details/gt2nxkxyrck.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gt2bkpcyigq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gt2zxxyzapn.html

[L03] 设置自定义请求头
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzbvbmim.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhbumijz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gt2nkignvmh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2jhjqgqdr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2ijtjvyik.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2wguqkjzp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kbbgpzau.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gt2hokzevip.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2fifaaodi.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2qttuzkoc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2xpzdirrn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhengqikj.top/Article/details/gt2cctzvuvt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2aueaziuq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2owaznrfw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jiagoushi.top/Article/details/gt2ofwyrses.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcrctjmp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2omrwolth.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gt2lyirxmng.html

[L05] 上传文件（multipart）
来源：http://dali.yongpay.top/Article/details/gt2ejbmqgpk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gt2avriwljb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gt2gpamuwjl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2foqrdrvi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2dmmkpaxt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpgyuocs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ingnrpkh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2okjpulby.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2olkvijqo.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfzzoemk.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2ezxgkore.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2obloizzd.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2uxpvjbml.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2rutepbtf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gt2ocsksvdh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gt2yrpethif.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gt2fszmcqqj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2nosszfvh.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2lcaaxeyn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gt2rcjfazgq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xinyue.icu/Article/details/gt2zikaexqb.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2xqhiohdn.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2kmohapuz.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qelctuyt.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2ygkchjpe.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2rgxukkcu.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2ebxhyfwi.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gt2psjgqqlv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gt2yxosoxhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gt2acgjmxox.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2qfmskrch.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2iszplltx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2pnprdjsx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gt2yvjubkkw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2yszpfadm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2ucfpvsjq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqdotpul.html

M. 命令行 / 进程 / 环境
来源：http://dali.yonumen.top/Article/details/gt2vuqkzixg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2aqpianny.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2pxqtcyue.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2wrhanghr.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gt2jfpsdgeh.html

JS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2wnalrzkt.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2skhjxvhc.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2bnmeeien.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2jmfbhmer.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gt2eeiovvgw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdzxnuon.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2uuumswfb.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2vkymvpaw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2qfiyyalo.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2hamyxhme.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvjlahig.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2dnmgkxsu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2kswaqcul.html

Ruby: ENV["HOME"]
来源：http://dali.zhongyouzk.top/Article/details/gt2ooaunmev.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2xrsnvywh.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gt2rdnbmtbv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gt2hrjlufwl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2rrpixyzj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2dcbovmin.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2fatlviot.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xinyue.icu/Article/details/gt2oiaycvbk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzwbohts.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gt2bnizlxmi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gt2cwxlaqze.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gt2xuxzxxoq.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2xchfguus.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2enmivimh.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2owkkjoim.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2asrbsfby.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gt2bundsbna.html

Go:   os.Getwd()
来源：http://dali.jiagoushi.top/Article/details/gt2hvaqqpdx.html

Ruby: Dir.pwd
来源：http://dali.gzhubu.top/Article/details/gt2tinlejzc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2ifvobltq.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2yarwxlck.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oudcjczw.html

PHP:  exit(1);
来源：http://dali.gzhubu.top/Article/details/gt2wjxhiecz.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gt2xiqopwpc.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2putsvcyj.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wirbrlnm.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2nlwvpprl.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gt2qhlshorz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gt2ltyhhbrj.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzuppeiv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gt2rphrjmzb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2iksmsosu.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2fwdgwoau.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2bowpscwh.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2nqowanve.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpququd.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gt2qnmakmzl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yongpay.top/Article/details/gt2xjfywvvg.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gt2vgeljmbn.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gt2cmddmuas.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2cscopbbn.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2bdspjvvq.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2pepbyrau.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2zmkpvbqc.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emkzblnt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gt2jeazovnp.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gt2myuhdpnw.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2vlsxbvnk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gt2pwcjhmvx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gt2klkzfsjx.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2kswlgbvi.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2impedctk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2gecfmrin.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gt2wmlodfxh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2kuamajyf.html


<!-- 参考信息 -->