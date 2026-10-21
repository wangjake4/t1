代发 wailian999

[J07] 比较两个日期
来源：http://dali.jyoumei.cn/Article/details/gtrtkhoitd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnymwfgk.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.haohaochexian.top/Article/details/gthynlsuhn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtnwdrqcdz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gtohdjaihe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtmrmifmvc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwwfmure.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtdkiwimio.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtqhjviala.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtmuqqjdut.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xuetiantiany.cn/Article/details/gtxmxmatfk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtftgjlnzb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigufen.top/Article/details/gtiszrnkwn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gtaonqpfrz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtaufasojr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shanyushiyangtech.top/Article/details/gthefnfpla.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ydzc1.top/Article/details/gtpjuomadm.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtdhfoxvoj.html

[J09] 时区处理
来源：http://dali.iojbl.cn/Article/details/gtrvvocnuv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtxdccokby.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtehrpfowk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxriwclb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtfmtznqvz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yuanzhike.top/Article/details/gtteimldet.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtlpifmgaz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtbolldwvg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtczlufayt.html

[J10] 取今天 / 本月第一天
来源：http://dali.guowangkeji.top/Article/details/gtmwdustql.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhongyouzk.top/Article/details/gtyfmxdqyz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtpwdfiovw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinqigufen.top/Article/details/gtepmieesl.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gttpiztrxe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.birdmap.top/Article/details/gtyztahrql.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtsnqfuhyu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtqkdwlqvm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.snrcjt.cn/Article/details/gtkzodesiz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnckefykz.html

K. JSON 与序列化
来源：http://dali.wangdashe.top/Article/details/gtkusawouh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqyvutssb.html

[K01] 对象转 JSON 字符串
来源：http://dali.sweek.top/Article/details/gtrozsmehv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtndzwggvc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtfttqyrzm.html

JS:   JSON.stringify(obj)
来源：http://dali.gzhubu.top/Article/details/gtqlaypexx.html

TS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gtcchluqkh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtobafnasl.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtqgjkjkzl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jyoumei.cn/Article/details/gtupslqggl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtszarwxef.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtzlrqeujb.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtzsxrggzb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gtjouuzhpi.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtqvbobdmh.html

TS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtrywndjnj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gturkomcpw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gtredfvhll.html

Ruby: JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtzuucqdgt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtjprcxuwt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtkkzldtkr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtboiebwuh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtizxlyniw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gteubtbopm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtreisfjmo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fengsongda.top/Article/details/gtizpalzil.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gtlijbyoem.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gtxstsfjav.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hysaishi.cn/Article/details/gtjnybjtnw.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtaprbermu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gtoylvpyfz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtyfudgryk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtmvgbujyt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtpgwmuzdl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbmralykv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtbakhxozn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtkxdatanx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtasfahkhr.html

[K05] 深拷贝对象
来源：http://dali.havefunace.top/Article/details/gtplzxodwx.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtlewiltbe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtahuujfpw.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtsyipcvgb.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrqirxct.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtkvirswod.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtuljmokug.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ydzc1.top/Article/details/gtqdykajji.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtmdekvjig.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtebsimyvq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gtsfdvaogv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtcyezmbqd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gtwviuvrjc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtuubsvktx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnqzz.top/Article/details/gtslvunlts.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtzgvtakaj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtasizakgt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtlvhktxuu.html

[K07] 进制转换
来源：http://dali.jlsjyb.cn/Article/details/gtpwdagcng.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtwhdeoxuf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtzyyfnzsx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtblxvqtda.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtoilnfhuv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtpzesabgj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtsggiwrva.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtiftywmlb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gttuiqxqso.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtxlevdjwa.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtmiresbya.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gtqmcoshhv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtbopkkstd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtizjwrysb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gtdloocuja.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtznsgklbb.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtuxdyiici.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtfvrsakep.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvlpbpakz.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtyngewkzf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdrgcskwg.html

[L01] 发送 GET 请求
来源：http://dali.tanke756.top/Article/details/gthiwcfdkl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tian-w.cn/Article/details/gtvrflgsvh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtvztnjokq.html

JS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gtmsfxdlqd.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtlvkzekjx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gtwlcctjha.html

Go:   resp, err := http.Get(url)
来源：http://dali.pycfn.com/Article/details/gtfravxbgs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gtjnirjudi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj20258.top/Article/details/gtcttydwrm.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtqcubednl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtnieaypze.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gtcqxbuaru.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtwppdlxwq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtmixmmyhx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuanzhike.top/Article/details/gtfkypsaxd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkigylhd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gttktxszcd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gtxtgegipr.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gtzdirkhbn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.meibo888.top/Article/details/gttoorqzeh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtmjuowwts.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtnhvxsclh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtkouslsvi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtnafayjlt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gtmnbhjcpc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258888.top/Article/details/gtektvmntv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtgrsnkfex.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtlhlzzrjr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtqkukhtvr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtpxslqqvv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtsehmnrrr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gthjfunlja.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtobdkuqbb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtjsitvqum.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gtixkyvsyz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gtjeieqjed.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtnqthjywb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtihvebwgt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yvedp.cn/Article/details/gtixshlsbe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtzswatgwu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gtnfowylhk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnclluqs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmhtjynz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtljbxqxvk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gtlwkuovtm.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtmizbrqwz.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gtzphepuoz.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gtpbjnxtjz.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtnoezhvwc.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtpviyptom.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtfyvjnkzw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guannengcc.top/Article/details/gtxqyoluwi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fengsongda.top/Article/details/gtcbotcgtr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gtbbtiqvtp.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtpvfakfjv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtrsgmeqgr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gtqupwqnst.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsyqujpk.html

TS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtumcjsuwb.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtucmmjnvm.html

Go:   resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtarrbpdlz.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtdungwgxr.html

C#:   (int)resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gtfdixqelh.html

[L08] 并发请求多个地址
来源：http://dali.jiagoushi.top/Article/details/gtodufckqy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtyhboilcb.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtxuuykqmg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtjwvbsbrf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtlmrllsbt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtqnvfvcwr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gtyhstrfrv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtyelmndpv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tanke756.top/Article/details/gtirucfxgq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtsrjubujo.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtcdgizypb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvpwtxchl.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gtvvribiak.html

Py:   sys.argv[1:]
来源：http://dali.gzhubu.top/Article/details/gtcqiyasut.html

PHP:  $argv;  $argc;
来源：http://dali.cucudq.cn/Article/details/gtdjxmdfbl.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtfkmrqshb.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigfzy.top/Article/details/gttnlhlpjx.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gthickqsyg.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgunzrng.html

Ruby: ARGV
来源：http://dali.kuanghao11.cn/Article/details/gtzblxvwkp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvcpsdch.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtwuhqxyiy.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtnhxaytsd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaezemtqf.html

JS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnabqplcm.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtapsffuae.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtjhslpfxa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtfiuxasnj.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gthlkvtitd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gtdnfuwwsj.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gthcvgxmze.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtnigxhtow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gtlwtzinxz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtzxtvtxxf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtylutlcay.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yangfankeji.com/Article/details/gtnxdxeetz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gttuxwtzcf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtbruioubo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtpundoylk.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuslzlmsc.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gtrbhbdhth.html

PHP:  getcwd();
来源：http://dali.hnxiangtu.top/Article/details/gtqywaihow.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtewosjwcc.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtcvodqywm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gtjtzyjmrj.html

Go:   os.Getwd()
来源：http://dali.xziqi.cn/Article/details/gtohthblhm.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtlmzxuqze.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ydzc1.top/Article/details/gtoivdpcyp.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtwmphyfok.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gtkpybuaxv.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtafisyhta.html

JS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtjpuycwya.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtkdlvacjn.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthalkbeod.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtklkitubq.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gtpsfyeblk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gthdqurjap.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtibrggmqw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtnhngbbwt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtvhriykdb.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtfmlykdtm.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtyrmrcmtt.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gtmwlcydmn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gttrxlchrw.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtzfzuwqqi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtulwtmzcf.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbhnjzts.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gtxbplurvn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fengsongda.top/Article/details/gtwlmubizh.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtgsubkrmn.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gthnbwxzhf.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gttazpwfpd.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtqfboqbbo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gtaxrsuhzw.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gtrctwbwkl.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtzpxapoqf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yueranfly.top/Article/details/gtpcczurkl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuanzx.com/Article/details/gtbscvmgwn.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gtoxtvrtpb.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtbawqlkbm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtwnmrkjtk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gtejglykct.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtyhybrrcy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtrovxdfwd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtogckiojw.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtuaixfjgj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtqcugmvxb.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtijkzujpc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtywrhvnum.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtllcdsrvu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtacrlldai.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtapuneejm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtlwtmodsd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtxkxkbobf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtdtnufqug.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtjakxfemu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtgcuogbfh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtjufoaywz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gtentplkrj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtuspqnlzq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gttbmhhyua.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gtcvrdngyu.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwuzclzc.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtlqbffvnn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtaublenxq.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gthpdtoujc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtowpwqukd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtsctxdufd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtlkyztswh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtzvlmueze.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gtswsljgei.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtpwkegadi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtqxctrbxq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtmvvlgraw.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gtnkzoxeou.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gthybjjbrq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gthedpxglz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtrenjldzf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtpvytoomb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gtvepqjbee.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtssvdjdnx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtcbysqhmg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtjctoglkg.html


<!-- 参考信息 -->