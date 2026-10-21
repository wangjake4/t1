代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtkpeedyxt.html

[J08] 提取年月日与星期
来源：http://dali.shuidangran.top/Article/details/gtbhljuwuk.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ivvv.top/Article/details/gtuxxdedpk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenlongwang.top/Article/details/gtgbgfxdpb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtftjihngi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gtpnfjowez.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxqqngtr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtvmgzwncu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwbykiti.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtcvejwapd.html

[J09] 时区处理
来源：http://dali.hnxiangtu.top/Article/details/gtqbbbjjvd.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yuxming.cn/Article/details/gtjfvphsgl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yanxiufei.cn/Article/details/gtrgzdwyxn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tanke756.top/Article/details/gtzqcqbuak.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.smart0.xyz/Article/details/gtyaxxprwa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yonumen.top/Article/details/gtbsoyhwcs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.tanke756.top/Article/details/gtjczsyyhf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtpltuqmra.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhoulong.xyz/Article/details/gtmczezjcg.html

[J10] 取今天 / 本月第一天
来源：http://dali.hfpthk.cn/Article/details/gtyxraeuhh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xinyue.icu/Article/details/gtthnavyhd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gzhubu.top/Article/details/gtmezgordi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtgjztyvox.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gticeibzer.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sweek.top/Article/details/gtdbkbjuhc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pycfn.com/Article/details/gtqixejihu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guowangkeji.top/Article/details/gthqgivqhg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxuscicz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtemvqcdjb.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtmudxjgbc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkybqgjwz.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtxrbgnaks.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.havefunace.top/Article/details/gtbcrvqfrq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtrqrgwfie.html

JS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtmnvplgvb.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtrxvyjjrh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cashguo.top/Article/details/gtqxafqivp.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gtctlpuijh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtifausxry.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtyynmsvml.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtpqqizuxo.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnimodihn.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gtitcdzmys.html

JS:   JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtfjitofpn.html

TS:   JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtauijtjsa.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhexbikl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gttvffbigj.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtikcpaexj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fzhhl.top/Article/details/gtqissnycv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gthaxdwkda.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtoxlaffjr.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnludllsk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtnhulsetz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtadluqkod.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtaxhwbdtr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtyzrpnprj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtpapljebs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cdnleiting.top/Article/details/gtylquennq.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtmnnvfyoq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtcardyupy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtlqtpdlpz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtovlamqut.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtbuzivial.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtqlkjdjyq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtjeqqqefe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtvodyppjz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gthtoemefh.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtaulclbvz.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzotfanr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nanxinkj.top/Article/details/gtjxrashhv.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtzohfoagk.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtgpytmnry.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gtsmzihwat.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtekeqputl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gtxbcphmfw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sysykeji.top/Article/details/gtrwvqkkmh.html

[K06] 解析 URL 查询串
来源：http://dali.quarkkingdee.top/Article/details/gtrgfdbtyz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtujlsponu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jyoumei.cn/Article/details/gtcenfowtj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gtauzehlhz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtqvorjtnh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtdryamjpo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtjeggpqex.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkuwnyoag.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gthyjdlyeu.html

[K07] 进制转换
来源：http://dali.yonumen.top/Article/details/gtyvhefeqv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtamsvcjag.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.quarkkingdee.top/Article/details/gtjrrlhnnc.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gthdxrgwpw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtotgzbncm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtddvuljwe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtqisrbxqb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tianlin.xyz/Article/details/gtngondqdu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtocmwmmdo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aizwys.cn/Article/details/gtjhplylld.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtswqsjdtz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtmyilukdr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtwgobjzvu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqdhjewa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.feifeiyinyue.top/Article/details/gtvnfkokst.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtrvprtsxi.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gtstwaqheq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtjizytrcj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtzgbzlhax.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtibyglbvr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttgtxzccv.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gtdsggefxl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtgfpfklrk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gtgzwsyxku.html

JS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtkcawsqus.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtvofkybax.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gtyezjmkpk.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtcqzkrbam.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gotoacloud.top/Article/details/gtljofbjvd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gtnezsbsdw.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtrowmwvuj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtldjlrpul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtokaqmqyr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtiiytmkvl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtftwmhhsl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gtsgsewzsy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtmtpbigjh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtvihicnib.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gtwgovomli.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtuaidonhk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtxrcbnsxt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtjbsltvuc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtohyokcja.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtwubqkwvz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlponanw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtzvfniiag.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtmwgdfvgp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtancawqna.html

[L04] 设置超时
来源：http://dali.yj20258.top/Article/details/gtknfzoxyz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtoiyknopc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gtzldxizuk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtpngytigc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtsdotexhq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtcwaktygv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtwdjzpeol.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtagkhkhzi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.nanxuanxn.top/Article/details/gtindmqhlh.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gtuhnddgua.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuanzx.com/Article/details/gtrjuurnvs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gtkhheedqk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gtqecksxya.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtpzuifkdc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtowcyignk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtguycjufh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtdaowhprm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvijzvfci.html

[L06] 解析响应为 JSON
来源：http://dali.meibo888.top/Article/details/gtyyafyntx.html

Py:   resp.json()
来源：http://dali.fengsongda.top/Article/details/gtwrovxlgg.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtqzptttmh.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtexxuyapx.html

TS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtjwdiutxn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtczlljdon.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtdxydemtn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gtgocyltar.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuxming.cn/Article/details/gtxodaypmh.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gteoantyjm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gtktqmzagu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gtalgifbmz.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtdkhzzejq.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gthaalyajk.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gtwwfivksz.html

Go:   resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtfenwxyyp.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtbmaecrsi.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gthhtlaftq.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtxjqxyipc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtnbtnqhxz.html

PHP:  curl_multi_init() 系列
来源：http://dali.sxryk.cn/Article/details/gtxqzwhmjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtvgujysmx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtcfqiwapm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xinyue.icu/Article/details/gteqvkrdyw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxgzwlgn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtmnjdpflm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtejkwyntj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtaafisonq.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gtamfkknuh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtyhyxabpy.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtmxomrhyq.html

Py:   sys.argv[1:]
来源：http://dali.sysykeji.top/Article/details/gthfefhcxk.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtyxmnkltm.html

JS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gtgbljmiiw.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gtwlpcdwmb.html

Java: args 数组（main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gtqsjsfhin.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtbsgvfjoq.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtkiidxmeq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtyytdesla.html

[M02] 读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtmtpzribr.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtsddjaeld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaslzidio.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtjdlgtkyh.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtppikiwqg.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtqsoocsgt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtnunnoxlh.html

Ruby: ENV["HOME"]
来源：http://dali.chenzaomai.com/Article/details/gtejfxseto.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gtbmfvtgyi.html

[M03] 执行外部命令
来源：http://dali.nanxuanxn.top/Article/details/gtpplngspk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gtgkgkeglk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ybcxt.top/Article/details/gtufsyoktj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gticpbrhzc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtwsfusukf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gthutphnpv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtuziilufc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtkcygzmyb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gtzuewlmjk.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gtbvvznhlx.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gtnjdtsryv.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtylaocplq.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtkqdmhsfu.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtbmlrmnqk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gtyiimnpcr.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gteemppnfr.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtpmjgujcp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtxntdrlym.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtesixlmlh.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtnglntjpd.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtmwretigb.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtsugocxvp.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtffmfamwh.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtgdujommg.html

Go:   os.Exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtsefnacof.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtirrtipbu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtojnfbarv.html

[M06] 向标准错误输出
来源：http://dali.nanxinkj.top/Article/details/gtqzvpnzhp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtrsflatkw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcoxjzev.html

JS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtxqqddiay.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtvjxmlfwb.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtybvsacfb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pengpengdd.cyou/Article/details/gtmkdpomqy.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gthpsyqfvu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtqcayhyue.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gtnryllcdb.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gtaxcxhrea.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtynolsjdi.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtrysfzxww.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtcwuzvhxi.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtwvqzbekh.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gtlkjdsbas.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtereipljf.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtviosahom.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtephlxzov.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtbwiaeeof.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtjklrpxms.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyumppsxo.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtresutccu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gtfnuywbdz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtjzhuzedb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtuzkpgwcj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtlamlfduu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwvaprhqf.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtinzcpjvn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdphujyul.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtyxrkkmmv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtogokrswr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtjlsowtmc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gthkoxwhvc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtquhmoxah.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gttjnplnsf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjrqwzznk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gtxfnzhkpk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtnrxfosqa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtdragohle.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtbucmmjmw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gtevlxiegf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gtrmdzqkoa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gturtptbsa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xziqi.cn/Article/details/gtrlgyajic.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtvmuhylgy.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtrxeilqny.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gthtoxdior.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtlemzmgns.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtxllswfvf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtozrwcibq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxubrfxap.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtoqsmldmw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gtsnlxgmwz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gtyjmkspsb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nwbrower.top/Article/details/gtahvfgfxw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtmgzsclzu.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gtrrlgplgf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtapqzvbff.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmhhtilka.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtbefjqunw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtoghnjcqy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtnkohbifl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtoqiqgywf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsffuuqez.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtcxprkugp.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtjgddiefd.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtjutuzzpw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gtunlrmzyp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvodpshyu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtfjwrszgt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gteokifclq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtscxjdpag.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gtzftohtlu.html


<!-- 参考信息 -->