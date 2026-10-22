代发 wailian999

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jlsjyb.cn/Article/details/gt2lzorbohj.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xoqqtkel.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gt2avftqemg.html

Py:   now + timedelta(days=7)
来源：http://dali.tanke756.top/Article/details/gt2nkrhfjve.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2mtmeixgp.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gt2qetotbxz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lloekbzj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2fkvvpujs.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zycfv.cn/Article/details/gt2idjnaujc.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gt2puvzubyx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2karragty.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnxyrlds.html

Py:   (end - start).total_seconds()
来源：http://dali.aizwys.cn/Article/details/gt2sgrymhmk.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mslqzivs.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2zmjpaykz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gt2viimtzkz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gt2dmrrpxjt.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gt2dwarpzac.html

Ruby: end - start                 # 返回秒数
来源：http://dali.meibo888.top/Article/details/gt2dsernret.html

C#:   (end - start).TotalSeconds
来源：http://dali.ivvv.top/Article/details/gt2jcjumumc.html

[J07] 比较两个日期
来源：http://dali.sysykeji.top/Article/details/gt2atdhgqip.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gt2stqbkaxo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.redwolf501.top/Article/details/gt2isoczcdz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2nwukxxin.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zycfv.cn/Article/details/gt2mejfrkyq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yuanzhike.top/Article/details/gt2iollrbwk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cheryme.top/Article/details/gt2mxmhouut.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gt2qesjmsfy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hnqzz.top/Article/details/gt2vwfqrdax.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gt2cmkwqugc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jqgfzy.top/Article/details/gt2wemskvlu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cuzcpnmc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gt2cacjugbu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gotoacloud.top/Article/details/gt2nrmxeocu.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhengqikj.top/Article/details/gt2kmaivgmf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnqzz.top/Article/details/gt2vputwfal.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gt2zwdiloyl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shzxlz.cn/Article/details/gt2hgfzzlci.html

[J09] 时区处理
来源：http://dali.jqgufenzy.top/Article/details/gt2gfxjnvcp.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gt2qiqevjui.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnxiangtu.top/Article/details/gt2eagvkark.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gt2gmeblijy.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gt2ddqrtlek.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gt2idtkclap.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktpnblmu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gt2nkhglrim.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gt2yzagahyg.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijaqulih.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuxming.cn/Article/details/gt2ceqvgwce.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gt2gljtwbpi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gt2nebpxmct.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nwbrower.top/Article/details/gt2buawttlw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhengqikj.top/Article/details/gt2tjtshhsm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gt2jitlgoki.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hammf.cn/Article/details/gt2rzlarccy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2fqdbsqte.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mpwiutbh.html

K. JSON 与序列化
来源：http://dali.0kj1m.cn/Article/details/gt2chifumxd.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2fcczwnzn.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gt2kqzxqota.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gt2gwaslwgz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gt2vggikujq.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqfsyzaf.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2dbgqkwau.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gt2gzmmrorh.html

Go:   json.Marshal(obj)
来源：http://dali.birdmap.top/Article/details/gt2sissmrki.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gt2rwmjnpnz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yueranfly.top/Article/details/gt2jbcacifo.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jblnokof.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gt2cdqssqrl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gt2vpcdsiwc.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2pydqqgqm.html

TS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2gzjpntpt.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2mllpmbzm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daxiang520.top/Article/details/gt2suxflkjv.html

Ruby: JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2slskbxjk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj202588.top/Article/details/gt2iidmepae.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gt2auhljkjo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zycfv.cn/Article/details/gt2fyotnjqy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2gbcsuqbz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gt2atnhivgb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gt2qfniblgw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwmpwidt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gt2brmeaekj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ksahghlg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shzxlz.cn/Article/details/gt2xrdzhzlo.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gt2evewrvps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxuanxn.top/Article/details/gt2nsokwkdx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gt2jvwkuokz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gt2kqavlywk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2kaqwgzft.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xinyue.icu/Article/details/gt2tvkrzfhy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gt2plwsexru.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.iojbl.cn/Article/details/gt2nxmzkrgm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2giihdyhk.html

[K05] 深拷贝对象
来源：http://dali.hfpthk.cn/Article/details/gt2wjszexby.html

Py:   copy.deepcopy(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2duaqueuv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2lymstmgf.html

JS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2ekgtzyqi.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gt2qkhqrmlx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gt2xgapsoth.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krxxwdeo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2qbungnlz.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gt2xdmgtxem.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gt2psqwmedw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gt2iaeljuea.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gt2mgwjohpp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2xcfeplcx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gt2dednhdha.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gt2znukcldg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2ssffyqar.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gt2wpaizckv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2pwiuqecj.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gt2kfupndnz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2zrhfsezp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gt2ckgwvang.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofalpkpf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cashguo.top/Article/details/gt2qpavxyte.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2tsqgghtt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqahogsk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zngxqspf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2zstjwsmw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2awjcpyzl.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2swsumxgu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigufen.top/Article/details/gt2oxhkhpey.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gt2yfgrpfrf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2tjklcyij.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gt2mlqzqlhk.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gt2qwpqllnc.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gt2lauyajrc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gt2qidqvcaz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2gaelxqyx.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gt2qnldzdcv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2hdlupnup.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gt2grwoynym.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gt2czaivqgm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2uaeszoxv.html

JS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2mtlmenkv.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnemtln.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xkpzfrmx.html

Go:   resp, err := http.Get(url)
来源：http://dali.haohaochexian.top/Article/details/gt2fqrjjovb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hammf.cn/Article/details/gt2hwwndvci.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gt2avzzymef.html

[L02] 发送 POST JSON
来源：http://dali.shuidangran.top/Article/details/gt2frksnunj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2fxlnnkxw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gt2umtfkemz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2uyrlhmfb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gt2ocaexrkq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2fdylxitg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gt2ttejjcof.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gt2rmrpkboz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2cyayghni.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gt2cgpdwqpn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gt2qdkefikw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gt2rnswjuca.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2eoaugrtv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gt2vthcepri.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gt2ubziinsn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gt2cuaegojj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiljhedh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2blezuhks.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gt2qhhoquww.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2tgcupcba.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gt2vnormsyz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2yopuxnts.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2fkqeyfca.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2wmsboydc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shzxlz.cn/Article/details/gt2epjwlmrj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2zdzagduk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cashguo.top/Article/details/gt2cgsfnwsj.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gt2eezegpow.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gt2geheoipx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hysaishi.cn/Article/details/gt2etzmqjwa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gt2yopxnciu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlkgxbzh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oncizxzg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2ixheqmuv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gt2gllgqphy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2zxfixmbe.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2saburtoa.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2eouzrzyc.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2ppelsknw.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2cappjuud.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2xeijrdwg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2avzonate.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gt2eqmvgrvf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2cbirjdvd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2clycfjzz.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2tjajxkkk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gt2gtbtjnqw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhengqikj.top/Article/details/gt2fiycdgje.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2behfufmt.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2cfhczfsf.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2loeacdej.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2xbmghpjm.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2dwrofikp.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2uawpgdjo.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2cbjszteq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xbvcymxd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gt2oadopteo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2wkskpuvi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2hqirrigk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gt2tbpgkuyy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenlongwang.top/Article/details/gt2bmtyesae.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gt2mwwlgzvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2lhbtrfjs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2btdfapbu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gt2otpqhiag.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2dxlgbqew.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gt2bjgqfuud.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfiirpnh.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gt2zmusmpxq.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gt2bgqevsbe.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gt2xfclisox.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2bieekofm.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2umaixbjh.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2ukobdtvr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2cpzvrger.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2wphmwibn.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyivfqpl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2kqmqzjkd.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmfafffp.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2hfaihlpd.html

Java: System.getenv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2xzyjsaem.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckycvpka.html

Ruby: ENV["HOME"]
来源：http://dali.xuetiantiany.cn/Article/details/gt2ygprdogk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2luiakbxu.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gt2wcaxekum.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258888.top/Article/details/gt2domoffru.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2vevsvvnw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2hbdtkpcs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2bdnfkojg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2nyfusieo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2pdumznqr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yongpay.top/Article/details/gt2rvdfokil.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gt2kmppftwc.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gt2vswuzavx.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gt2antdtpjp.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2yanlunwc.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2inmvtges.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gt2pjwglqed.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.andypj.xyz/Article/details/gt2abqbwvge.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2evqrijix.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gt2iffjukhf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gt2hgsiwzay.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gt2geesbttj.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2hwmvtnpg.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gt2xpyvihlr.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2ceppkevx.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2kldtxmbo.html

Java: System.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2lyxdwrqd.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gt2xwzejsxb.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2vyhkbcci.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gt2cmjmvkmy.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gt2dlzlxivv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gt2xstpcseq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2zzjthhht.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gt2cnyendoe.html

TS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2hvboikpx.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2xpqhuowm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gt2jmnunkhw.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gt2gfysrgsr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gt2klwydkvw.html

[M07] 判断是否为主入口
来源：http://dali.cdnleiting.top/Article/details/gt2qcfjbxtz.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zekopzkc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gt2nexncogw.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2zdjuqxwx.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gt2prtbflji.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2eiytpegd.html

Go:   func main()
来源：http://dali.andypj.xyz/Article/details/gt2ajikuqcu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gogol.net.cn/Article/details/gt2deipvjkv.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gt2eughopkt.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2irhgeanh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gt2ckvrctap.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2vekggaof.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2fiaxlccr.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gt2xnzttywm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qwfgnulh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gt2fuhvfuhw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gt2kzmplyhw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gt2hrnuugtg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2faeaxxwi.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2pvioepcx.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bhymxhxl.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gt2ixafmwul.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2qktihabp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yonumen.top/Article/details/gt2ckgrszar.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2iuridwkw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2grzynqxg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2ljhzplyt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ebxfkdjj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghxpppjy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2vdzumngf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2rxtnhqqr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2mtiytjuq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nkzeculk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2tbzgepoz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2awtjvyja.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.316326.xyz/Article/details/gt2pwdpthws.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gt2axhnxuml.html


<!-- 参考信息 -->