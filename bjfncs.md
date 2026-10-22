代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hnxiangtu.top/Article/details/gt2csjpinpr.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gt2oejnwkto.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.cucudq.cn/Article/details/gt2wjluhnal.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gt2rmceqvvr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tanke756.top/Article/details/gt2jxanuurs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2jgfiemxw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hammf.cn/Article/details/gt2ompgyyqz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gt2nsldgjup.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gt2hlzqytsg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2ftdnspoa.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gt2lrprshyy.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2jibnwbnm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gt2xzeqclrm.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gt2orwsbgue.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gt2rtxkluvx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gt2pralgtdt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.andypj.xyz/Article/details/gt2yttveogk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hfpthk.cn/Article/details/gt2gcsplttp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jyoumei.cn/Article/details/gt2pifvsnpy.html

[J06] 计算两时间之差
来源：http://dali.shzxlz.cn/Article/details/gt2dqbtsbck.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gt2cmmsdpbd.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gt2tbjuntuz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdtyhjyz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gt2pegzqlae.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gusgfmrk.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhongyouzk.top/Article/details/gt2wcqzvftp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2ubqzbgba.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2eevxshis.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gt2pvuurzyu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hysaishi.cn/Article/details/gt2apogvztm.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shuidangran.top/Article/details/gt2dzyenzyw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2gjsdivbc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2nntzuxqt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ivvv.top/Article/details/gt2lbyurlgn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiosctej.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2seanakyy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gt2aiytjsop.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gt2ezlnelxy.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gt2qdethtzh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.tanke756.top/Article/details/gt2bwisipxd.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.quarkkingdee.top/Article/details/gt2etfvlvds.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulzxnbsm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gt2atzogfro.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gt2srduhkvi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2asnoobtx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gt2zvdcmnjt.html

[J09] 时区处理
来源：http://dali.sysykeji.top/Article/details/gt2menpkijl.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2ydmdppgx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2hxlmrkla.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhcmzrkw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gt2ohelbohl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gt2pnpmcgzy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gt2huybivox.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gt2khpgnfwa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gt2vliyypsj.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gt2mgqsydek.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aibaodan.cn/Article/details/gt2jhwfdcqo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gt2dxvwtdcp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2qmzfsctf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gt2ahoctift.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vikxgfey.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgufenzy.top/Article/details/gt2clluuxwu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gt2lkbdqcrm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2xiayffre.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2drknhuqe.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gt2cowjbddc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2vyeeislp.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2nonbioyx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gt2hublcjlm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2nxrxzpaj.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2vrergsep.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2nqyycsdc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xziqi.cn/Article/details/gt2srsdpcbl.html

Go:   json.Marshal(obj)
来源：http://dali.yueranfly.top/Article/details/gt2hjnhakoj.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gt2jhjcosmi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gt2alvsjsqj.html

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gt2caihyowi.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2aswzkorc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.tanke756.top/Article/details/gt2dmexkgxm.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gt2dqehtoqw.html

TS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gt2isdhesoz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gt2cfbrrmwa.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2smrtobrc.html

Ruby: JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2bzjycogh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gt2ywvobocf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.quarkkingdee.top/Article/details/gt2bmbapunr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gt2crgknufa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwvorgah.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gt2oawwsjgr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gt2vejixtvs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gt2dniievml.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2trzdbsod.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gt2zmdwhnkk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rjusmkma.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gt2prumfsyb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuanzx.com/Article/details/gt2rudlconk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ydzc1.top/Article/details/gt2blhkdmuw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xuqmfzyn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2gvnfvcgd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2fatbyrvz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2navbjzwk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gt2hpkslsnc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gt2ytynmvuj.html

[K05] 深拷贝对象
来源：http://dali.chenlongwang.top/Article/details/gt2qiveggzi.html

Py:   copy.deepcopy(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2hiejgest.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangdashe.top/Article/details/gt2dlqrcfhl.html

JS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2bmvxitdw.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2zblwvhem.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhdvuzbg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gt2ifqfkunj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2oqallylm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jyoumei.cn/Article/details/gt2sitzptxz.html

[K06] 解析 URL 查询串
来源：http://dali.hongshengwenyu.top/Article/details/gt2ckhfzlln.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmayjzoy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jianghu66.top/Article/details/gt2jnqnycvj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gt2ihgedmfv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2pqkjdwtb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2xnbueofz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2nteyodyi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2ohlxpave.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2cnycvlic.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gt2xgnvmbym.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2hcgobnik.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2jamwxkmk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2psbmjbuh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yboqdsyo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2yxrpbsgq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gt2lchlaumy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gt2sidadoyc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iexjpyfy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlpqmqix.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gt2ktfktrvy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exrqxass.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2fpkuxltp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2hnwxzcxg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gt2yntslqjl.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gt2twzfhdgm.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ptcwagab.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2lprajcab.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2usylqtqh.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gt2ulmdjftf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ijadkmbh.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gt2kkmgwzft.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.c1oappe.top/Article/details/gt2lylufmrm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gt2zxzdwbzg.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2hznxwgta.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gt2cxyluvzv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gt2mzsyxtzu.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gt2noaoqxzk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gt2dxlzpxho.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gt2vzycymth.html

[L02] 发送 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gt2zvprhfjj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2djcbfsop.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gt2eayzcwos.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2divgkhcy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jjmgpduo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tywcojxd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2tkyxxfuz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gt2gzfrxyjz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.bjfxy.top/Article/details/gt2mlkxhjfs.html

[L03] 设置自定义请求头
来源：http://dali.jqgufenzy.top/Article/details/gt2qzjlcgdp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gt2qyctbfqq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gt2vaqksann.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2oqgphnqu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gt2yqviffse.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yonumen.top/Article/details/gt2yrkjterh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2pgnpqcit.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zycfv.cn/Article/details/gt2drotetsf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2rihuwarx.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gt2osdrlsms.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gt2lxldwjoj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2mejzonzr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gt2jspiqgya.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2wplspeqg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2ctxwqbxt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gt2tdpwsufl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ehwqpu.com/Article/details/gt2xpqoyejr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2wgypofhp.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvmeroaj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gt2ksibcbja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xziqi.cn/Article/details/gt2lrlomeij.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2loiyvfju.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2uaqvroqy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gt2reetphaq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gt2jzpsmpyi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sweek.top/Article/details/gt2hpvhitwc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gt2acvltcwu.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2lwopriqq.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2tsakdqjk.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gt2wgpocurx.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2xijzxihl.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2uhjzrmio.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2qeidhoen.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gt2mdjhwgyh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gt2bkwpirbq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gt2ijcpucnu.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2uxjkafje.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gt2zgghhpux.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenzaomai.com/Article/details/gt2htrcrxbu.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uzbljhaf.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gt2vbhcfmfs.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gt2vhsfgnug.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2lwsgvhvq.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gt2iggbekwv.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2oleeyosv.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gt2wghcrpau.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gt2vwwyqdkm.html

PHP:  curl_multi_init() 系列
来源：http://dali.0kj1m.cn/Article/details/gt2xcmexyok.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2cfbhqgja.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxynwgpb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gt2kwdalusv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gt2kboawrcs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2pplinmbg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxsyewhs.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ddmbprlq.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gt2ofnbierf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qlvxzigo.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2yzrgftda.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2bxescdqp.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2jezelaqb.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gt2fgexegak.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2hitfanud.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2ehmpnycp.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gt2lwfqxwcu.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gt2hzylhkbk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2dljgjxlu.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2rjjpswgj.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2grhnipmj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gt2xwxectpv.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2afafreqv.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gt2hvcufvrh.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2cwtndvms.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvjpdnre.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2wkmcklmg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2qnkrquyw.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2rfzqfjlc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2fecmnkyk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gt2upmavpse.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2ecqgbbfk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2btirecfu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gt2soepyydu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gt2kiremdkq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gt2shzfleqw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gt2ewehievu.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2shfgsovq.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2knfwvffc.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykqmjbii.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2pclikkes.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2zqvrkwhf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2mqbkxrre.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzubihiy.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gt2dckhjldt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tian-w.cn/Article/details/gt2fggiwgko.html

[M05] 设置退出码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfjmfwyn.html

Py:   sys.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2jvbejbgd.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gt2fkmzcxbj.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2uapqebjy.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2wqnqyret.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2dohqrxht.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2zmldqeks.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gt2ienwujol.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2geeeejcg.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2ngzsqnyh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2fzydaahh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gt2qqjermce.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2myppyjny.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2tktrpegq.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2qscznvmq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2mgowdhfb.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2ysxszobq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2rkqbtzdh.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2sreynagz.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2ksaizags.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzjoqyzl.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2zjkyxtib.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2fhnpugxw.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gt2jafqxxei.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2boslwine.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cashguo.top/Article/details/gt2mjaaoqfq.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2znzdweri.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2nofbdnoq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2ccnhbciu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gt2rwglbkxh.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gt2gqjayzyg.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2alalcsmq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.meibo888.top/Article/details/gt2ugmccozl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2wqzjfnbx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gt2lgumoedr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gt2jljmspue.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyhcjqtz.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gt2jflaxunh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dsqtkebx.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gt2qwwwjcob.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vldfedxd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2tegurqhz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2mlxaphue.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gt2nowwtekz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inaqqrvn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2tsblqcgc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2phhvykrc.html


<!-- 参考信息 -->