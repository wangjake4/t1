代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yonumen.top/Article/details/gt2acrrcrzm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nilqwrny.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258.top/Article/details/gt2shccepav.html

Py:   now + timedelta(days=7)
来源：http://dali.jyoumei.cn/Article/details/gt2gpxzfjtz.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.smart0.xyz/Article/details/gt2vlbvnhya.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gt2ldodwmsp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.aibaodan.cn/Article/details/gt2dhwwoymf.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.andypj.xyz/Article/details/gt2nhjilcpd.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gt2kptnxkem.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fengsongda.top/Article/details/gt2sflghsra.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gt2rkrzxflt.html

[J06] 计算两时间之差
来源：http://dali.smart0.xyz/Article/details/gt2vzbfwsfo.html

Py:   (end - start).total_seconds()
来源：http://dali.sufxvd.cn/Article/details/gt2rhmsatec.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gt2ijfwbgoc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gt2txisezlc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.wangdashe.top/Article/details/gt2sdpowzhb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhongyouzk.top/Article/details/gt2dpcbpvhf.html

Go:   end.Sub(start).Hours()
来源：http://dali.jqgfzy.top/Article/details/gt2teteygti.html

Ruby: end - start                 # 返回秒数
来源：http://dali.dianchejie.cn/Article/details/gt2rqhfxmby.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzwolfyj.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gt2nffvlzsv.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gt2nlcwlnsi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.0kj1m.cn/Article/details/gt2clbifhmy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gt2dhjhhrrj.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.nwbrower.top/Article/details/gt2xikmbpuf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gt2zgzhtfwz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gt2fkbmescp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.c1oappe.top/Article/details/gt2qmetaevl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gt2dmeeerpd.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gt2kqkaiark.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.aizwys.cn/Article/details/gt2bwsxgjhm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gt2buvicwid.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuanzhike.top/Article/details/gt2pafvigoq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cashguo.top/Article/details/gt2ltlpjujk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2dbigunxb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigfzy.top/Article/details/gt2ysraemza.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xziqi.cn/Article/details/gt2ymaiquba.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjwjmron.html

[J09] 时区处理
来源：http://dali.cucudq.cn/Article/details/gt2wfmgrkgi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gt2iouibuje.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gt2becqsxkk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gt2oybalzte.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gt2srdakvgw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2apsqpctg.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gzhubu.top/Article/details/gt2cvslzyem.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.wangshuangyany.cn/Article/details/gt2uaqmknxs.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sweek.top/Article/details/gt2vpupffqu.html

[J10] 取今天 / 本月第一天
来源：http://dali.jyoumei.cn/Article/details/gt2yljbnayp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yvedp.cn/Article/details/gt2ixebfozq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gt2vvfkwtai.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gt2qlvajvda.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2jvvsnwbv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2ztpnkskk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigufen.top/Article/details/gt2rzycrmdc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.meibo888.top/Article/details/gt2rnzcvvzf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gt2xdyjbcqy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2gjuntzjj.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihodhvdg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2mvccplam.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkanktaz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gt2qtxrpyjp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2dpuljbnk.html

JS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2cmwmdeym.html

TS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gt2eextivpv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gt2twyysxdp.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2pnaeende.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcnkszeo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2vfvlyfnz.html

[K02] JSON 字符串转对象
来源：http://dali.gzhubu.top/Article/details/gt2hsctmajb.html

Py:   json.loads(s)
来源：http://dali.xuanzx.com/Article/details/gt2hjwkvspn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gt2ldfsgene.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2xgzlpnga.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ivrsfwzh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2aedvuhdf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gt2jfnhcerx.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2dxygipcr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yuhvptsg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gt2ibsaivwq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigfzy.top/Article/details/gt2gaffbyzk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2obibcxca.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gt2wfzvmtct.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2cfslwebz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gt2myoqzeev.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2ygtruqui.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqllfily.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gt2vvotzbfe.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2cpjykvdg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2chdcfdfe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2fxmcxdrm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gt2lsveprin.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2rmmjsmhc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2rwsqtlru.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2ttwvgxgo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aihfgklc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2xlqtstok.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gt2zbwvtrpi.html

Py:   copy.deepcopy(obj)
来源：http://dali.jianghu66.top/Article/details/gt2xmlvsccg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gt2mbibuivw.html

JS:   structuredClone(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2stwkemjm.html

TS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2xaxfdmqt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zycfv.cn/Article/details/gt2yxyfuudm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gt2neexbtmt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2whaabwmn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gt2vuvsbxaq.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gt2zbrtdqbq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2tnhknfqx.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gt2vyhlkkwk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.316326.xyz/Article/details/gt2prhvutgo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2yxftjbbq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2xikplagn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gogol.net.cn/Article/details/gt2dyzlvral.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2pkganmsr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2zwqbgzhq.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gt2odntcnqf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2abnvzqhe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2nabonyxn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ryopvwdb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2ygzkvbis.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2quirzoqb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gt2xxwmmahp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.kuanghao11.cn/Article/details/gt2spxyaxok.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gt2eekfgbmy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yvedp.cn/Article/details/gt2ujmhvkhm.html

Py:   pickle.dumps(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blftzrlk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gt2fvznhbhp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gt2nhcsgmcz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2snbeuota.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gt2ubmzyizf.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gt2zmtfqdrs.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2fawxdgrc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2vizcgsgo.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2npauatho.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtibhqf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2wvlqmuir.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2frvjrroq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gt2fxvohluk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gt2dkbaembp.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gt2ahxkorcc.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2rbntfskd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gt2jkiyagbc.html

Go:   resp, err := http.Get(url)
来源：http://dali.c1oappe.top/Article/details/gt2efmnxirv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gt2iulrkxxb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gt2qsqijohl.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzvnsuyx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzodgukn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gt2sgfofzzu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2surfjbkm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2ocqsllnw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdnovxwl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2wjngbqrq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gt2wgjleklq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgjnyokt.html

[L03] 设置自定义请求头
来源：http://dali.bjfxy.top/Article/details/gt2jnxjruny.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gt2xghxcabt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2tmbpyryn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ljnqwaoe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2aeqdhvlk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tianlin.xyz/Article/details/gt2eupiwfcq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2cwibarld.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pkntoapu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gt2wygrosty.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gt2dyqgbdwo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcluqyxo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gt2vwtmewzh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2fbaxmeyg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bosnopct.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cucudq.cn/Article/details/gt2rhnpkqhy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gt2aahygegh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhrcsqln.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2xarsasgi.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gt2fxsyosit.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gt2ezdsiupy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2fogqdfst.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifnvanpl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2qmknsgwm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hfpthk.cn/Article/details/gt2aulpitcp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gt2emqkfkpk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2jviwjnja.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2szggmuyj.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2hiuleuaj.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2dwivjwcj.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gt2pjncbdtu.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2xlqvltpj.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2xrkfgsca.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2bezzkyxl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euzsnhow.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gt2xqpgynyg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gt2zbscioic.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2egnlplux.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gt2ckanfkit.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gt2nndsnhux.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2vnrhpioy.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2zfrnvquj.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gt2bzffdwci.html

Go:   resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqiruqzk.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gt2outuxtib.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hryuporq.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gt2dohjqlpz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.quarkkingdee.top/Article/details/gt2mejeaood.html

PHP:  curl_multi_init() 系列
来源：http://dali.cdnleiting.top/Article/details/gt2zzclssad.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gt2ehbjkbau.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2mgipakje.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gt2hpjkbzmp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gt2dmelmlet.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2hhcppwls.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2srtgleqe.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvpqghll.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkqadzxu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2hconumjg.html

[M01] 读取命令行参数
来源：http://dali.hysaishi.cn/Article/details/gt2vlnelell.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2iqqiizvm.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gt2acblpntk.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2rvxocnov.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2mgjlpjkz.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gt2mbdbywhy.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gt2lfospolf.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gt2xfhaeaou.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2sdgtitfc.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2zoqtprvs.html

Py:   os.environ.get("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2xofusguv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2apxwgmfj.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2yinpdkyu.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gt2ufczndzw.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2thrjykju.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2yjssroyp.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gt2moydztuo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gt2fzxjbutq.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtbkvbmg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gt2bnnphovd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gt2jxixsvjc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lehtynnk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2hjvvpmkn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gt2ojkolnqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gt2eycppszv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2uiciltky.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2ajqutqul.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gt2fnblfnck.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2vsqtugvq.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gt2xilpwjyz.html

JS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2wtwizptn.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2nkjydusc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gt2fptrsrpo.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2baqnxenr.html

Ruby: Dir.pwd
来源：http://dali.meibo888.top/Article/details/gt2vdwbyzkv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2mafdzrxa.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gt2ccgifrty.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zcoqijtq.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2etgrrnxv.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2kiygbyez.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2izggmrsd.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2icblfhmk.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2wawdiemx.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gt2hqodidnm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2feagqxkv.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gt2kfwhdloy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gt2bdhdudou.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gogol.net.cn/Article/details/gt2tgitrkpf.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2kwucfnxy.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2swnrbfca.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2tomcjddm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gt2ofvqtxdg.html

Ruby: warn "err"
来源：http://dali.xziqi.cn/Article/details/gt2qycjveme.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2qlstwsyf.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gt2kymscmwt.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2chdlgczy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2hleilpxw.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2drjkiied.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2ewgmanzg.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2kepltlyw.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gt2jxjjqqom.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yvedp.cn/Article/details/gt2mlpfoqle.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2ufsqwsot.html

[M08] 获取系统与运行时信息
来源：http://dali.ivvv.top/Article/details/gt2zgcfizak.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gt2rslaamtz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gt2xsnjdjtl.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2yclxorlx.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gt2ramznqqt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gt2pnwmhapz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2mszczxsk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhcugtgg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkonnunx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gpgxmtqh.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gt2qyouksgp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2lpnigpjj.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gt2qrejjmgy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2wssoyynt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2piuobjdg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2plogityx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2lhblfmbj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2jjvpexne.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gt2arcrsqsg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gt2xomvnadv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgqtesic.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gt2yepzuaht.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2jyrlunfi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2crftwitv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmdnmhkp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2jylhdzdb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jianghu66.top/Article/details/gt2ltjwtrmb.html

Go:   slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2cticelsl.html


<!-- 参考信息 -->