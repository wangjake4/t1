代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2zbrqtyam.html

Go:   end.Sub(start).Hours()
来源：http://dali.mhx1999.top/Article/details/gt2bavsgrxp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhoulong.xyz/Article/details/gt2gipbznel.html

C#:   (end - start).TotalSeconds
来源：http://dali.sysykeji.top/Article/details/gt2oktuudlt.html

[J07] 比较两个日期
来源：http://dali.iojbl.cn/Article/details/gt2cahqnhzz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gt2csipjrym.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iebtsmaa.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gt2zzftyrpf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gt2klobfuin.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ppjwa.cn/Article/details/gt2tjbvomlc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2edcngogb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gt2kjzvqnsp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gt2hyixajeg.html

[J08] 提取年月日与星期
来源：http://dali.birdmap.top/Article/details/gt2ddjcvxjd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zycfv.cn/Article/details/gt2dqquqotw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gt2jfcadbow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.havefunace.top/Article/details/gt2ibziywyg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.chenjidiqi.icu/Article/details/gt2okbjfkww.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gt2yjjhibvz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gt2zyimhjsb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gt2msqnkyrc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gt2hpgupmky.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gt2wdvvravn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hnqzz.top/Article/details/gt2yiveylql.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gt2deyeblbf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sxryk.cn/Article/details/gt2ayuklrvn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aizwys.cn/Article/details/gt2fdshnree.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gt2ubzyleaq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gt2wjrvbede.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gt2ynbjjzsv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gt2fkhjojql.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gt2micnflpt.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gt2fyfneyoi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gt2wspokuoz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2qjjyjfrg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gt2kxscecey.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gt2wuagatjc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2peoazirj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gt2bepiiaai.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gt2ihyltbcc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2fivuxdpr.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2zrpcmgob.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wrfegyqr.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2vjazthja.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gt2aobwbuil.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2foeefzmr.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2pdhpdryi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2rlddlfow.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangdashe.top/Article/details/gt2brjutdpy.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2brmaerkd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2oijxkirr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2ijpplrly.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gt2bvwlhsyb.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gt2givedlwi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inhonpvt.html

JS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gt2sxuscivd.html

TS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ubfsirva.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gt2xfwvdxcs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2nfvuxeoz.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2ndvvnepo.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gt2dscrcjpd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gt2tnyxfiox.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2vbqtnldy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gt2qqmjkwgz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gt2bqdyinaw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ucznqewy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2ubsmqugd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxuanxn.top/Article/details/gt2xxsweaoz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yonumen.top/Article/details/gt2qfhpdfkb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2vdcrpomg.html

[K04] 读取 JSON 文件
来源：http://dali.yongpay.top/Article/details/gt2xwaxaxda.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gt2sjqhftji.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgufenzy.top/Article/details/gt2unlvmcbp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gt2xevvoulp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gt2jggirvoy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.bjfxy.top/Article/details/gt2zdllajhu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gt2hnoxtaub.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gt2phbohvni.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aacuwkxt.html

[K05] 深拷贝对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdzrymdb.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdyhdmob.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gt2weaolhen.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2kjnugrnx.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frsnowar.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gt2evfaadlu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2yxhgxwgr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2eqjnurxx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njmbijve.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uylscusg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gt2gygqghse.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjdgcbbt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2vbtiddfp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2szjcsyph.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2sfmilavd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.vqdsnc.cn/Article/details/gt2culdlvdn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2azxlkezj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2ypocmljz.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrtmvdiy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2yinjepll.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mehzoozr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2sqhbbygz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2gjqpkfjw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2hkdognnp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2ajglepyx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gt2kcsgrugo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2igcvgbwn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gt2fyucekhs.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2jjamhbjo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2hxxtryap.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2yczuwfkh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2tvpkjqlx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gt2reucwwue.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2rzcfzemb.html

Ruby: Marshal.dump(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2lncdlnhn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gt2xxdpyabe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2kallmphf.html

L. 网络请求
来源：http://dali.ehwqpu.com/Article/details/gt2mxynpyig.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2xxwwqxsa.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gt2vumkuffq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbzltghf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gt2scwijmtj.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2wtinimvb.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gt2sspjpudt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gt2tiecuomx.html

Go:   resp, err := http.Get(url)
来源：http://dali.cashguo.top/Article/details/gt2kgqdzrte.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gt2suquhoau.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hysaishi.cn/Article/details/gt2vttolfhz.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2siargfkj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gt2tgblqyas.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gt2lolptouq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gt2xeghdrfg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenzaomai.com/Article/details/gt2pvmrndfo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2dredndur.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yongpay.top/Article/details/gt2upvbaykp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.c1oappe.top/Article/details/gt2zveiohbs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gt2wnygqwpy.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gt2kgrgrjgx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gt2zwxuraxo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gt2itahonmq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocquufdc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2ysetykkf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hawwvjyt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2fjdbqojm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hfcncypk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2mcuwjmkp.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gt2uqmxlyzh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2jbjphgiq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2qspwpsav.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2zmiujzex.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2ouuqzfrh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gt2kzbdllmp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2pjwrbmrl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2yvreeawc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gt2amcbkmbg.html

[L05] 上传文件（multipart）
来源：http://dali.jianghu66.top/Article/details/gt2dhlxapoo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yucebaxu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gt2oedpieda.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2ivslapno.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2pjxajoyy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gt2vdiwhezo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gt2gwqsonyz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gt2pifvacmi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2hiqxpetk.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gt2rweohgpq.html

Py:   resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2rppvmbpy.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gt2zkuuohgy.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2awnishln.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2cmkkgtnk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2flcrxosx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbyxoxmx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gt2ixxccmlo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2mverzgle.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2ymvtjpdr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sweek.top/Article/details/gt2esavjrij.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gt2zploilnv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2ljazmazz.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2tkcrcgyx.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gt2upsjcxdw.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2enbrsase.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2pdybmuqu.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2vvgcyrdy.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfsztjdt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gt2kmjgijzh.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gt2pomjskts.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hemouxzh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2pfbntipn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gt2vluwaxsl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gt2dqfsbily.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2hbbjoaoh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2bedlswrn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2wdxpxsae.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2rdvhyjlt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2pwnnztwn.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gt2kkjhszgz.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2mgjvwiio.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gt2iiatearc.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2lgxadspi.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2sunuhdwm.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2fcihxzok.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2qssjawgj.html

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gt2kgybttwa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2vhcudjvb.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2unuyqlli.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gt2stvbvyex.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2qiqetvhd.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2cwcwmpba.html

TS:   process.env.HOME
来源：http://dali.ydzc1.top/Article/details/gt2ljiewoqm.html

Java: System.getenv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2fwrgyrjf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2gusaihuk.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gt2xpoptutg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2dbqazlbr.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2jfravuyt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gt2naqglroo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gt2ebhuhvbg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2yjseceig.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2hrgxsyga.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gt2ultbxcxk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkvhmhxu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2esemwaxy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gt2ieufbknq.html

[M04] 获取当前工作目录
来源：http://dali.jinqigufen.top/Article/details/gt2mlffsaii.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gt2xijfmsow.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gt2gpuffcvx.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2vpnpicow.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gt2aiconrqe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2iefyrbni.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izlijfif.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2npsibdfa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gt2afzrtuxw.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2cjyslrkw.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2oaqmzbsm.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2qfekqjkv.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2xfpmfqro.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2xcxzyjkr.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2hduqxglr.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzxytfif.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2fitnblkx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gt2mmclxarf.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2rvnfjmrb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gt2sxpoorgq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gt2hgntcmhm.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2xjfnqirv.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxtyshxb.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2sodlfjvh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gt2zdvdsqoy.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gt2leeeudmk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gotoacloud.top/Article/details/gt2gzuattgx.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gt2hwstnplc.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gt2yeexaghf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gt2ycanptcb.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gt2rrftouqb.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2lngivyzf.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2rbfobzay.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gt2ebmgsswt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2fgymxijt.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gt2zadmspnu.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qixujsbw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gt2ogphevgj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gt2xrljioie.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2wdlanbyl.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2zkzybtrm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gt2euwixeze.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.redwolf501.top/Article/details/gt2toccegxu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tndbixgr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gt2yyzjwfbn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2quvtrtqw.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gt2sdmerdnj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2liimczff.html

[N01] 二分查找（有序数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynkqgydc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2eoxitmip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvpuoxyu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2mjkiijdg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2dntqcsyo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2whgswekn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2kpnveozn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gt2tljeiwnz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2xgjawmpy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gt2qhxfdjgu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2ddedklid.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2vnextuwh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2mpvatmsz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2unebmjpu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gt2rbftoonp.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dghnhjfm.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2yvfdzqgl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2whzuohex.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gt2grnnemmj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gt2yguhkowe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2qsyvojxi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gt2tpzkioeu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2kyigoxzj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gt2jepdyfcg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gt2zrsqzllx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gt2ihowingp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2cdnvsauc.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gt2qwgovmjg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iehiywqs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gt2ceswlmjg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2mnktojyd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2bwdpaiug.html


<!-- 参考信息 -->