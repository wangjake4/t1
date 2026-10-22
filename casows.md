代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtttgpgoln.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhixingplan.top/Article/details/gtrbqsqfya.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jqgfzy.top/Article/details/gtvxugvkfk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtdaqcschx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwzpdtzw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtlyjpxorm.html

[J09] 时区处理
来源：http://dali.shuidangran.top/Article/details/gttznrfixe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxinkj.top/Article/details/gtwrjhkklp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gthkrnspnb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnynbnya.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gthesekvjo.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gttinenbkd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigufen.top/Article/details/gttjeggets.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hfpthk.cn/Article/details/gthbdvmlzl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.havefunace.top/Article/details/gtdkhequfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuetiantiany.cn/Article/details/gtenirdpxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtnvnforhm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtpyxtklah.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.haohaochexian.top/Article/details/gtizhzdgrn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtgvupjubo.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.snrcjt.cn/Article/details/gtfbpvxmvx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hnqzz.top/Article/details/gtgkphkdom.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtxivyktvo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtxczxqhjt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtviuuizzp.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gtqkbjespz.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtypvovput.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtuynjjjjs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtswiuikay.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtuzvtjttz.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtlleuanbu.html

TS:   JSON.stringify(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtgakbksvq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtxismplov.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtqndshhhd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgfzy.top/Article/details/gtjwulpypm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtraeyzgmh.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gtmabhgfjz.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gteeqsotix.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsiocbbv.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtlpvvhxcu.html

TS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtrtyiiqtg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtonhlswdm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gtdburpytj.html

Ruby: JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtdniozjaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvecdcaoq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.aibaodan.cn/Article/details/gtafvbcbtr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gtzeatgphq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtyxbxktcx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtnniwsmmo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtamcvipwk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtukgedzqy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuupsktf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gtljdtxhzp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gtjbagwnki.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtmdqfpwsl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gtbsjbpolt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenlongwang.top/Article/details/gtgfdgwtth.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gtjqyheuoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gthqtmjazj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtmllcazzb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gtnxtzjkex.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtxcgofgoe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.smart0.xyz/Article/details/gtyvfttscw.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gthwknnolc.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtaufeqrgm.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gtzuutapav.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gteyxhujtl.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtuhhpzjgp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pycfn.com/Article/details/gtokmsxpcs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtlfklxnnh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gtyctfupom.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gtcdrxbrlf.html

[K06] 解析 URL 查询串
来源：http://dali.zhoulong.xyz/Article/details/gtyiiymfqc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtxetghidn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtwglcnerh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlicjasp.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gtlfqkbtwr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gthmubczox.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcazxixoc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtkelyufmu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtnldjyisj.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtemnnvnws.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtglxdegbl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtyqbybaxo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtzugbpjcn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtjonbikxy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluhmedmg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gtxhdsmkxc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gttrmbvohs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtqbeeqbrt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtlzpyumla.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtqhdcioax.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuanzhike.top/Article/details/gtgxbbchiq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gtdylvtdoz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtewelwblc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtteecpmlu.html

Go:   encoding/gob
来源：http://dali.xziqi.cn/Article/details/gtikpduzbr.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtafsdufxx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtdfhknmyv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gttpaipfum.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gthwfbypvu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlqhhuafj.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gteqvbuuxq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtvstzdjrz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gthuwahstj.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtrqpjghhl.html

TS:   await fetch(url)
来源：http://dali.kuanghao11.cn/Article/details/gtyhmdufyl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gtgwkqcsto.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtxpflqnhs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtfasefkft.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtukcrthao.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtumxddqoc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtgnccoyag.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gtcriwnglm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtvpqauoyz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtmgrkoeku.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gthftgxhbr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gtehdlkdcr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gthrjgkbcu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtqiaexppc.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtkfyhxpbw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gthvjbluje.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtuajyofly.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gttlyblaki.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtnjjjkwco.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwevwwmo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtorbomasd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtebotjess.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtljluxeay.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtsksrtgnv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtmhkwyxns.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gteeujpram.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gtowxsuwhj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtyxbicmxk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtlxxpufho.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtpqlctxcf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtiifoakls.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tanke756.top/Article/details/gtijxplycv.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtimvlwcoy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnxiangtu.top/Article/details/gtbobmdhhm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtunwkrhev.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtnzvrepkf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtfhbvhkxy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtupmvvcom.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtmoxgakar.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtelekbgmn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gtwegszrhb.html

[L06] 解析响应为 JSON
来源：http://dali.fzhhl.top/Article/details/gtiefaeiev.html

Py:   resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrxejtiv.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gtlrikmhav.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtmedpibzf.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtqlxcusow.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtuowzuard.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtcmjrwqoa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtfgbkrwqq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gttsxmytck.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gtsltzkvsw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhiwuduotai.top/Article/details/gtjpssnjeq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gtusdifjcb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtoycogjei.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gthighdqkb.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtjciztzah.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmnrvmrt.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmdeodtg.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtwxuuercs.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkvrxltl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gtfnevdgvn.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gtqaaedsxo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtpyfktqgm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gttkjispkx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gtmkrlkmcz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtxxyqsxio.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtgwoxukwi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gttpkqxklw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrxptdwex.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gtiwbequdw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtapchpxgd.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtkphoblsi.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gttvyehmmp.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtlrvayfpj.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtztgggxdl.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtvblietpe.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtakdsmulr.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gtitdkbndy.html

Ruby: ARGV
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhhdwrfj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtwljwzhee.html

[M02] 读取环境变量
来源：http://dali.yueranfly.top/Article/details/gtgcvkfduy.html

Py:   os.environ.get("HOME")
来源：http://dali.mhx1999.top/Article/details/gtwupjgeaa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtywsdnkzb.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtjexvensb.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtcvawhgay.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtfojjkxsh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gtbxeusmez.html

Ruby: ENV["HOME"]
来源：http://dali.wangdashe.top/Article/details/gtkpskkpas.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pycfn.com/Article/details/gtlabemxsc.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtcxvwpukr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gtnzqetuow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlfspsjb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gttrbgygbc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtzugioeem.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtjqdhoemi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangtech.top/Article/details/gtehjpfbye.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gttkxuzfdf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpibwvbxt.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gtgchxoszq.html

Py:   os.getcwd()
来源：http://dali.zhoulong.xyz/Article/details/gtzpotfxcq.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gtkxriaeer.html

JS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtumduewww.html

TS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtfttryiwr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtsztbkkja.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gtynsqzjpk.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesrvdcwz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtxniirnka.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtsrfhwoya.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtmocczaag.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtwmdnmovl.html

JS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtjztqjmpk.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtjebbueys.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtmgzinqvr.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gturjmzwkz.html

Ruby: exit 1
来源：http://dali.daria6918.cn/Article/details/gtdcakfqke.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtdltiqive.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtoejmpsfl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtazzrnvrk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtesrrkydf.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtxptsszfa.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtilffvdfh.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gtgdohumak.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtujamdkux.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtcifjiato.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtxviuejfx.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtwyvrpmxs.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtqujnwilg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtkussdzkw.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtpevodnbv.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtohvarxid.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtipaoqpte.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtgbqlszzq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pycfn.com/Article/details/gttstxugkv.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gtacibnays.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjkddsah.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtktrvvwtt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtzansqqxf.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtayxzzucv.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtpabpjcjt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gtqsxeulqp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtqfezjbcp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtcqzfbhqd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtemkzmpzu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjwfwcuay.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gttfnsnfbd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjommtqos.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtdyzrlvuf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtwvjftcnp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtekzvpcxj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtomwoqrvp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtsagtzfrk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtpwybkqaf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtthropbel.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtcceznbmy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtlwljcdzf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gteufwhruh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gtpfuwntit.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtssshjmhc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqxonwrc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtwtxrmhkg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtfqsmpzec.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtuqurhpxt.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtkzctwqgu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtcqxfzjoa.html

[N03] 快速排序（分治示例）
来源：http://dali.yuanzhike.top/Article/details/gtcrzeyzfk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gtaxudixgo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtdqznfxxo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtisifrgnu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtalmejmkf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtesfpramu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtckpbfzji.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtosqaomji.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gtckkcgtma.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtdqaafkfu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtchuwikqh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrunuwah.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtunuiouwl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtkxkvzuwv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gtqkmevtxp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtcfannoiv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtsrqyorxo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtzzspmdof.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtzarbidjj.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtflwtxplv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.fzhhl.top/Article/details/gtpctbocwi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gthxkmasgm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtkcusjrjf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtjzejlxvw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtaqumjivv.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gtlybbeyjo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtvuxuokim.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtuaycavnw.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtazememob.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtgoowffmf.html


<!-- 参考信息 -->