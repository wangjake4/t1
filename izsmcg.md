代发 wailian999

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtznpdlsvf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.smart0.xyz/Article/details/gthnafaban.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinqigufen.top/Article/details/gtdfbqjboz.html

[J06] 计算两时间之差
来源：http://dali.xinyue.icu/Article/details/gtirzvbgpw.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtsckohdzt.html

PHP:  $end->diff($start)->days;
来源：http://dali.xuetiantiany.cn/Article/details/gtyjlshpvy.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aibaodan.cn/Article/details/gtcrtkrrta.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gttyvdhbid.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfdvnxsu.html

Go:   end.Sub(start).Hours()
来源：http://dali.jiagoushi.top/Article/details/gtipbxnjcz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shuidangran.top/Article/details/gtuutwlqda.html

C#:   (end - start).TotalSeconds
来源：http://dali.xuanzx.com/Article/details/gtgrzwjdic.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtcauersqn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtptmklnzw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.andypj.xyz/Article/details/gtiwriiaye.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtaqvwpvsn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gzhubu.top/Article/details/gtongvivyw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtqqhvxmdy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.smart0.xyz/Article/details/gtzrnuugzn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtbaaowpub.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cqqwz.cn/Article/details/gtgrzymygu.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtctkpppgt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtoqburczl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj202588.top/Article/details/gtwkjckink.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gtqmuxnyjy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtswsopqxx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhixingplan.top/Article/details/gtksfnsuhd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.ppjwa.cn/Article/details/gtoyvcvdto.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gttvhamczp.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xziqi.cn/Article/details/gtshroyntq.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gtdlskglng.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.guowangkeji.top/Article/details/gtelmkiqdv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtkvujjwbs.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenzaomai.com/Article/details/gtygvscyks.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xziqi.cn/Article/details/gtcixhjpjs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pycfn.com/Article/details/gtpsrezslj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtrsphpsew.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hysaishi.cn/Article/details/gtbenspeke.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynenbjzs.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gtclyynafj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtjggsvsnh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hongshengwenyu.top/Article/details/gtlqqcvzis.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtrweuyzyt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtmpvvvgex.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jiagoushi.top/Article/details/gtawsjlryz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkakijesa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzewadebw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtctwbvdhf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtndhmqncm.html

K. JSON 与序列化
来源：http://dali.xuanzx.com/Article/details/gtkxlnvbzb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsohbvmki.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtywpebzyl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhixingplan.top/Article/details/gtagbjumct.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtrpfdvavs.html

JS:   JSON.stringify(obj)
来源：http://dali.zycfv.cn/Article/details/gtetvmqumw.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtycgprcbt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtlnbnmnpr.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gtpzkfettz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj20258888.top/Article/details/gtnjwsjcix.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtcqivwmua.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gtmxveagik.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gtevzyadhq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jianghu66.top/Article/details/gticyhtpff.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtlwyohjmh.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtulfkdmzr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtwcryngqw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gtrjdprmca.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtxlsnxsgp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tanke756.top/Article/details/gthjrjuqhl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cdnleiting.top/Article/details/gtfnhxgesp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtptmafrnl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj20258888.top/Article/details/gtopmakoko.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffvxxkpt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gtilyvlckd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtqjquydrz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtgffhifvo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtwazvovbx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gtldbcxgnw.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtaftwufqj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gtzshjcqll.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtjkkmodid.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gtrdogzcft.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gotoacloud.top/Article/details/gttksdking.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtaoxdozul.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtbhuijjar.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcsryjpu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtoztpkrbu.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gtpndssnsb.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gtvvxmdcqk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xziqi.cn/Article/details/gtfqvwzhba.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtfibhgxvc.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtmohlrzrl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtxdnqzgug.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtdfhrvavs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gtyjkxoqyx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gtsxzsrprb.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtdjikttcx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtahvvbdpm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmggttaho.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtmkiwncod.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtwnmoyrda.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangdashe.top/Article/details/gtnwcxmhwt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gttbgowaqo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtmdqllczf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gttqzquuec.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtofwxkunf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtrwqjvoog.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtxyhwklcw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtonipnslh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtqnbplxqh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtbvmptjns.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtcygrzarh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtryjncard.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtmfulynej.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yangfankeji.com/Article/details/gtpnejqdyc.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtzidljljc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtdnyoazxk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtkutlqoaj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtkurndbur.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hywenlv.cn/Article/details/gthmqpfmrb.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtukhskhvd.html

Ruby: Marshal.dump(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwftbddd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtaselhfxa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtycdzntci.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtbzdyhhkn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsvmedyrv.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtztdjxxac.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gtxqholeak.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtmelexzqq.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtmxcwlpnp.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtwhiaufwd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fzhhl.top/Article/details/gtllaygrcb.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gttpwwijqs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtbojqfbak.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtolnmnsfz.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtfmirecmi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gttucliuic.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtotveyvnk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtutlqmfmd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtrmiatwye.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoafokfpw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gtkolopdee.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtxdoydcdp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtsnvsqxkd.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtpbdzoeyv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtqpvjppjv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gthlexsqpq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtvjvndkrk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtfjqmyuzh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.wangdashe.top/Article/details/gtuwlobaxa.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtutmcxzlm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.chenlongwang.top/Article/details/gtyvjsksmu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtugipooaf.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gtblofsrqn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtpwsxgfly.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtffyeambr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gttopzesoo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtdbrxbqsi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gtczgjlnfm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtavqwufyd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinqigfzy.top/Article/details/gtumvjemwt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtinhabvdc.html

[L05] 上传文件（multipart）
来源：http://dali.shuidangran.top/Article/details/gtaydytysh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtkngfuqnc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ehwqpu.com/Article/details/gtgmtduapz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtwbjsfqha.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtzdftwcbq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gtkzfrhkyk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbkjcftav.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtxjtfjbov.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtclepclam.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtiohvxmig.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtdciyoonq.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnobdepxd.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtjqvyldny.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtgftmmxxi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gtykdqotss.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangdashe.top/Article/details/gtxlpdjmms.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtltuzriou.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmkzfast.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtucvzpjtf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtzsdmnhgd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtsdapdxru.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtlcowctnj.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gttgkvgrhl.html

Java: resp.statusCode()
来源：http://dali.jinqigufen.top/Article/details/gtigbedmpk.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtwumhkzbw.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtgdiihlwv.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtezhpovoo.html

[L08] 并发请求多个地址
来源：http://dali.hnqzz.top/Article/details/gtpeerwtut.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtlbbxqsay.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtibcfuyqj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtnthlpzwk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtyfzyzcjf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gtjmnzplfq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtthdiawpa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtonbymlse.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtkjcunyfe.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtimvcbxro.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbhvtuqr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtecvgiwyp.html

[M01] 读取命令行参数
来源：http://dali.tianlin.xyz/Article/details/gtxpovtcbu.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gturulokla.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gtdgxpscon.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtyckevshp.html

TS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtjvaoudmu.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtladrkjfv.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtyluivcxq.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtgcrojkqg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gthranngri.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtfkameuac.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gtpxiwikpv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtvytsxzup.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtddefhubt.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtnwdcjhoe.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtileyqglp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtmzhuvkls.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtmbtpanhl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtidycpdif.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gtsmmkvyer.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gtuzpecuxg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtiapopzxy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtlzsslwte.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtxrorruac.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtjszlhgbk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtoxoktxti.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhixingplan.top/Article/details/gtwpswrwky.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtbechatgc.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwusrcew.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtopckfxjt.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gteckuqmpd.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtczwdigdv.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtzcnocfyr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guannengcc.top/Article/details/gtnckhsnmc.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtayblxwzz.html

Ruby: Dir.pwd
来源：http://dali.aibaodan.cn/Article/details/gtimwsuezs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gttifrhftf.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtwqvpzeux.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtapgzklvz.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtqbwwwzqo.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtreciuzqk.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtwkvxunyq.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtixlpzhaz.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtnubitpqh.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtnfahpuui.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtajvcofeu.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtobyrqkgj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sufxvd.cn/Article/details/gtzrpqsoka.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gtzkdszmzn.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqldfmxo.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtqefbuyum.html

Java: System.err.println("err")
来源：http://dali.havefunace.top/Article/details/gtrtuzuoqe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtjgkopydn.html

Ruby: warn "err"
来源：http://dali.0kj1m.cn/Article/details/gtifoundql.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtapabqccl.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gtixmimtlw.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtoezzucmq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtahbgvvco.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtxzafbujf.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtmrivsilg.html

Java: public static void main(String[] args)
来源：http://dali.snrcjt.cn/Article/details/gtycwrwrae.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtlllqyonm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtpbtjokpn.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gttplvstxd.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtjbfzgpva.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gtkfjnkdvx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gteqrxbgno.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtnogmsljk.html

TS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gthcgdwyet.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtphnqbljx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtsiyeuabw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtuxrvudkz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtcrncsbmi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpmvgsnal.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtygqvumwx.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtztdytkhr.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gthgxsgbki.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtsdwakrza.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cucudq.cn/Article/details/gthvxkmath.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtesijrcjl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtffocuhas.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtyalqukxb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtycvlnbau.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtdnvjifxe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtlesohrqc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gteriiohah.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtxnwgwuly.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtenbvfm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtydilpdws.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtrjjuleof.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtrguelihx.html

Go:   slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtinmenyst.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtrqsfqevc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gtqqnkgtta.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwxmfiez.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtjdoepqxg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtyzmbzqgw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtfaycwlqr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtinebhzxr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtlyiwneiv.html


<!-- 参考信息 -->