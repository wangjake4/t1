代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gt2ktnrizzk.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgkchgmb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gt2ctmqolfb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.meibo888.top/Article/details/gt2xsnwbzum.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hywenlv.cn/Article/details/gt2wqyrxnyw.html

[J04] 时间戳与日期互转
来源：http://dali.wangshuangyany.cn/Article/details/gt2fygeagve.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2gdpmwjtr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.316326.xyz/Article/details/gt2dvylauyo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nwbrower.top/Article/details/gt2yawcxnup.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gt2alanabvh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gt2ofbjzjuo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sweek.top/Article/details/gt2yweolkqv.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ljselsrq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.wangdashe.top/Article/details/gt2lqyepsig.html

[J05] 时间加减（加 7 天）
来源：http://dali.zdqjudy.top/Article/details/gt2joelkdfg.html

Py:   now + timedelta(days=7)
来源：http://dali.gaohongyu789.top/Article/details/gt2ylfxzcia.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.nanxuanxn.top/Article/details/gt2tttcupzc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.wangshuangyany.cn/Article/details/gt2todshhnm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2pxlkxfzy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2fxtrourp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gt2eyhnpajs.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nwbrower.top/Article/details/gt2wwkvmygg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2qbaolpou.html

[J06] 计算两时间之差
来源：http://dali.bjfxy.top/Article/details/gt2whzpvgzq.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gt2vtgtowsg.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gt2bxrwheqp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjpbugus.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.havefunace.top/Article/details/gt2czzmyqii.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gt2ovtklzrz.html

Go:   end.Sub(start).Hours()
来源：http://dali.andypj.xyz/Article/details/gt2njsntkll.html

Ruby: end - start                 # 返回秒数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jyaaicwv.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuanzhike.top/Article/details/gt2yemwzjyk.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gt2lhnzqpiu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gt2krnfhrxv.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gt2rytblsvb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2hpqcdzkx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgeodqma.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sxryk.cn/Article/details/gt2nvcuorue.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gt2tuuwwuqh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2obxqpypg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2ynkmuuhd.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2mvrgmwpz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2lxvuybpt.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nanxuanxn.top/Article/details/gt2dxdzwdhq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yongpay.top/Article/details/gt2nimjggzu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258.top/Article/details/gt2qzxfrjqj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gt2dukkjtev.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cucudq.cn/Article/details/gt2awflbfbq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2ueczrmqs.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hywenlv.cn/Article/details/gt2uyfgzjre.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gt2dilgrnnj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jlsjyb.cn/Article/details/gt2vwpsudwm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj20258888.top/Article/details/gt2phdnqggs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cremqbug.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gt2eywboxyn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gt2qaopkiqh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gt2wwpuvpjg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gt2bsvozmpt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gt2zisdygyg.html

[J10] 取今天 / 本月第一天
来源：http://dali.nwbrower.top/Article/details/gt2ufgxenfm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gt2kwplrbgf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gt2nkpmkzjo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.wangdashe.top/Article/details/gt2efndaujc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yongpay.top/Article/details/gt2wafoybls.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ornwjjih.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gt2ndkjcwyx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gt2usuxoosr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2qeodgkrz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2stqttfmj.html

K. JSON 与序列化
来源：http://dali.jqgfzy.top/Article/details/gt2weniaikd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2bebafozh.html

[K01] 对象转 JSON 字符串
来源：http://dali.sufxvd.cn/Article/details/gt2dwyokuxo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2puhjliss.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gt2notephzf.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gt2ujirxipi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2ydobuyrp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gt2boltsgri.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2lplaorlg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.havefunace.top/Article/details/gt2qspvmkiq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bbswouci.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrodzqri.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gt2xcppoqgc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hammf.cn/Article/details/gt2ixccuwia.html

JS:   JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gt2gmxiskbs.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2rjsvlbmc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orskqqru.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2rrbzxpne.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtrczgmm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gt2apxkdkyw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daria6918.cn/Article/details/gt2scsytnuv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gt2mmesrkdy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2zxiibdly.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gt2meyusjmu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2dpnyzxpq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gt2mvokafdw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.havefunace.top/Article/details/gt2ddktfdpm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uevpywmw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gt2mmvwajyk.html

[K04] 读取 JSON 文件
来源：http://dali.gzhubu.top/Article/details/gt2jshydein.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gt2esmnzqcu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gt2mcyovklf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2iqwlteih.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gt2xxyjzxuj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2irtphhne.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gt2jehnkdli.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2fnrdthgj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2cymdtfwa.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gt2cdytmkqx.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gt2qfurnoac.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2wftulvws.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2tppsfhoh.html

TS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2jdwfkvor.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2ndocqdny.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gt2tmvszdau.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zszqurtm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2nltyizqc.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gt2bjqmjoqe.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2vhcuhnso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gt2sriaaexd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2sslvrxvb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gt2qncemyrx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2tncozpeq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gt2xepegkxf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2watiqzcv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sppkonkp.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gt2cxwvrucy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2qypvbdtz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gt2hdavqmzq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2gytyoxmd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2ljhnxxib.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbuzzhwo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2yrbrjexj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2tkyvhtpd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2yyayvzwr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gt2emfvojgg.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2dgtnzhix.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gt2fpkstkkx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gt2owdxyowy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2reklrpte.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2ahbpgqio.html

Go:   encoding/gob
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usxfqsdf.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gt2wzzjnejd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2ssyhsrnd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qwzsyiaa.html

L. 网络请求
来源：http://dali.zhoulong.xyz/Article/details/gt2locacfyu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2okjfqwug.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gt2hjctxkkb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigfzy.top/Article/details/gt2tpcxpbnw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gt2lawmgkcc.html

JS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2wqejktya.html

TS:   await fetch(url)
来源：http://dali.sxryk.cn/Article/details/gt2clvxbqgy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gt2ooylasnp.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2ewzidmkz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gt2uuwngsqg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gt2ngtmwprr.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gt2kudegvnb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gt2kvbuckao.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2dnsjxixv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gt2giowmnad.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2ullacfax.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yangfankeji.com/Article/details/gt2hlycsgha.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2iazbqink.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2slvobsqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gt2ifxykpdw.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gt2npwkhsou.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2pqvzjlxw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2kofravyt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gt2hqtawufl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2cbmojiqs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2neiiblws.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gt2gkwgftgf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gt2rxahuwdl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2jxqtqamt.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2lbsxqhas.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cfsfpjiw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258888.top/Article/details/gt2cdruqled.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2wivmmfsw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gt2efjupies.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gt2cljzafhk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.andypj.xyz/Article/details/gt2pvdjqmpg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hysaishi.cn/Article/details/gt2vvtvhvki.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gt2uglphqor.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gt2rfqerzru.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gt2mxljzacm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gt2oxqwgsgg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gt2fdbgvcwd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2jybftfkj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gt2zpdnswob.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mhmpociy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gt2enurtuln.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gt2mstplhbs.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2jhlqycwe.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxhmfmgu.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gt2lmzquqvs.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2ulgqfxkv.html

TS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcvscaia.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtmnhdgz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gt2wxjupxjn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gt2gsprzvay.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrhwwyu.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2edbfyuvc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gt2iyxivcaj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mplkvuqh.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2qjtbqzir.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aymvjrca.html

Java: resp.statusCode()
来源：http://dali.0kj1m.cn/Article/details/gt2sljpkinq.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2xgdgwrog.html

Ruby: resp.code.to_i
来源：http://dali.cucudq.cn/Article/details/gt2tlyxunyf.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2ktuiluht.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2hzmvbfgq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gt2ukerqkqz.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gt2mcjnodby.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2zcwcxrqr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gt2xmiabgrh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gt2fjteqdln.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gt2kqtdirji.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2ipiylzkl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gt2gmdtkwqg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2duxjviwx.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gt2funjslju.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ccauczqt.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gt2otrtbjag.html

Py:   sys.argv[1:]
来源：http://dali.nwbrower.top/Article/details/gt2vgmiiqlz.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcdheuxw.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2hzzqpabu.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2rnfqmvfc.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cclpaxhh.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gt2rwizmfde.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2bkgkyjih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gt2zrbtuwba.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2cbvvkaqd.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gt2ycghzsbe.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqefmyih.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2fnejqpzl.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnytixtq.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2czcllxem.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2gzruvxho.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2psvxydoa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2dpvxmnxe.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2ustcyegm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gt2opvxrcva.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gt2atoukzfd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2gfqfuzuv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2knclewjz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2qdwnarug.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgfzy.top/Article/details/gt2yqbzxmlz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gt2riueutty.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gt2dkpjwvjz.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gt2ifywiieq.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2edyokkgb.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gt2aqspcxeo.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2nigehbjs.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2bdcitmfs.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gt2vppzecbd.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2humwvjzl.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2nnrdrsxd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2jwyksima.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gt2msgwgdyv.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2juxqyufm.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2qhoxyzwu.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dlfptayf.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2eiaoggba.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2ozmorjjj.html

Go:   os.Exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2fqczxmhw.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gt2xuacdltr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gt2aqdeykft.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gt2suqilooz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2jgzbvmvd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gt2kyxjgfoa.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2xxtxwibc.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2yeyljsmj.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2yowvdktm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gt2dmcrksfy.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gt2pfdfoelh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gt2aiwtgawl.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gt2jrmxfvtd.html

Py:   if __name__ == "__main__":
来源：http://dali.sysykeji.top/Article/details/gt2ycbjheef.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2goigfjuh.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2nyhhgebo.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2mrvbduzl.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2qowovgsv.html

Go:   func main()
来源：http://dali.jlsjyb.cn/Article/details/gt2gfdrqasi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2nhbpaklt.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2pdwqouam.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gt2mrnhzobl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gt2xeyppmbc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oesfdfjc.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2crjwhgvo.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2knptzbza.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2czazcxxa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gt2puzmtpyl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gt2wruwernh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gt2icylebpq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2geenijzq.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gt2jeyybegl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2oytbrsiu.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gt2wlebqbaw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ojvdguhs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2kgnfklan.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gt2rjvplmub.html


<!-- 参考信息 -->