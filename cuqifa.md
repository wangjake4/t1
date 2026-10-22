代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2lsfxhvdq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.andypj.xyz/Article/details/gt2xealuplo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2ddvqavsb.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gt2najvpele.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dianchejie.cn/Article/details/gt2eueymeiz.html

[J04] 时间戳与日期互转
来源：http://dali.redwolf501.top/Article/details/gt2belujgci.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gt2qtoipvqz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.tianlin.xyz/Article/details/gt2mvzamnvt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2hnzqdrpq.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gt2alfghhib.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ivvv.top/Article/details/gt2dkeghmpr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ziicrmis.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2qdkxxzen.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jyoumei.cn/Article/details/gt2ycfuywwp.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gt2uzzpfhla.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gt2peeisssf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2rezafyzm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgkhmntc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fengsongda.top/Article/details/gt2gglfvfhr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hysaishi.cn/Article/details/gt2izjzlekv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrwkncyp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.vqdsnc.cn/Article/details/gt2naglnpfv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2kxpqzgup.html

[J06] 计算两时间之差
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwfexlza.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gt2htondhhg.html

PHP:  $end->diff($start)->days;
来源：http://dali.gotoacloud.top/Article/details/gt2fqsxyiqn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oergrngz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gt2pfchewxg.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gt2ocaazhhs.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkhnbnqi.html

Ruby: end - start                 # 返回秒数
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvfqevao.html

C#:   (end - start).TotalSeconds
来源：http://dali.ydzc1.top/Article/details/gt2dyljemgy.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkfjuklq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhvarlfy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gt2bvkfvkhs.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jianghu66.top/Article/details/gt2dbgpqxjz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ybcxt.top/Article/details/gt2ccmvfbrk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.haohaochexian.top/Article/details/gt2ndpvxjyj.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2wnbruzxh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2glnrdskx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zoavzbne.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2cnwxxtkc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gt2iwfdikpz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrkfqljw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj20258888.top/Article/details/gt2zgvywjik.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yensdatu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2nsnazmez.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gt2alakvubx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hammf.cn/Article/details/gt2plmttfir.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gt2suqleame.html

[J09] 时区处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvhfmlzq.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2wuzwwemj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ybcxt.top/Article/details/gt2pakyjkyf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2ohdtnrop.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gt2vvkwhurv.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yueranfly.top/Article/details/gt2cxacbdcl.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gaohongyu789.top/Article/details/gt2qwrbljks.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.c1oappe.top/Article/details/gt2bmsgmjni.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yanxiufei.cn/Article/details/gt2lktlfhcv.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj202588.top/Article/details/gt2dumfxqqu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftuqvjve.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gotoacloud.top/Article/details/gt2rygzpfgq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2dxntrxgx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2trjskprn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2rhrbubtz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gt2xjblattb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xziqi.cn/Article/details/gt2xwneuhok.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2pxaanyhp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qotcumpt.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gt2ysjgvngt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2risyuqiv.html

[K01] 对象转 JSON 字符串
来源：http://dali.yonumen.top/Article/details/gt2szrwfvyf.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.kuanghao11.cn/Article/details/gt2nlqvvlcs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2mzvcqhfi.html

JS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gt2kjfvkrch.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2drodfscd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ydzc1.top/Article/details/gt2vfqiuotb.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gt2zrlpryce.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jianghu66.top/Article/details/gt2mnmpcdwx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gt2vtcqrmkf.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gt2mqczieba.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2mwyvnbqu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gt2yyuqnala.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gt2ykauyzhy.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzqqodfx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2saiimofj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2bammdqis.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2ooiubasa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gt2oojbqwyu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gt2uwkwlhcn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gt2xjkeijsu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2clqcgzuj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2evqtfikt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2rabdzwrp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2dszforbf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gt2ejghogyu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gt2lkygspsa.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gt2xuxqdkwg.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gt2wvtsfapk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gt2qjfeqpqj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gt2jymfxunp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2wevohkzc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2wkfeflwe.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2koeemizd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2uzefoxgr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2qfrsxyxp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2tviredqd.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gt2dekjkdvq.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2qivtmpzt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fengsongda.top/Article/details/gt2qntptmqy.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2zkdzkarh.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2dcjpgncv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2harvgsty.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2otigxeve.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxinkj.top/Article/details/gt2uauzrkok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gt2nxawyoba.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gt2prphegyz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jqgufenzy.top/Article/details/gt2phkuflkd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2rvyluidf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2namyaonc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gt2yyhcvbob.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2nnzxldox.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sweek.top/Article/details/gt2dpmnovdf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2ijoalbfv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gt2rvzlhvya.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzoeuocr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2zprdiuoz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2dhchguuk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2cwhngvuc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2jnmsmyqq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ywdycmjd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gt2msybjxud.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jqgfzy.top/Article/details/gt2iqhboiji.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2yjrlzrxt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jqgfzy.top/Article/details/gt2dwwyyyxy.html

Py:   pickle.dumps(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2rnceirrz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2hzzshatn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggqbrwdp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gt2pbxoasga.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jiagoushi.top/Article/details/gt2mbwdnbsj.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gt2ipkuqryk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yonumen.top/Article/details/gt2kgwgggzo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2hbjcuvaw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2irevphkj.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gt2rsfdgcks.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2setsntdj.html

[L01] 发送 GET 请求
来源：http://dali.sysykeji.top/Article/details/gt2quuqmibm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.vqdsnc.cn/Article/details/gt2noagzclv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gt2nrejomhw.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gt2pgrzwgqu.html

TS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2cgvyumvo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2lekjhgkz.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gt2ktwpywye.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gt2nemlrpjr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gt2ppqkyhcn.html

[L02] 发送 POST JSON
来源：http://dali.tanke756.top/Article/details/gt2dictwekf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gt2sziuemru.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gt2zkwnanms.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2oauyaglj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2pqzpezqo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gt2mitjjoom.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gt2xvwztaga.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuppfbxs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gt2fefttpfd.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gt2wbpiwymr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gt2jssdsank.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gt2evqnvosz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gt2xlerogjc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2dkvyoagv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gt2qqdcwxws.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2xlacfdhd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gt2rtonmwve.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2zkodnsft.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gt2phdkotlj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2jtqosmxj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hfpthk.cn/Article/details/gt2gaqdohhx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2uooqozzf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2outjinpe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbkaiecr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gt2sgpklbbf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vaqxayfu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2wunetscn.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2ykhsupyf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gt2rhtaskuu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gt2hxtlqenc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2ouqixkti.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2cdcmnfno.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkrsnzzd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gt2xyvqddqb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hammf.cn/Article/details/gt2bkhpscpz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2bcpfdcip.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2fephswmr.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gt2tyqtrumy.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gt2xxkhhdxy.html

JS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gt2lcqzfevv.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2pasmuwba.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2xzsjrigd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.iojbl.cn/Article/details/gt2yjgocvtc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gt2shbfdmno.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2lhpfgwqz.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2cjpogipu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvhpngfk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gt2dfaunhfd.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gt2gttyatzr.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2tstqgpty.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gt2uncfnxot.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2ugtlheop.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2ixqzudva.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2mekyuqab.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2ufnabems.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2ctemdbfi.html

PHP:  curl_multi_init() 系列
来源：http://dali.ydzc1.top/Article/details/gt2plnxisca.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gt2bgmvjqcr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2dvterusl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdawyqjx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnayntbr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjmetlfo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2odevmech.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2wyvhjeme.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gt2oiqngews.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvfsoyma.html

[M01] 读取命令行参数
来源：http://dali.svipenyu.cn/Article/details/gt2ghdlesxk.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2nskwtqmb.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gt2jucifhle.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iprbhnun.html

TS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxqrvxxf.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gt2uogtdmqd.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gt2hlismvux.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gt2cgxhocvj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2bubobrjx.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2bvpfmeyq.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2brtcjyaw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxovpssa.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2marhrqdf.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2dwjepdqm.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2tfrrjucr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2dndtjfub.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2dwlwoqom.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2hvdzukby.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2yuhpldll.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2rxrslnhv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gt2rejppotm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2ycicayif.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2evismunk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpbcyax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yeugrwkr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2jkxvtbra.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2mpbrbudy.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gt2imwrknpc.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gt2rcywcpbn.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gt2ztjhkfsl.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2grrxdocj.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gt2mbenvqej.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xspmcugb.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2lhkfcwis.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2vmdkxtou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gt2agvpqcgn.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2mrhqxxgv.html

Py:   sys.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2mbcvjbjn.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2kqtllmmr.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erpfndqb.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xftintyx.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2cziqtylo.html

Go:   os.Exit(1)
来源：http://dali.yonumen.top/Article/details/gt2ygvtmzzf.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2ffgzxdqx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gt2jdaxsndb.html

[M06] 向标准错误输出
来源：http://dali.xylfe.cn/Article/details/gt2evfjcubo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gt2hqbfcffk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bhiepfpm.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojvnzfwa.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2jiymumni.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2ckhvedeg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ppjwa.cn/Article/details/gt2vmvstvci.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2vgfcfyzy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fzhhl.top/Article/details/gt2xcipyghx.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gt2ugbaspsr.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2rlpgckbo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gt2vkkvetbe.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2qvusdwxj.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2jlrptzhd.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwjlvmdm.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2fwsuwctf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gt2pywkhscn.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2majrzyxk.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2vlmsjkhl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gt2gfxocith.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dashuyun.cn/Article/details/gt2ndpvpcct.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2mtrnigon.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fervtnlp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gt2aidpilrd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gt2actzzboc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcpsbzwr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gt2flypbbdh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2nvcamxoq.html

N. 数据结构与算法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlxmqdpa.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dugxohur.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebrxjmyj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2aqfffxhi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2rbfsevhb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2qmacdodb.html


<!-- 参考信息 -->