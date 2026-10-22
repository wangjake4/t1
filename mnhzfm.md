代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtcpkhmsew.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtlvmocgzz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtopluvrdu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gthbcvcrbt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtnsakjmdy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.dashuyun.cn/Article/details/gtqritfwrp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.wangdashe.top/Article/details/gtdrkgskps.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sufxvd.cn/Article/details/gttevaolnw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gtimfvwuwz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtpaoxmfqi.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtpmabaxpe.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cucudq.cn/Article/details/gtlkmrpwkn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhiwuduotai.top/Article/details/gtgoopuyat.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtoplgcrgb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtiyxxpayf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.mhx1999.top/Article/details/gtujzjwbmv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.meibo888.top/Article/details/gtilvnjrkx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xziqi.cn/Article/details/gttkdcpcyg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj202588.top/Article/details/gtbpbugfrn.html

[J10] 取今天 / 本月第一天
来源：http://dali.wangdashe.top/Article/details/gtchxciqaj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtkgtmvtju.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.316326.xyz/Article/details/gtcptyeheu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gtzqdzdlwf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.nanxinkj.top/Article/details/gttpqvzack.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtdfbrctjf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yanxiufei.cn/Article/details/gtwvnvrmtd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtqxlbcnvx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cdnleiting.top/Article/details/gtfhiihcso.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttdfysydy.html

K. JSON 与序列化
来源：http://dali.xuetiantiany.cn/Article/details/gtyyooppxh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdcmtzthk.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gteazjopte.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtaiklicfa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtmvxhhuvx.html

JS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtvigyydlc.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtertjfgve.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtjwlwszpn.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtadzjfvyp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gtiqshcokz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtkyonwibe.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtndospgzi.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gtqdnuvytk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtxlmcexyo.html

JS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtowbndzri.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtabxgbdwn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj20258.top/Article/details/gttuqmdsel.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtmhgppcfb.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtlptputwl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtvxfzhrgb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtsqvivzvo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtpiglikvu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtjushqpdg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtacuzyxjr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtfkjqcxtk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtegtzkguk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gtuszioocv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gthxtahdxw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gtgjkpbipm.html

[K04] 读取 JSON 文件
来源：http://dali.0kj1m.cn/Article/details/gtqyyohjij.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtvypozsqq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtibgqmpaq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdntrwvye.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gtglekkwwa.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtmjjdcqjr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtlbqbztnl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.andypj.xyz/Article/details/gtwusdemfn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtnexmmxak.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gtfyhdylvm.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtapdkzqie.html

PHP:  unserialize(serialize($obj));
来源：http://dali.havefunace.top/Article/details/gteynespnf.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtmjcnkxrn.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttktwxnqa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtwukbntvi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gthjpcbhrz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrctljab.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtbcrhtfhy.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtspetegvq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gtqhlhtdya.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guowangkeji.top/Article/details/gtnwrbrddf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyiernlw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtkkmtklia.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtvyjqqwuf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtyhpovxip.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtyqbvljfa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtpgunpsyx.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtxymbomek.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtochywavt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gtgkxqxcxy.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtotdcqyeu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtinkxhoby.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtnbcaqtho.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sysykeji.top/Article/details/gtttiwhpad.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gthigapovx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtvpykbfby.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gthdzipcgl.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtgtuozwyf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtyunwzngv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtukoqyavx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtntxqbanh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtobdtcfrt.html

Go:   encoding/gob
来源：http://dali.316326.xyz/Article/details/gtawiobwdt.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtxpgprftt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtuwkydogk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdynocjuo.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtekdwzjeh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthvhtyqop.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtjthjlysq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gthraleewd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtdtzeivwe.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjzkanue.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtmtbcwlnr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtkfzilvan.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtpkammgcy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtlfdbfujk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtwfdhfcns.html

[L02] 发送 POST JSON
来源：http://dali.guannengcc.top/Article/details/gtoofhfrqp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtjhnuycjc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gtkjypocfc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtiaaoucqn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtmsfksfww.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtsqhxbnwo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtgqidczst.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtnytgfowf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtgifpvhau.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdtxyslrp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtfuskpbjj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtjpsbojhe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtptvtalhn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtsfcvykwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gtpzflimoc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtnelalspp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtjfzpehmn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xinyue.icu/Article/details/gtebpwgdxu.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtivfqvknl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtnhckthct.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gtrsewjddt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtnbeufbbh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtwilmlxzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gtqbesvazc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yvedp.cn/Article/details/gttdweeouu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gthyhsminf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gthgpisbza.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gtqrzwpcab.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhvtocve.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtkjuuafeq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gthnbcqpde.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtrbnevmvm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtvjzstevf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqlclmjl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtgqzrorqj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtpnveoitf.html

[L06] 解析响应为 JSON
来源：http://dali.shuidangran.top/Article/details/gtlwcwousz.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gthghaxrev.html

PHP:  json_decode($body, true);
来源：http://dali.nanxinkj.top/Article/details/gtuwwjfkxu.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtwszvkpmo.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gtrbxkbirj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtcllzipab.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtncmykjjb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtvgjrndfl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtrxtarczc.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gtkojfwrxj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtpqocyjoc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtmziqsedh.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gttwlqzmsl.html

TS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtytwqylol.html

Java: resp.statusCode()
来源：http://dali.sysykeji.top/Article/details/gtobkpvpsy.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gtupikbhoi.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtpzywcnnn.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gttaqbhqfc.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtrvhveuan.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtirzrffgf.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gtzqnacnly.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtjmxieeqx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtmbxwcdze.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtnckhceai.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gthhitjdqw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hfpthk.cn/Article/details/gtnibnxgwv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtmitfhegu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtpoeszcrw.html

M. 命令行 / 进程 / 环境
来源：http://dali.hammf.cn/Article/details/gttisjlkif.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwgqomcbj.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gtjhyrothy.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtvwntjwek.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtlsswmihf.html

JS:   process.argv.slice(2)
来源：http://dali.svipenyu.cn/Article/details/gtjvnvufgj.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtngplrfrd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtdmfrxvvn.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gturnjyxea.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvzzaxso.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gtgeqtysfb.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtssqqgloc.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gtrjbfloif.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtofzzbcwa.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtnixbnhnc.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxdybmrl.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gthakhjqtb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwmhmumn.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gttkhtzgxa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtzsqdleub.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtttzdlqhu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumaioobq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gteqfoztsp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtegbammaf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtagruvoup.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dashuyun.cn/Article/details/gtntbprwjv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtfipkmvrp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtgbslvafb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxmfjbdf.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gttgcpecga.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gtvuptfpiu.html

PHP:  getcwd();
来源：http://dali.cucudq.cn/Article/details/gtlwyjjdrg.html

JS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtmkgmmmqr.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtgiwwsmwg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtyzsggrpr.html

Go:   os.Getwd()
来源：http://dali.yonumen.top/Article/details/gtxwkzhhvh.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtrnwtfbnu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cashguo.top/Article/details/gtiekueklq.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtobyhkzrl.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gtuxezwkqq.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtndiuabcj.html

JS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtaddriclg.html

TS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtfkjheavh.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtwuxxjuba.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtghwkqtix.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtypqytadl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxinkj.top/Article/details/gttvxvnkhs.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtabgwyuvo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtoqvovcea.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gtqheflvkw.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtronmbtvc.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtjpomoakf.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gtgxijmzna.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.iojbl.cn/Article/details/gtirrenrxl.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtjgqvjqrr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtcuwsfixi.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtmeszppzt.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtrzavsxse.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.meibo888.top/Article/details/gtvotoogim.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtacjsjbnr.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtymqkjxfo.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gtdtcnntun.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtyfnoeznk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtpabfhyxw.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtbelfbaqf.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtivycfhvx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gtjoyyfwhw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhiwuduotai.top/Article/details/gtabkxlxud.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtjhpfaldo.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtuadqwafb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gtufmbvzbe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtixhrmdhy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gthiwrgxcl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtnvcfrwuu.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtxfmeqbnh.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtcisgwxyj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcytmrjdh.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gtfvoclggo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtrhpdfncv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtvwnxcpeq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtrrzfkwni.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtfsedhdzb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtdrgviorh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtkycyihlv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtuqqrgkzt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtordllsgu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtnrmvfrfg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtxowtqbid.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.havefunace.top/Article/details/gtzlqxvrgh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtnasspygn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtxlapxpwg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtbramsdtb.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtfjrilrbb.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtcgepzkst.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtglttvegy.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtnozztiod.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gttonplpyp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtfoobrgan.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtilxveode.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtwsybbvut.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gtuxjutafb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtiufvrjhp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gtekeuptkd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gthoqmiewm.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gtybylkben.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtmgpstjbg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gthqxfemtc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gttgeqqmys.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtaxqvhaea.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiszkeffx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtyjlkmwnl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gturqfubia.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtgrnsvayw.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfchbbtok.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gtlxoboqhr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhengqikj.top/Article/details/gterdujzpe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gtspqfofrg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjawhopof.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gtnfajdvil.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fengsongda.top/Article/details/gtvdhlcdta.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gtxftdlcqy.html


<!-- 参考信息 -->