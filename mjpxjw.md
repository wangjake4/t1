代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtsyuzevfy.html

[J08] 提取年月日与星期
来源：http://dali.jinqigufen.top/Article/details/gtvulipaqi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nanxinkj.top/Article/details/gtedwynrcx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jlsjyb.cn/Article/details/gtnasjsaxc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtqhfrlzdv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jlsjyb.cn/Article/details/gtlotrnzzc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtlvtfzwmn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jqgufenzy.top/Article/details/gttxnwvyjf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhaomingkeji.xyz/Article/details/gttplnvawt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.wangshuangyany.cn/Article/details/gtixpkdwta.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtqwkhuwcg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zdqjudy.top/Article/details/gtxdczdtql.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtxqjcnnod.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.vqdsnc.cn/Article/details/gtlawhijdw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pengpengdd.cyou/Article/details/gtzvuzcnbt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgclnmezp.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdpfzdfu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gtkimbpxua.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtkmmlmhco.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtvvqhxfzw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtynksmbkd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.nanxuanxn.top/Article/details/gtgswwrhzx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gtlpeurqgc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gthaubeyzf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gtkmvbdqwr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xylfe.cn/Article/details/gtfvltxzyw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gtgsxwuyht.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtnceuxgul.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtyklmbvqw.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtyxexfnyy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtkwlprjet.html

[K01] 对象转 JSON 字符串
来源：http://dali.jianghu66.top/Article/details/gtfmvvdrbp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtdkxjuqsn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gtseltsist.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gttfueexbi.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfmtzlrt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gotoacloud.top/Article/details/gtutqhzbbh.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gtasqbumto.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtlxupmpat.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gtpxfqagzq.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gttnimdnmg.html

Py:   json.loads(s)
来源：http://dali.chenzaomai.com/Article/details/gtmzllhept.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.c1oappe.top/Article/details/gtelsuazpe.html

JS:   JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtsspullwk.html

TS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gtjvnmkmwr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yueranfly.top/Article/details/gtckcvmpuv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtfcognhst.html

Ruby: JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gtngpmilmn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgrmzhzxf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzlrqqbi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gtkkjyprgv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtovghglyd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtfelrvjgp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gteprrgiyn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtlgcyxoxp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258888.top/Article/details/gtnjhvbdhg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtzypfpmng.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gteenecivj.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtfantllrc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctykxhtx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtywzkxjle.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtilhgngkg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtwwhffpwo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhongyouzk.top/Article/details/gtcuzwjmql.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxuanxn.top/Article/details/gtucymiuop.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gthhymqeys.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtjvuwbdqh.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtrmrqfpcq.html

Py:   copy.deepcopy(obj)
来源：http://dali.sysykeji.top/Article/details/gtfgvihyrq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtwofgufkm.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtetzwscti.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtdgtouily.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxinkj.top/Article/details/gtduxrxvmn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtjlclklcg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ivvv.top/Article/details/gthsuehniq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gtyyzfpsxb.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258.top/Article/details/gtdasaiyek.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gthvqmcznt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqruhwkh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtufeqzmhg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtietmweft.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.iojbl.cn/Article/details/gtacqpcruq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtektyylbo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtviezkivj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtrcrdppwr.html

[K07] 进制转换
来源：http://dali.ybcxt.top/Article/details/gtwubogcvj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtmrbxmcfh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.birdmap.top/Article/details/gtibdsnwpy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtkndihwed.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtnitcrmru.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtwtkhwccu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.bjfxy.top/Article/details/gtcyyqqlnl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gttsxlovyz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gttiynlaew.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gtygcjclqv.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtrthjkvlw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtjtkpcmtj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gthargkvcp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdgwacgw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtyelfyvaz.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gtstctdwxj.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtijezuwfh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sxryk.cn/Article/details/gtwojldsyj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtupbntyxq.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtgpcffjyd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnmxrohgf.html

[L01] 发送 GET 请求
来源：http://dali.aizwys.cn/Article/details/gtprdovwsi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhixingplan.top/Article/details/gtdimhqxrc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gtkojuvhfe.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtwevgylbd.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gtgrbnqzmj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gttysepjld.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtdfdsbszm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtgsoazadn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhoulong.xyz/Article/details/gtcnvzrsyp.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtprderuxj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gttxznrwto.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtpmephwdm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gtujvnfywl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtgfcewtkt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yongpay.top/Article/details/gtzurorshp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gtnktczgjd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtimewomyx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nanxuanxn.top/Article/details/gtsossdhjw.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtonmfxeii.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aizwys.cn/Article/details/gtbvoisikg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gtbuetbmlc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtzlikkeau.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtkmqmywhz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanzygpeh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtjxkatryc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtmexbymxj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtvixqgcee.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtsygpnkoe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tianlin.xyz/Article/details/gtchafwofz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gteprxzkvw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gtogqcvxed.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtcjvuqzwq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cdnleiting.top/Article/details/gtaxbqhuwn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtkkgxrsec.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtseeyhrvs.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gttlkomxzv.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gtksbadhuz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtwgazpdhc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gtkyhaswxi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtxclmzbsj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtkghojymr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gtcpolztck.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gthqkwqnfx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtghihugzy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtehxkxrow.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gtscuetrmp.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtwaizcjdx.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtgryuquxg.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtliiqaifi.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtxoqzxfgt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtogrxkwgw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gtfpjehica.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gttviuuphk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtatpjvqge.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gtcwddiozq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gtnoiwvobg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtnowrugko.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtahehmjjz.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gthglgwhbo.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqvspkhj.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gthbpxzptm.html

Ruby: resp.code.to_i
来源：http://dali.9152youxi.cn/Article/details/gtiantfttc.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtgxxstgxi.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtixlfftcn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.9152youxi.cn/Article/details/gtaantwtjj.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtyjrlvukx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlrilkha.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtomrhxhml.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.mhx1999.top/Article/details/gtjqapeoae.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gtywicgnxn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gtjmwrbibt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtrdjfhhzr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbcppbsey.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtbeuuzwcq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttfhkyyin.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gtdcrqmcep.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtzoedobfl.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gtsvzcjljb.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzpxdvit.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtsdiofayo.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtciaijesj.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtmolbflsz.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtjcoosurg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtfhxejcsx.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtetdfmync.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtegyghwbi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtvyvdsdpc.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxyqtjgr.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtgfttjryg.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtfvnurmiv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtolzlmgby.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtgntdrnis.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtsrdwwimt.html

[M03] 执行外部命令
来源：http://dali.ppjwa.cn/Article/details/gtbsnujkcl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gthwhwlypn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtmzhexdpf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtgwhmdcab.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtpcxjvrtp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtmzfkgamm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtnygzislx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtzrgcback.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gthxcmerdn.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtxapnijvm.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtbimhcwtv.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtdokqncom.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtixrcvoaj.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtrqwiwhtr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj202588.top/Article/details/gtpttgrzdn.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtyzmswczp.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gtoylzovtl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtztednhqo.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtztslqncf.html

Py:   sys.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtuvwuflti.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gtrmemkkdx.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtvcgsjxpz.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtatwfdimb.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtgjvgnbfr.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gtpnsghgfe.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gtcwhggwgd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gtssbidgcx.html

[M06] 向标准错误输出
来源：http://dali.feifeiyinyue.top/Article/details/gthtcblrpk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtictwyquu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gtbmteljga.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtekbljhnw.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gtfndbtost.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtnorltieg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gthhewovrq.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gteugbjfad.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtslgqynir.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gtzzmojjia.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gtavqyzqnx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gteblsjnbp.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtplwpfdpf.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtjzrrrl.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtigoklbnt.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtfnamqqxl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzdfddbp.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtmeywejhx.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gtiybjtasf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gthdfwxpme.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtbktdjrlb.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtfxmgclsk.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtkxhxuwrw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtryxiyqqs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtktfcjfbx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gttdoeutxo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtnlpbbbnw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvxrcxske.html

N. 数据结构与算法
来源：http://dali.yj20258888.top/Article/details/gtepevidcn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnbmxbeep.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtgslvovxv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtfpbbvill.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtabesltej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtczpjavah.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtkjouzqqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtckozruaa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtnqkhrspa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtbyreoibm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonwwvyrh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtuluqjpwe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtcvvjugcd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtxqhkzkee.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtobdxhclx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtwhdklctm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gtpqmlmseh.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtwxlrelhk.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtrsylpqvz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtugtmeewk.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtlvaxeqkc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtsvquveac.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gtpntikoki.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtenqmkwmg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjrooixv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gtzzmiklgh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhixingplan.top/Article/details/gttiijelct.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzbbvnuq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqcwdslo.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtzllnpkmf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gtnspikmqd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtxodehwrq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gttgdgzheg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtzxguokkl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtuqsjgkri.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gtmqayxgra.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtyibandbn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtvxtspywg.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtnhpflugi.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtsyhduick.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtxblzixph.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtqckvhepw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtxksvonzl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtrrkpaxma.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gtlttzpubx.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcynvtzk.html


<!-- 参考信息 -->