代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xylfe.cn/Article/details/gtroxmlfvb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hysaishi.cn/Article/details/gtguznlqdz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tanke756.top/Article/details/gtemhigpcb.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gtlybzzude.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtismbjbbz.html

[J08] 提取年月日与星期
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlporombd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.tianlin.xyz/Article/details/gtpyqgztif.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhixingplan.top/Article/details/gtcptsmfkk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemnlatxl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtphdvcdfo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tian-w.cn/Article/details/gthgughlft.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yongpay.top/Article/details/gtlghgzqjp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xylfe.cn/Article/details/gtwovuphko.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtgugczihi.html

[J09] 时区处理
来源：http://dali.gogol.net.cn/Article/details/gthtzvzznx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tanke756.top/Article/details/gtnvhnyfcb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtnlutpnil.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtqccmultt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.316326.xyz/Article/details/gthzmbqlws.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gtdobqsmhj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gteqiwcxgr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gtkblmvhmv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shzxlz.cn/Article/details/gtnkukazeg.html

[J10] 取今天 / 本月第一天
来源：http://dali.0kj1m.cn/Article/details/gthkfrmmje.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.havefunace.top/Article/details/gtueuendqi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfljcvwm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtiruzdzbg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtxnnvvbpl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtffqvdkde.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenlongwang.top/Article/details/gtpipeusfs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yueranfly.top/Article/details/gtmcfivqut.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenlongwang.top/Article/details/gtxdzaqdbe.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtbbjtvwbo.html

K. JSON 与序列化
来源：http://dali.hfpthk.cn/Article/details/gtacylmvnv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvrekgiwn.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtueuutggd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtoirhlihb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtijntkllx.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtvbwlginv.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtppcdcdvn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtwejrkxmi.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtklsfogzi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gtrikwliwu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtdkaebbpa.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtxdwollct.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtgruuizet.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtchezksmh.html

JS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtjyuaqcvc.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtuqlgsbmx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ybcxt.top/Article/details/gtpxxytmhl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtqameacxa.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtdkczvjnk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gtrvzmrsql.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gtrfuznika.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hammf.cn/Article/details/gtdnhwrcif.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtjbakpmxf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtnkgcpmcq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtuqsxeusa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtuvagzmqk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gtlzeqyzvt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtbvebbixq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtjexoatos.html

[K04] 读取 JSON 文件
来源：http://dali.shzxlz.cn/Article/details/gtqoqccnls.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtlrgoqmzi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtljddzzek.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtbcfmayto.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtqeeryykz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258.top/Article/details/gtmgjwvxcy.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtgrynunbu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gaohongyu789.top/Article/details/gtyjftjytc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtqogdtcjf.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtnusnuhue.html

Py:   copy.deepcopy(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuyjkikf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqmttbus.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtgcgnylyn.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtydfsnkoj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cheryme.top/Article/details/gtllcwzkvw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gtojfwmagd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljkqotvg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtcrzkchnj.html

[K06] 解析 URL 查询串
来源：http://dali.bjfxy.top/Article/details/gtfshbpgnv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gthmvjjluf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtxyycraec.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtnzewllko.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtkxhcomwn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gtnwbczsng.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtjqaraexb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtwmbvasry.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtzxvuuhem.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtedomfrar.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtgyywosgb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtffhmxfks.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtwqbnxxxj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysrxlnri.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtdleaoniq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hammf.cn/Article/details/gtkxqduups.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gttjjveopv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtuktmnvca.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gtwsvstroz.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtacmmamla.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gthabhomdz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtkztajgul.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhqstsmb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gtfisrwvfk.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtkmtaixnn.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gtvgckljya.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtmvkodicx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtukviaaep.html

L. 网络请求
来源：http://dali.yongpay.top/Article/details/gtycpyqiuh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxugnxqqb.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gthuavsyws.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258888.top/Article/details/gtuyhazovi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtmrpjsthh.html

JS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gtiydwwrvg.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtggbqytql.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhgtgknw.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtisevpmqn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.aibaodan.cn/Article/details/gtlwlazych.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.redwolf501.top/Article/details/gtczmjznrk.html

[L02] 发送 POST JSON
来源：http://dali.bjfxy.top/Article/details/gtkjlqvite.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenjidiqi.icu/Article/details/gtuatrassy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtamcerbpn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtjrucjley.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtrxezurdy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtcmbcnlkw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gtqjotlzbi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtuacfwchl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtqkdknmmz.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtyibkquhe.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtyfasdkfl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtexyvehxh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gtzoawusxl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtqsjvpsyw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gttyydssgr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gttyaioalg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gtyotoeuqh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtexqmgweb.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtnqjxwyib.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtlemwrtzg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtmztnktpx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtrcldpwxl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtmbmflmvm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtpdegdsnr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gttfxgkodt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gtwuptahjm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gttqvfmgwo.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtmanouvcb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtyiydtmjg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gtadgptjqd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtjmxwpfbg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwexmqxk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gtjqmnnoin.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xylfe.cn/Article/details/gtzstohqmi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gtadjvqait.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwxsthnbb.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtcynohnni.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtoifxlxii.html

PHP:  json_decode($body, true);
来源：http://dali.nanxuanxn.top/Article/details/gtdrddbdcg.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtqwmiqgta.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrhxvsdb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gtovvhubdj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtwjhbdocl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gthmtarvce.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gtfnuyjtas.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtlzonnsen.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtbnalnspj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtqdbuwifi.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gthtuzthxj.html

TS:   resp.ok;  resp.status
来源：http://dali.316326.xyz/Article/details/gthvsnpmxi.html

Java: resp.statusCode()
来源：http://dali.hammf.cn/Article/details/gtfzkjsmlw.html

Go:   resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtirvrpmqk.html

Ruby: resp.code.to_i
来源：http://dali.zhoulong.xyz/Article/details/gtspvtvfgv.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtmautfvnz.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtohtlomrv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gtcyqnigtq.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtimqxszqk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtswcigkha.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtarcngihq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtiwrknihb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtqkhzkmbd.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtxtuhwbtb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtocrhnrim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtowiwdpek.html

M. 命令行 / 进程 / 环境
来源：http://dali.fzhhl.top/Article/details/gtlpolhdzu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtteoyraxk.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtovzwqobm.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtipjfnqwh.html

PHP:  $argv;  $argc;
来源：http://dali.iojbl.cn/Article/details/gtblufrjov.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtoxxrpoju.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtwsscvvcg.html

Java: args 数组（main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gttdtigssi.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtfyyycono.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtedizioig.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtfoxbkwia.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtftbkcgto.html

Py:   os.environ.get("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtxjcjxtzn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtqxnjzwbj.html

JS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtzypixwkr.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvuvkaqb.html

Java: System.getenv("HOME")
来源：http://dali.meibo888.top/Article/details/gtjeceoaez.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtbibuxdxo.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gtuxfazmhu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtidpwpzkc.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtnaxlfpmg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhongyouzk.top/Article/details/gtwolbvyrp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtknhxmfwa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtaunmbvxg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gtyvcxseau.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gtweoxbpvq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtdivwjwrb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtileweevc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtlwhjsjzs.html

[M04] 获取当前工作目录
来源：http://dali.cucudq.cn/Article/details/gtjhtcjeum.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtuizbhvuz.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtwdxvdbfs.html

JS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gtswdwbusj.html

TS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gtjmobdqdk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngnpdwat.html

Go:   os.Getwd()
来源：http://dali.fzhhl.top/Article/details/gtyapcgcuj.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtfycuylki.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtbwcrcsal.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtftwuymmq.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtexhmgjxy.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtieatnkpp.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtvctevaik.html

TS:   process.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtbqapfrzu.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtadtgqdhf.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtxcedlewm.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtbfpniyyk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtwraasoks.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtupjqkdki.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbonlbtry.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtybrlbhbq.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkzncrbm.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkcxxtcx.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtblhysqso.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtdladmcrg.html

Ruby: warn "err"
来源：http://dali.wangdashe.top/Article/details/gttlqmkzhd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gtcvhogtox.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtuudvtojt.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gturrzmopu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gtysucebci.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtujporktp.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtkcwfdxsh.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gtcrakqpfv.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtfkwrvtwo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigfzy.top/Article/details/gtxdtugnhj.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtakmeqalk.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gteojoouef.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfqleoph.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtfxgjekqf.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gttkzynoka.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtoshuwwck.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtzgyzwzor.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtkxinipwi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtntxuznha.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gtcciytybp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtetruehkh.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gtzoingxnj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpcjawsvd.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtweydpvpz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtiqjgvumi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtodnnoipb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gthitzipia.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtxibiscov.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtnnpgdqud.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtbiryviex.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gtawtngbgd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtnmayrpbw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtmntcucvm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtdwnoljpm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtrxcvyhqq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtbdrnwqnk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtfhudivqg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtfzfwxitw.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfytabog.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtalddjfqt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtkibjbvel.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtutyuzyqb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtlstvbhqa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gtcahhxiro.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtsvbvpijh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtxriefylm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gtcwicqhdq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtpttnbswy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtgsvnizgg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gteeqwdddc.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfytiaay.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gtafbyhlop.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtjkcdlfry.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtebkgrzfz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtkkoomnxg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtzannyyig.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gtmluqdlzx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtqzvwznxe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtixqxwjvj.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtevbrvwji.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtiqoxwsqh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtehgunimi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gthenpxmby.html


<!-- 参考信息 -->