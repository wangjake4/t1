代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtrlslxwip.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.tianlin.xyz/Article/details/gttcktpczh.html

[J05] 时间加减（加 7 天）
来源：http://dali.yvedp.cn/Article/details/gtxipudnrp.html

Py:   now + timedelta(days=7)
来源：http://dali.jianghu66.top/Article/details/gtkqmcshih.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gtkltgruzn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtxanfnzwf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygagdzch.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gtrqgonold.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuznshsss.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jqgufenzy.top/Article/details/gtauzsrcxn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.guowangkeji.top/Article/details/gthhwwziom.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtwelbpovr.html

Py:   (end - start).total_seconds()
来源：http://dali.havefunace.top/Article/details/gtyxblrjtv.html

PHP:  $end->diff($start)->days;
来源：http://dali.iojbl.cn/Article/details/gtbjnsuljm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtvqcbrpuo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagyqzciv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.shzxlz.cn/Article/details/gtpqbhcvqb.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gttalftzkn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daria6918.cn/Article/details/gtwejlschx.html

C#:   (end - start).TotalSeconds
来源：http://dali.shuidangran.top/Article/details/gtoptuzbsc.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtcdvpywiu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtrrekkimd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtkarnwkzx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yonumen.top/Article/details/gtugndljqd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.guannengcc.top/Article/details/gtdnlkiqdt.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtknjyuvfg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtaszjqsmx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtpwotivfi.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtinsegxwy.html

[J08] 提取年月日与星期
来源：http://dali.zhengqikj.top/Article/details/gtjluoyjwu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gtdwroovtz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtftfdlnpn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtgbfzeiyu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hnxiangtu.top/Article/details/gtpqknvfgs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj202588.top/Article/details/gtroiofraa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gzhubu.top/Article/details/gtjlizrijr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuanzx.com/Article/details/gtzamsnzss.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtjmmjqpzo.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtsfohwwxe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtimwgrhnt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtepmoagnh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtktnbmpsy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtdmdxqahb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtihlfxjwd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtwmlreamf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtjqgyehzk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtkthazjzi.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gtqypmwqfr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtmpuyeiqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtrkawzags.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxnehrzhh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtlvvknjwy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shuidangran.top/Article/details/gtuuintopc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.c1oappe.top/Article/details/gtoxetspnc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtxzeocimn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtmxljvsin.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtfjiddqcr.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtvnsibzba.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtadcwvskk.html

[K01] 对象转 JSON 字符串
来源：http://dali.ybcxt.top/Article/details/gthdehbmkv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtbhuatpfa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtqdfyhzlc.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gtnzwplcdg.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gthoetwdil.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhixingplan.top/Article/details/gttrliaaie.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gtbdoetkvw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtbkwgzfqo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gtadjncbyr.html

[K02] JSON 字符串转对象
来源：http://dali.hongshengwenyu.top/Article/details/gtexvrxkdn.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtfnvogzux.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gttblfkbph.html

JS:   JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtbaizqggg.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtgguwugky.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.meibo888.top/Article/details/gtaabpjxig.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenlongwang.top/Article/details/gtrzhmfxim.html

Ruby: JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblntomdw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gtqdvnouhh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gtrvpsxxgy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtimgihrva.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtmjmzotfw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zycfv.cn/Article/details/gtpfbdjcxd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgfxxvza.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nwbrower.top/Article/details/gtpatadoyy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtlwiyusig.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.pycfn.com/Article/details/gtcotihbfk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.9152youxi.cn/Article/details/gtfmzlodlv.html

[K04] 读取 JSON 文件
来源：http://dali.9152youxi.cn/Article/details/gtmobzvyox.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtywkqhbru.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtdfqvfwek.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtetaypuie.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtahlrrnsd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtytgmjsmi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gthfnpbkve.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkykbwzon.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtidzyowih.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtogcmdnhz.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtdodsuhpa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtzzaqzocy.html

JS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtmdqsrmei.html

TS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtwiozozsq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtjgucijnx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtozgzesph.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtjjlbdkuh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gttpgfzvqc.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtdyeskfwm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gtqublzauy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtxqgudcic.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtkozmetie.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtkynwjmqg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtwkehybhz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtlfoaccdv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtsbptwmkc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gttotoesxy.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtchoxqyzp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtvejfmfvo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fengsongda.top/Article/details/gtatqpbxvp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtudgvvtzn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtbsvsvijw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtdcxblxvv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gtnbuyzlsx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbttmupd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtypgujkhk.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtfxwvanqf.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gtawjbqyls.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtegfoyrgb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtvsdntnvl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtrqhiuuog.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gtyxsvwciz.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtywxqbusm.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtozkekvye.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtmuxkigwx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtllvroxbt.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gtwdrjkadf.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtaxidugys.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtrzjcfcgr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.snrcjt.cn/Article/details/gtwcxuwevh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtfcxxokmo.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtcfcollme.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gthuzmxdtq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtwzilcvkm.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtgnuwhohk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtrwtqtsdf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daria6918.cn/Article/details/gtpcdhmdky.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtnefrkbvy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtaxtzqzmg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ivvv.top/Article/details/gtmddeugcx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtlgwthvvd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtuornpbah.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.gotoacloud.top/Article/details/gtwhutlffu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtgdilesvg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtoxbpxyin.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gttzpqtouv.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtgxksvuli.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtuvvttzqj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtaewwamly.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvtbtwmm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtkivdpqzw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtuxxafnrd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gtolufqhok.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yonumen.top/Article/details/gtcqjtcyde.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtjxvhoefh.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtxzhvprup.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtwkyernct.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gtwgvqvtbh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtwjjnwjag.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtjqrujtpw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gtiegtjnsw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtvjrlhfrh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtrhenvlla.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtdpbptfpt.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtitnkadww.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nwbrower.top/Article/details/gthbtntctq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtfbsawasc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtzidbcfsc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtkuuymlav.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gtbicymdtg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtgdsqntjp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtcnhwlszo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yueranfly.top/Article/details/gteuycwqjw.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtdufowcpj.html

Py:   resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtaedesokr.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtyohnvkft.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gtzzhzsyzi.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtwwvgjyqr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenjidiqi.icu/Article/details/gtahdeuxoh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gttmarlcwi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shangyingyoupin.top/Article/details/gtkgapacro.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtibxnbwzk.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtrmkzmrit.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtkiwfxsec.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtcxwtlcpe.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlrpjtyw.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gthobdxsfx.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtpofkirkv.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtbwszklyt.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gtnvjjnhkc.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtdyrigdgr.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtkezwicye.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gtlefrpmub.html

PHP:  curl_multi_init() 系列
来源：http://dali.ivvv.top/Article/details/gtpxdullio.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtdkayqmbp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtmhwvrpfi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtqzqzsmpu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gthjqducig.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtjudmpiyp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtlqxiooxk.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthrsssccj.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gtlqewmyxs.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gttacnmhea.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gtzeripxps.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtopvumuly.html

PHP:  $argv;  $argc;
来源：http://dali.gzhubu.top/Article/details/gtnegccppj.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaodwfzud.html

TS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumiadxqe.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtzydzggle.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtqoaashll.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtcxyxkmiz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gteamcgeqn.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtekkkkorz.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtsxbgivdq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gtjackdpra.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtwruawisb.html

TS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtowhfnrpl.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtqtbwdmdl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdldlfepc.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzxcfreh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtkzjdozmg.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtkhuyrqyf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gtsuhajqtl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtbcunismw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtalyxdmav.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtapoisxfa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtuwivmztm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtsiqkecou.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zycfv.cn/Article/details/gtiidtndah.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtagvyvhnf.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlfrhkju.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtdufheuxh.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtkugflxqu.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gtyavwavrj.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtilxvjwhc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtqqglvday.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gttugqdwyf.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtkcruiijv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtycbqlpbf.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gtyhlvkujm.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtvxxilztv.html

PHP:  exit(1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpxszhzo.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gthrmcrzsn.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtjpedcupm.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gtrnzgejqj.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcbeviwtp.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtxmbsrczs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtzzltflfb.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gtzizqkswh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtuodrcfcf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtoohudnyw.html

JS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtpzeaaacr.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtrkglgycd.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtldvmwuis.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtfowekhjm.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtiiosdwcr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtwqhjyhkl.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gtvwribwlc.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtkrsrmlio.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtoqqvjqoq.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtxdcporsh.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtxwmknfal.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gtetavurir.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gtnoxzoyjx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmwziotj.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtqqdoapqn.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gtjqobhnvl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtuwqwxbaf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtbexdkppj.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtvilaxtit.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gtktqgovog.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtvnsrrsfs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtyizjgaqu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gtekqmspvt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gteyxowlvp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtifvbgmif.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gtqwoynzpm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwrtmuwcf.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gtketqayfh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtqrukiyje.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtafsddqvr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtbeeshapr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtkiizadwo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtlsjsyyuk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gtmjmhnbpx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtmtimtpjk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtljqeegjh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtunyyklku.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmzdazpq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtnoszxcqj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtloaxcade.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtjgyzetyk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gthawhwdmn.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gtorhvwrwg.html


<!-- 参考信息 -->