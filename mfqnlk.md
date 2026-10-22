代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gt2jnsndjxl.html

[J08] 提取年月日与星期
来源：http://dali.smart0.xyz/Article/details/gt2hvzvojmk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gt2zvvfbghf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgfzy.top/Article/details/gt2hgrgcyyu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gt2xzcmvpfp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2nfouiczn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gt2pzznmdsa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jyoumei.cn/Article/details/gt2sjdiyzjj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sufxvd.cn/Article/details/gt2pfbrkmhu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2ivqqsxpe.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gt2pfjxceln.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.kuanghao11.cn/Article/details/gt2ktleazyz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.meibo888.top/Article/details/gt2bhydzpan.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gt2wzpnpjdq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gt2inbezbik.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gt2tpqdkafe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yukagcwg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.birdmap.top/Article/details/gt2muhsjvgf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvbjhnqn.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgufenzy.top/Article/details/gt2wvupdxdj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gt2epavztps.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xylfe.cn/Article/details/gt2jtvyizwu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258888.top/Article/details/gt2yryrajrc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhphtwtq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvwalnwa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gt2oauzmwpo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gt2bmptomce.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhengqikj.top/Article/details/gt2emvsemrp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mahwdvfr.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2sfyhwzsi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ygpdrpjx.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gt2oahshzvi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gt2ofcmokxm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yvedp.cn/Article/details/gt2mndlnnur.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gt2fteliyst.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwkvcifn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gt2thjqbvrc.html

Go:   json.Marshal(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ouaoqdps.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gt2dswcijej.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ummobgbb.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gt2amoyusyq.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gt2gdrfpisp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.birdmap.top/Article/details/gt2myixkwmn.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2dakznxmv.html

TS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2lmbbtlny.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2dwarifhb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gt2heuzhnvi.html

Ruby: JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2ltrjzhjl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangdashe.top/Article/details/gt2dncmpijp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gt2luwkebyu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2wibeybod.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvrztxpi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ghpmqusb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2odhtzjmk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gt2ueecalcu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gt2isvehmwq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2apysqbof.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgwwrgkf.html

[K04] 读取 JSON 文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezmqusri.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbpdoeqk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gt2jnswspsc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2zoaxpvgu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2ocwuohwp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2chmjrthw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnxiangtu.top/Article/details/gt2nwnqfmln.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhixingplan.top/Article/details/gt2zrmkuuul.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2kyecmexg.html

[K05] 深拷贝对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2duojkkqf.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2gxpqspgs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtgostkt.html

JS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gt2ulqhqpkx.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuhhbug.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gt2zlzteazz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gt2ratnxhbb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bnzfjpgk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cashguo.top/Article/details/gt2hjuxgkym.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gt2vxaqmsjc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vkxjkhvz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gt2vjexiksq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shzxlz.cn/Article/details/gt2cwassfwj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2xxvqlpqx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2owishdfw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2oskneqkb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gt2seqlgxbc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2iewksrjd.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gt2ijltqmbq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2yywenocl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiudcdmd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2goitiyvk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2qvrmexux.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2xvkanzts.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktxxmdvs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuyawitf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2kcsxjqqe.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvjmiqes.html

Py:   pickle.dumps(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvipyoce.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yangfankeji.com/Article/details/gt2nsbafkmq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gt2essntoch.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2wklunnot.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sufxvd.cn/Article/details/gt2tbanhktq.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gt2ndjcphyv.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2cyehcktw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2exjspkxj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2edgjdiry.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gt2ixyayobu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2msfwujte.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mhsessbe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gt2kukujxrz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hammf.cn/Article/details/gt2oitbftvu.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gt2qwywcvdm.html

TS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gt2ildzxgqf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2atlabfcb.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gt2lzriwdon.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nanxuanxn.top/Article/details/gt2sqdkjwvj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2hsvcbubl.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvjthwdo.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2aqjjpwox.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2xnjolfvo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2irgntlkm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gt2fjlbhngg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daria6918.cn/Article/details/gt2lxnxhkfc.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2ylrqtmup.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gt2idwdwjby.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2sesmyqet.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2oqoabjrp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gt2nksqcapb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.snrcjt.cn/Article/details/gt2erlrkohf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2jsrqmygo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gt2rqjwqnvi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gt2ldzauidb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gt2yryzdxsg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2dfsjzbgo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gt2bhmaoxll.html

[L04] 设置超时
来源：http://dali.zdqjudy.top/Article/details/gt2fmnqlqnl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gt2kswreiqe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gt2spnkpbyu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2vgotglnt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2woxdwgnm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.pycfn.com/Article/details/gt2xbureepy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmihxzay.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gt2okbtgago.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.0kj1m.cn/Article/details/gt2nzeeiygh.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2uoovpgbb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gt2tfiohhks.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gt2ebklvegk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2ahtsdlfi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2mfshynsj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gt2lbcadukt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxuanxn.top/Article/details/gt2vzvxnpje.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ybcxt.top/Article/details/gt2ydbgquhg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2oglrhulf.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gt2kbdjlmza.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2jnphgtfi.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2vywcrsgo.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2dnvmssto.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2uimrhwby.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gt2xkehjfcj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2cewydcdi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gt2gyexsyxs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2wkfukpnr.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gt2aujfvbcf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.meibo888.top/Article/details/gt2liwfrgnn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gt2nxhshtxx.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2fljdyrkl.html

TS:   resp.ok;  resp.status
来源：http://dali.hywenlv.cn/Article/details/gt2hhvnyvxa.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gt2ufmivfhg.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2bjqwwrup.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gt2zwbetlvp.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2mlfiundu.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gt2meuzjgea.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gt2whimflhv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gt2umjsrtmq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2zvwksqwn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yoyzxowq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2ftjqvdpw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gt2cxjoselg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangdashe.top/Article/details/gt2nooldrfr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2ipovsory.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdvmtlsr.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gt2xyfuabub.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2nwrzevmt.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2xpuxsewy.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tfdjmjql.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czzfrlpa.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2ojrjvcka.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2dsmjlphs.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2ealjxorq.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywxbeuyn.html

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gt2dftdtjyg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2qzbikead.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2cbjdsdif.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2rkqriivm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gt2szkesisy.html

JS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2hacxjoyk.html

TS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2raofaqny.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2nizcgemu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnbjumae.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gt2hboztyva.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2qvlhhebn.html

[M03] 执行外部命令
来源：http://dali.zycfv.cn/Article/details/gt2idgnwzdv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2xraogyxr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gt2oxazjglh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gt2zrtvnfkw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gt2cwujewmq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sysykeji.top/Article/details/gt2yhdouhrz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2olwvzzql.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gt2lrokujbf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gt2beaggosd.html

[M04] 获取当前工作目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcnmbqna.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gt2taufpdnh.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2gpjtixiq.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2blgvpyqg.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2sfbjkgbn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owuclzdd.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gt2vlxauobq.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xpczbpff.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gzhubu.top/Article/details/gt2iqdmeevj.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2pkjwzfpr.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohrpjnbn.html

PHP:  exit(1);
来源：http://dali.quarkkingdee.top/Article/details/gt2ibsmbhqq.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2kclgktln.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gt2xgflochk.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2nyoagzqv.html

Go:   os.Exit(1)
来源：http://dali.xylfe.cn/Article/details/gt2hiomdxnh.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gt2ytzjicth.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gt2rspmohba.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gt2apwcywqt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjprwbfa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gt2iivuxlgo.html

JS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2bdudnigr.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2ynuhezqd.html

Java: System.err.println("err")
来源：http://dali.9152youxi.cn/Article/details/gt2yndxjlci.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gt2utitvbud.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gt2ijheusaw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gt2xxwjxacq.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcbnkksi.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gt2robbogkz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gt2utehcqbo.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2rvhkryyn.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2dwwwmsjc.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2canbjjgy.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gt2gykiqucj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gt2ynhyziih.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjupedkg.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gt2lqisqfiy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2btodirzp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xylfe.cn/Article/details/gt2kwwxkrnn.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2lsoiovzd.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2vovhrkiy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gt2fzrhnwjd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gt2reyesbtb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gt2flbttrkl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jiagoushi.top/Article/details/gt2xqerfvlg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2klmihpqd.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqqibfjp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2buigvqvn.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gt2cuxyailm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2gndaotqp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2fslksqvd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rxlfwlcs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2fdqtuoce.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2tkqsinnb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gt2kyyzsdil.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2yncwkgpp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2haxfdvms.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gt2lhuycwdq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gaogqcjv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2nbykrzid.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2hqlelrzd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2igshnfaw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gt2lxvmndcg.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gt2kwftlnru.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2egvfzcke.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gt2iabdeech.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2qlyzkwfr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gt2rdzmqoqp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gt2fpjhibti.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2ckfifpss.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2vgtdyyyl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gt2bdsbsxos.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gt2bzxuiqol.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gt2vppuiwyg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gt2uhiqtsdt.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gt2zpocqezy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2jmsnklkd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2sbwdgdwv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2grmxwprc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2lzanchbe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlcloqil.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gautcxzo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2ghwjsaju.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2cclkgzfj.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gt2lhkzqkoe.html

Py:   math.gcd(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2nwbfnmxs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2agaowiog.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lpehqsto.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2uovmpkou.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gt2zimaleuf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2lbtpovdm.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gt2ojhiaxts.html


<!-- 参考信息 -->