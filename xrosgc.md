代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtfbjpadss.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gtssgdexfi.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtxxzneqki.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtcgwkidnr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhijiandao.cn/Article/details/gtmzhejbdu.html

[J08] 提取年月日与星期
来源：http://dali.chenjidiqi.icu/Article/details/gtrrclvydi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtcuexvxct.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gtqcqzgoxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtapgshjpd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtuauyipwp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.vqdsnc.cn/Article/details/gtxmrbqawn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gtwdbalupd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtxmogifuq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.vqdsnc.cn/Article/details/gtclcrwair.html

[J09] 时区处理
来源：http://dali.daxiang520.top/Article/details/gtvhuawzuz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cdnleiting.top/Article/details/gtihmryepx.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yj202588.top/Article/details/gttnzdsmyp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtlkzqfzou.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtzuhvxbte.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.kuanghao11.cn/Article/details/gtlaflqysk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazsvesnl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiupepten.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.mhx1999.top/Article/details/gtjgabofhz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtsgopiwxl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gtsixcwxyx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgufenzy.top/Article/details/gtgnzronqx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofkklvnb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cashguo.top/Article/details/gtnjxnrqtd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtsvzzegxx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gttklqjjjs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.fengsongda.top/Article/details/gtsihedqbd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtthdxnyps.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtonakzvba.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtwkkfikar.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtktykydfo.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtttshmadp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtqbkswswm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtcnladg.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtegomyrdy.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtolmbtliv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtxrwloqor.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gtxttxrtyk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tianlin.xyz/Article/details/gteeafsbyf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtzvyachnq.html

[K02] JSON 字符串转对象
来源：http://dali.zycfv.cn/Article/details/gtlzxwonqd.html

Py:   json.loads(s)
来源：http://dali.yj20258.top/Article/details/gtwtjbnwqw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtvmcyckzb.html

JS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtygszwyxm.html

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtjexcsfui.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtdzcdywao.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtcerwiljh.html

Ruby: JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtzskzsnli.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gtzuwbotkn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtrpdwuuct.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gtuwwieqeu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtmkdbqaup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gthhdfpxqt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtmemszrqy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gtusizzrtt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtddvjswqu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtnnvkumrm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jqgfzy.top/Article/details/gtwwsbzsca.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gtliqmiayq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gtxqhagzka.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtziabbaxy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtelmfdlbh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtkrtocatb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdooganfi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtjuunaksw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtkekejicn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtnlsfemkp.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gtgxavodog.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtpywmbbbj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtvxaakeol.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtfprhlvwp.html

TS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gtlumenxyy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ivvv.top/Article/details/gtflygnkgx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxniande.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtrifyjpfy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtaqjpdail.html

[K06] 解析 URL 查询串
来源：http://dali.sweek.top/Article/details/gtyqrfpycf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jlsjyb.cn/Article/details/gtjcupvems.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gtknqboztb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtantknser.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gtzkmxylcr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtuqsrqxpo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtwvbsvshb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtkxahzseq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gthfckxcyg.html

[K07] 进制转换
来源：http://dali.cucudq.cn/Article/details/gtumeovzny.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtqeowzrhn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtnqmfgmzc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtmipmefdv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtoxelyqlp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtmvamnfer.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cucudq.cn/Article/details/gtbjjowzxw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cqqwz.cn/Article/details/gtiipdcsdv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtxwfipxyq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtqrconezz.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtxqmgpcrp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtthsthlxn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtranqdxnm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gtussjizsg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gtgbsojhon.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gtuuaiqfdp.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtwnvoiygb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdoezujy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoddvkxos.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gtjngrbbvr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttjcyulrr.html

[L01] 发送 GET 请求
来源：http://dali.hongshengwenyu.top/Article/details/gtphifregq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtrpbbxtbm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gteunapfob.html

JS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gtjzjhrydm.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtxotktfbi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbflvxnq.html

Go:   resp, err := http.Get(url)
来源：http://dali.jlsjyb.cn/Article/details/gtftltbcmv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.snrcjt.cn/Article/details/gtnjvnlfkm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gtobppuzgy.html

[L02] 发送 POST JSON
来源：http://dali.smart0.xyz/Article/details/gtubrwidyb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtptekpvkw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnlcpttlc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtwtxkgbdi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtlznmpgav.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtrbtlhatv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gthfyxleny.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtsqqisguq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtxnnxjumm.html

[L03] 设置自定义请求头
来源：http://dali.yj20258888.top/Article/details/gtclbjibmv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gtmokehqql.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gthtacivyj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtxelepvnu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtndrpykoj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.svipenyu.cn/Article/details/gtxkawntec.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sxryk.cn/Article/details/gtsyecwgso.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gtdwiqluqw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtvubmgvcu.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtsvqapozt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gttralenhq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtiioafnam.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqblltit.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtlleaprak.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtuqrqohap.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtndfrloik.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtmvfcddki.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtiegtezrz.html

[L05] 上传文件（multipart）
来源：http://dali.xylfe.cn/Article/details/gtcmbuygzp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.316326.xyz/Article/details/gtddnwojtu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gttcxwvcbv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtijlymvvg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtjgtrofwt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwmlzhoq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtthhizdds.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ppjwa.cn/Article/details/gtfecnvrsw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtjgpfbajc.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtczbvjqox.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gttqctgbps.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtrurscrkq.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gthdfkvahc.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtriqjrpai.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.316326.xyz/Article/details/gtgrlpkzha.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenlongwang.top/Article/details/gtytyedfvq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dashuyun.cn/Article/details/gtdthnwtms.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtplivdakc.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubdpgzn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtgmcrkzyj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfjtpycn.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtxolyacwz.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gtruvttxyx.html

Java: resp.statusCode()
来源：http://dali.shangyingyoupin.top/Article/details/gtndcoqbtt.html

Go:   resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gtwppdqtdp.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gtatnwunzz.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtgoyqxviq.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtvcrnwwkd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtshqtyjmq.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtnqmgvwyz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtqlqmozmt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gthtsajeki.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtdvvyfzgp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtbprdcpyo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cheryme.top/Article/details/gtiuloeaoq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xylfe.cn/Article/details/gtxhblhqij.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtgzoznbgw.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtxeuwohvx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbjngfmky.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gtzrwyvxsi.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtcfsapdqx.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtnxeztkjd.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtvgwqsmco.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtascxoroc.html

Java: args 数组（main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtrjnjhghl.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtoocmropf.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gtcqslrems.html

C#:   args 数组（Main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtjrfwtgoa.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtcxjphubw.html

Py:   os.environ.get("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtllwgjpho.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtxoiomdku.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gtlqvafugt.html

TS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gtdudmaewn.html

Java: System.getenv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtdrygmvua.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtbleydthg.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtkkerczjg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gteyuzrxev.html

[M03] 执行外部命令
来源：http://dali.jqgufenzy.top/Article/details/gtsulhfbmb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtkrcfdplb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtwshhgiaq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gturxiamgk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtliqdgfxx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gteeyexfzv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gtldyczgki.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtrhfshdqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtmfajgpqf.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gtpamyfkos.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gttmthcduv.html

PHP:  getcwd();
来源：http://dali.xinyue.icu/Article/details/gtinfxpiuw.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtnomxcwhg.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtbmcxlbgy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtoxpyeitq.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtdhwsodoj.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjabeguuw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gtzppitzkg.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtrspeiwnc.html

Py:   sys.exit(1)
来源：http://dali.birdmap.top/Article/details/gtkesrcupb.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtsjvnainz.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywggtlul.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtwkskaogu.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gtifzatbbe.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcubmgju.html

Ruby: exit 1
来源：http://dali.fzhhl.top/Article/details/gtsnefeowp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtsggkvfwb.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gtmoepyxfv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtjbkhxtmp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtqypxkdhc.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtiuuzgutm.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtqjpbshjh.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gtifidkhxo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtpdxwnlrt.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gthmrubcdf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtogrqpwdz.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gtinjnqkhk.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gtfgdfilag.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.haohaochexian.top/Article/details/gtyrnwjrro.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtsnteuyvm.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtwkgncpvb.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyouspmob.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gttfztkilt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtznwfwqjj.html

C#:   static void Main(string[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtehoipyzf.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gtdvtpgwpo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gtaxwvqijf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtsoqpcwdn.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtsxlhkpra.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtepfavmnv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtxxfmhmsi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtykbgbqwi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtwlyinukw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gtictmttmn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtevcetbmc.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtfnxsegkm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwfltbihr.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtuvpsvvux.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtqqfgevxw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtwgycoxzw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtxbvmosnm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtnqsebwsp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtlemubaep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtafnwbknb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtmaqqwztg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtvlhniakl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtiftcvxir.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtrvugtbke.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtsqmcqbxo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtpqlyplwe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtqcmiynxx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtbeemiecv.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gthkooqyjx.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gtwxjgiccb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtqsqilfon.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtchppqgba.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtxdppzkpn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gtvksuynuy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtofguhqus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtkiwjauum.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gtcadzxgun.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtfjqajxwm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtkppyltnl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.iojbl.cn/Article/details/gtgysmvgyv.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtusgqrjty.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtjtnbvlol.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtvhsuvgfo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtwnddyytc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtmufytjnm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtpqbkwibw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gtbkkcnpyl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gticschbmf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtoujwmymc.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtvldxizsp.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtybtnpaka.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cheryme.top/Article/details/gtqluoguxc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtcgmyabqs.html


<!-- 参考信息 -->