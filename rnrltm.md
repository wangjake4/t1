代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gt2fhfhxpoh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlydmhnl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gt2ofnpxzxf.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2bvstxdto.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hysaishi.cn/Article/details/gt2xihbwrqo.html

[J04] 时间戳与日期互转
来源：http://dali.ybcxt.top/Article/details/gt2ybznyrcw.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gt2qtoupjwf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gt2fqvlapph.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gogol.net.cn/Article/details/gt2qvlzwquo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwdxffni.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.aizwys.cn/Article/details/gt2soakixzz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2zaeovmgi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.mhx1999.top/Article/details/gt2dfyrzulx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ytzsdooy.html

[J05] 时间加减（加 7 天）
来源：http://dali.ehwqpu.com/Article/details/gt2smbayuhs.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgufenzy.top/Article/details/gt2tuxmfneh.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinqigufen.top/Article/details/gt2qwmqxewj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj202588.top/Article/details/gt2ratvwllg.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.c1oappe.top/Article/details/gt2szymrhbb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gaohongyu789.top/Article/details/gt2jszdydwn.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2kmzitqbb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gt2trlavabs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gt2bilmvpek.html

[J06] 计算两时间之差
来源：http://dali.chenlongwang.top/Article/details/gt2vjepucsr.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gt2vbueotab.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gt2jigpxxbh.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxpwpfjc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2pfsrtmrl.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2kfqczwsv.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gt2njglacvq.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2bjzzzqhc.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oyhvuyby.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gt2aldvxwvn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2ncrvuvzf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hongshengwenyu.top/Article/details/gt2deemxpkt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yanxiufei.cn/Article/details/gt2jappybho.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.kuanghao11.cn/Article/details/gt2hxhmanbt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hywenlv.cn/Article/details/gt2qkvagvfi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2yxyqgyjv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cdnleiting.top/Article/details/gt2sgssdarh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzzfhwyd.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gt2vvopkfil.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gt2tilgdclb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sysykeji.top/Article/details/gt2kvafixgw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cdnleiting.top/Article/details/gt2kqnvrkrd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gt2habwiexi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xinyue.icu/Article/details/gt2tuczlaxj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gt2gyurmzpz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gt2shlxsqpw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gt2adkwtygf.html

[J09] 时区处理
来源：http://dali.yongpay.top/Article/details/gt2hmukfunj.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gt2jzwnzsrb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gt2fsyvqies.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2hbdigeug.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gt2xhncjvan.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gt2egqruwnx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gt2cozrrgem.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gt2jmfuzroy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyrhdmfx.html

[J10] 取今天 / 本月第一天
来源：http://dali.xylfe.cn/Article/details/gt2fknfkakr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wxipjgfz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jlsjyb.cn/Article/details/gt2oktcpxiv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdiecjgd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2youclhbm.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cheryme.top/Article/details/gt2bacmwutr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shzxlz.cn/Article/details/gt2dixywqfd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj202588.top/Article/details/gt2hngfybmd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hysaishi.cn/Article/details/gt2igfjbdku.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2lvnrpwfu.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gt2klasioat.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2iotmuiol.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2gnzjrftg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ppjwa.cn/Article/details/gt2dnpktdra.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxuanxn.top/Article/details/gt2iolneqsv.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtfqdgi.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2bmqjpvmx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2ydqivzxi.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2dqmxlxhv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gt2ftrqrxdq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aizwys.cn/Article/details/gt2lzwnqybd.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2wqgnyxvz.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gt2ayniygjm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gt2pfostawu.html

JS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2agucdqzi.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfoachpc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.havefunace.top/Article/details/gt2ahqhouei.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gt2raumshxt.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2dhvvqjjh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2qdkkbcxu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gt2rlobuxcz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2ekttpkko.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gt2chhxlcxr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2anwbgmct.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2gpwyymzh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2ejatgszh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2smdfiias.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2hpjklzrp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwfbgqjn.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2mihqfych.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2qceopzks.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agkwoafj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gt2dmjhbmim.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2jwdnjbtd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gt2htddzfwe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgfzy.top/Article/details/gt2wdabuusj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gt2ulpkwxxy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2aymcjadn.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2nlnrphfs.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2kqsaxlyj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jyoumei.cn/Article/details/gt2anulnfgc.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2zvwpnzcp.html

TS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjzbyrvp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzntkslm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gt2fxhdphwh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfpdntvl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gt2amzgmchw.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gt2czcgtndw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gt2cmkqwsqd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jiagoushi.top/Article/details/gt2zflyfwiy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2ghmshyqd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpfssfwf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kewfuewk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2prhykumg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gt2ipldaoiu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2erzpargv.html

[K07] 进制转换
来源：http://dali.gotoacloud.top/Article/details/gt2lnkovwtp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2pzoogbpo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2vbxkhnwa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2yuodmuyp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2fpjfdhug.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsrsscrl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gt2ylvadpdc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqtzjatu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2grlssted.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gt2cemhwigk.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2hjvpwjmc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2evlqzrjn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gt2ybnxgfjd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2lnbkwqvw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2gploibqu.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gt2zasudzqd.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gt2mqxhhsap.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2vvjbnfnd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2nxehahfk.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbcicynz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhfpnfgg.html

[L01] 发送 GET 请求
来源：http://dali.ehwqpu.com/Article/details/gt2gaueocof.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgfzy.top/Article/details/gt2tisnvpki.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gt2tvprhekt.html

JS:   await fetch(url)
来源：http://dali.svipenyu.cn/Article/details/gt2lhfvycbp.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2xlylqhrc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2norudyzz.html

Go:   resp, err := http.Get(url)
来源：http://dali.fzhhl.top/Article/details/gt2momlfogu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gt2ociwxcfx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gt2nqndhvyr.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2pkchkptx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gt2jpgahjvq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2hsfabfae.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gt2efeiuvzi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2vikhymsr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gt2qzkxsgyg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lygaikjm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fzhhl.top/Article/details/gt2wwnrjrva.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gt2xkthmfqm.html

[L03] 设置自定义请求头
来源：http://dali.chenlongwang.top/Article/details/gt2tzgszghu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gt2stipdlpa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ehwqpu.com/Article/details/gt2dxtmvozm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2pjhslwnb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxahmvrm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gt2klpubrpf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbuakohi.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2dguzcyhf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2lfkiaepz.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yiqsxlhx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2gquocvsw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2ixygvbrv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2yxiwpard.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2vmybwjco.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xziqi.cn/Article/details/gt2yfzfffau.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2gyzhdukm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zdqjudy.top/Article/details/gt2zxglxeda.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gt2labhgujc.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gt2oqohrkai.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gt2rjthusbx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gt2gmgcrosd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2qjbiachq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2mlbnymab.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gt2fjnwthxd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gt2aehxsmvp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gt2bdajpdfb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2infsroed.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gt2xmtcwjbk.html

Py:   resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2umtcrdzq.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gt2udqwjuuw.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2qgeepnot.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2xszlmvmz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2idvzqrzb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gt2ridsjthe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gt2cggxrxvh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2zlzbgqaw.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2kxfkdjiv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gt2khlowinx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gt2itzryutm.html

JS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2fjhdvdfc.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2dhwhchaj.html

Java: resp.statusCode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbbohuol.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2iynazufl.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gt2qlxhiqpw.html

C#:   (int)resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcmtcjxb.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gt2pvbhhtlb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2uyrlslkj.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gt2hzffcvyu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2kogooafv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2ekiaomnv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gt2vgehwscv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gt2iavpccug.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2yuxbbmyh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2qqgxegck.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fqcohznp.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gt2qpcbevlf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2gzdkcnnz.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2wumbtvzo.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2lunljktq.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2uncqycxh.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2jqphfwmm.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2oirhcxfx.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2xhcfhdyj.html

Go:   os.Args[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2rzvbccwb.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwthdaud.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2matjigul.html

[M02] 读取环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2dihmgfhb.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2kehrmowp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2xhduqxit.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2rwgazuhu.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzshqfbo.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2ytxrhamw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2cqytfckz.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gt2hjeguglv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2chsdabks.html

[M03] 执行外部命令
来源：http://dali.wangdashe.top/Article/details/gt2blnucwym.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gt2vwziqkzm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gt2cnfqfccg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gt2ayhyavrp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2vyiiiakv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkaeasdj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gt2rjvnjkww.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2ofhmescx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gt2robfmzcb.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gt2ksnedrnz.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2eiwxdvsz.html

PHP:  getcwd();
来源：http://dali.fengsongda.top/Article/details/gt2awwxackf.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2vjofulfq.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2yjboeakn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gt2yshswzqj.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gt2ognauiqq.html

Ruby: Dir.pwd
来源：http://dali.nwbrower.top/Article/details/gt2xlnaenwh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxobtuzc.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gt2szihkdyo.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2mrtqzpkr.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hahzhdvw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqppawv.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2yippqevr.html

Java: System.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2fbkrvkgv.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2vuzlqbav.html

Ruby: exit 1
来源：http://dali.fengsongda.top/Article/details/gt2kpyezzns.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gt2qnumotso.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gt2kxjnhqrh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yonumen.top/Article/details/gt2gxmygynq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gt2zuqggvma.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mphdiqej.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2fouyjfox.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gt2rsmbuqmu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekbscrnp.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2hsccjduf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yongpay.top/Article/details/gt2xcrtjhfv.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gt2yrnjxfoy.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2touwaegm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2nwodpouc.html

JS:   require.main === module
来源：http://dali.wangdashe.top/Article/details/gt2zyqjxosr.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2ocsgocfx.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gt2hqqpfbjo.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2sohvyonc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gt2gzjfvcli.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gt2diqmohri.html

[M08] 获取系统与运行时信息
来源：http://dali.mhx1999.top/Article/details/gt2jrhoubsu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cdnleiting.top/Article/details/gt2pbyxniqo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gt2ixatbzvd.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvakzaau.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2eavnenov.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gt2fgdleudt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gt2ozxtwmxn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2itcyybtu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gt2cavnojgd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2kbaslglk.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gt2fablvprr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hnabfium.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gt2xqqvdjtu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2qsvdnagu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guannengcc.top/Article/details/gt2nyluvpba.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2kbesvkrv.html


<!-- 参考信息 -->