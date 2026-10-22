代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ybcxt.top/Article/details/gt2vohnpgtj.html

[J04] 时间戳与日期互转
来源：http://dali.jlsjyb.cn/Article/details/gt2kvejeudt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2fkdnvynp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ydzc1.top/Article/details/gt2fvbfxtzs.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.gzhubu.top/Article/details/gt2ffponjli.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.dashuyun.cn/Article/details/gt2olmoflqv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2uhodzzdp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2ztclhzgk.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gt2efgmeamd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxzhpxvz.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2gfjzjqxt.html

Py:   now + timedelta(days=7)
来源：http://dali.xziqi.cn/Article/details/gt2ehebuuwl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.daria6918.cn/Article/details/gt2wecyxvqm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gt2qmfwxqcr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2cwuwdext.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hammf.cn/Article/details/gt2oxwcsaxe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgfzy.top/Article/details/gt2sagyyugt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.316326.xyz/Article/details/gt2njwjcirr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.vqdsnc.cn/Article/details/gt2smslmmdp.html

[J06] 计算两时间之差
来源：http://dali.hnxiangtu.top/Article/details/gt2ikfmvlbt.html

Py:   (end - start).total_seconds()
来源：http://dali.yangfankeji.com/Article/details/gt2pfnvsujn.html

PHP:  $end->diff($start)->days;
来源：http://dali.mhx1999.top/Article/details/gt2uocbxhrf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nwbrower.top/Article/details/gt2kklxjmrj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2ucrmkbbo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.0kj1m.cn/Article/details/gt2tzdrszka.html

Go:   end.Sub(start).Hours()
来源：http://dali.fzhhl.top/Article/details/gt2egwdovkx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gt2haumjavn.html

C#:   (end - start).TotalSeconds
来源：http://dali.hfpthk.cn/Article/details/gt2gpbratsk.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gt2kjrnylkj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2kzkvnvxd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gt2plkienlx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2orlcpoan.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2fftaiqsd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.c1oappe.top/Article/details/gt2qurvfhyq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gt2xguixlxb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gt2ixpcfuzm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gt2ktlekivx.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gt2ctyurrvc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.wangdashe.top/Article/details/gt2hfceqkim.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenzaomai.com/Article/details/gt2avmycwym.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gt2jheovwmc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nwbrower.top/Article/details/gt2opybrgsa.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.chenlongwang.top/Article/details/gt2jclzyhep.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fengsongda.top/Article/details/gt2fptypjxo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangtech.top/Article/details/gt2azoukppo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gt2xduzidod.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gt2knomhbxn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhoulong.xyz/Article/details/gt2xdngnnvl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gt2jsvakxno.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2boypzmlh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhengqikj.top/Article/details/gt2gqbqmrpm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gt2szkxrota.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gt2lqejmhfj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gt2mlwsbthy.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvdmusyy.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gt2tydlrjnp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gt2stokhojq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.haohaochexian.top/Article/details/gt2pwmjiver.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnqzz.top/Article/details/gt2vyaizxuc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gt2ozdsoloc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gt2qchgzujr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cucudq.cn/Article/details/gt2geezlsnz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gt2ezerhgnf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2uisujokx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2eaurtrkq.html

K. JSON 与序列化
来源：http://dali.yanxiufei.cn/Article/details/gt2azrvmyag.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2spaqshfz.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2toctnjvu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2nnnvyfwb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2qzdevdeh.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alzhllot.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2xjegbcmq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gt2ucihwozb.html

Go:   json.Marshal(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2rqusoqez.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aibaodan.cn/Article/details/gt2hsqnstom.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gt2jhgbuiea.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gt2cigpxvle.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omzlruka.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gt2eredlgqh.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2uhutglyv.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2fclhayuj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2oxnrzhiy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gt2ouiamcti.html

Ruby: JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gt2runabkdb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gt2ygepubqj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2zuhoteeb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iovnghtq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2bcgxmuwm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nttjvkgi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gt2eeymzjtc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gt2fvexsvhk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2eslhklyk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yvedp.cn/Article/details/gt2pyglplrb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhongyouzk.top/Article/details/gt2vnhsmyqo.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gt2oaustuyi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gt2lhcgclyv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sweek.top/Article/details/gt2wdkteyky.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2ukjjsrfe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2hbcbvnkb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2aeuyqpck.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2esexudwn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugdnuffz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gt2rljmnstg.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gt2nguywjyz.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gt2nayowltc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.0kj1m.cn/Article/details/gt2tmytiffs.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2vflucnrc.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2vdzdeatn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gt2dywrefou.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gt2aexurikh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2pdnjlvly.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daxiang520.top/Article/details/gt2mbjbjzkz.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrooprfq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiuljxd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2utjhsuli.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gt2slhqielh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2mkkoejon.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvqnfmzc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gt2gonymvyr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2wxkjrosd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2awjckiyn.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pllybtjt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2iywmhjvc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.snrcjt.cn/Article/details/gt2aakjnnzj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2poanohqx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2figaqham.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2vzviexxy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daxiang520.top/Article/details/gt2nqrkcyxw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gt2lapawprs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2uirnmuuk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gt2hxrpanpe.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gt2dougrxdc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2elavujcn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gt2khmfwwur.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gt2vtorwlwo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2anwnvyfl.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gt2wvgbgsqp.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2incvvjqd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gt2dvsteecp.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2zhjnuhsc.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gt2pcnjbwmc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2skncwiuh.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gt2btppgsms.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hammf.cn/Article/details/gt2kgzmklys.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gt2wfbefpuk.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2xqpvjyll.html

TS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gt2rrydjthi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gt2ezbtebls.html

Go:   resp, err := http.Get(url)
来源：http://dali.andypj.xyz/Article/details/gt2puzxwkpi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.andypj.xyz/Article/details/gt2lrxugguy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gt2nrvtejtj.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gt2dxxniycv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gt2htsvcraw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gt2hxfnlzlr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gt2fsceuxkb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2noermfrv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjogtfcx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj202588.top/Article/details/gt2fvmgokst.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gt2yikmmsdm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2jsmninyy.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdstxtdh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gt2opejuake.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cdnleiting.top/Article/details/gt2mzpakfbh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2evhorfdw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2xeeybcgc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gt2zdbokazh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2ibrunjnn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.9152youxi.cn/Article/details/gt2dkcurzkp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gt2fswtpbad.html

[L04] 设置超时
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sffskuhj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gt2legiftmp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2azhihtoe.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2mlstcump.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shcrlvav.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2hcqtukga.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gt2vcmczwci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gt2jrbzdxaq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gt2shlmyccc.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2gymtpklm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqdruuww.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gt2vnpkfgow.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2ihwfmnka.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2dsixfkkm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkaxdmrq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gt2jygvvwlk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2pqyhlkvq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjtjutev.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gt2swkasqwp.html

Py:   resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gt2aahezgdy.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bytbbdan.html

JS:   await resp.json()
来源：http://dali.cheryme.top/Article/details/gt2ynbithuk.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2yzaxlvxl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gt2yplnpgxi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2usaywrbz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrgpjyir.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gt2bbvuoidr.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2xivvacyw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gt2hiqxjlht.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elsugkcd.html

JS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gt2ornevowx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2sqbpkabz.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycbmtlit.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2kutwgdic.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2tcdarbuk.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2intnfydc.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2mdogzwdh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gt2rabfqnbe.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gt2znkoqhyi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gt2awcuucrp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2hotvirsr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gt2thrmtqfw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gt2piiluepw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2zfnindnk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gt2dlpywdjn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jikanxjo.html

M. 命令行 / 进程 / 环境
来源：http://dali.xuanzx.com/Article/details/gt2pglrcomi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ihqfhmnq.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2ofzoehtj.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2aghrkttm.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gt2lgesaldx.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2abhoylbr.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2ukoodnim.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2epzkvqid.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2ichbnocf.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2snpdfpbw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2nxtzchtv.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2etpdxywa.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gt2sqbogbim.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2daxbocmf.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gt2bassxzzv.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gt2qlmsukgi.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2xivgpjyo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2ozqlgyzs.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gt2ndvxsgtj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2jpuauzeg.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gt2sprhqzxq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gt2wstiarvl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2plkackzl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apukynry.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2tktvxhgv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gt2ogggfzuj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2yptexbdq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2cdikgsfm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2dgytrixc.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2zfviibxp.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gt2tskeukeu.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gt2sddlwewv.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2zfhdzcaa.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gt2ipjafepc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dilwizoe.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2ikhfsqoe.html

Ruby: Dir.pwd
来源：http://dali.jlsjyb.cn/Article/details/gt2pkonrxbx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gt2geohifaa.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gt2ysltykot.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2aslyjkdj.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2fihabnos.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2wrnsnhdz.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2ytxvwrsg.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2cponyabd.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2eygqglll.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2gcuidtnu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gt2lpmgjvyc.html

[M06] 向标准错误输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkhtgtnt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2imboeqnn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gt2udbulxnp.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2tlanpxdv.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2qefuwbjt.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gt2lkdjpktb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gt2vqztuemd.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2oitbdjuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2temvktsx.html

[M07] 判断是否为主入口
来源：http://dali.gaohongyu789.top/Article/details/gt2jljyszhc.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2sdasackp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gt2fitqkyvw.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tznpklyp.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2nojidduf.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gt2tihnaxwo.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gt2nppewuwg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgufenzy.top/Article/details/gt2jizrnewv.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gt2kavgqkmx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nddfptqj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gt2mvjlntur.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2mbfmtqbh.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gt2dwvrtqzj.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2ynlukuex.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gt2vnimajut.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gt2eakrjgwu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gt2kposxlbn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gt2ndcjnxyx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xwmydvjm.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gt2ktybyztz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2yzltfkem.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gt2gqvngwcp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2oxdmbeix.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byvhiebp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gt2bnnyssav.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2fnwxgyjn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2mftanzpz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2niztayff.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2zhhbblfj.html


<!-- 参考信息 -->