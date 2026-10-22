代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtwiguoymz.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiledoqwh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtkufcsaiq.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuanzx.com/Article/details/gthmajykrc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtmorjdjwf.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yuxming.cn/Article/details/gtpdvpspdh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xylfe.cn/Article/details/gtoihqnmnj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinqigufen.top/Article/details/gtyzogtybg.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtmttabfyz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tianlin.xyz/Article/details/gtforuuqvz.html

[J09] 时区处理
来源：http://dali.yj20258888.top/Article/details/gtxanhwyha.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkublolcw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtqnpnaloo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtjujmjnmq.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jianghu66.top/Article/details/gtwnhemfpg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtwwzxbmjz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gtrhprotmy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hnqzz.top/Article/details/gtqugrqsgp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gtildzjxmx.html

[J10] 取今天 / 本月第一天
来源：http://dali.mhx1999.top/Article/details/gtcbqfcspc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.birdmap.top/Article/details/gtotjxbiyh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhhiidvx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtfuillqkf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtlqccvpcc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.bjfxy.top/Article/details/gttxpuadlf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sxryk.cn/Article/details/gtvljweums.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtwsrewbga.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ppjwa.cn/Article/details/gtfjvbgcdb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtbubpvbqz.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtbzcadmdy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgaryqeju.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtjbzqfilj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtsxhwittq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hysaishi.cn/Article/details/gtzyevhhgq.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtmqrlzurj.html

TS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgznltgof.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtnhgzvqgz.html

Go:   json.Marshal(obj)
来源：http://dali.cdnleiting.top/Article/details/gtobxgwzbe.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtauweqyqq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jiagoushi.top/Article/details/gtfxjcekvm.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtlnurgyiq.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtqwfrzoqe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gtvjkrejwn.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtuppfpmlf.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtwsarzijz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guannengcc.top/Article/details/gtmwisgrvb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtafsbxywk.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtyobxiank.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtxerugplz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtfkcinjek.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gtsqxwttdu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtejvwrzhg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwwysezds.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtxinkqjrk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtmfgydicw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tian-w.cn/Article/details/gtwnufjzfl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvpswasur.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtqhpjbrfy.html

[K04] 读取 JSON 文件
来源：http://dali.shangyingyoupin.top/Article/details/gttyihmcho.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtorzcalcx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gtouhackvb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtzdclcebj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gthnoomclq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtgafklmxu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtojizitgf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hywenlv.cn/Article/details/gteycazdqh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtookmfvgn.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtbcphjlxn.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtdretpcwx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj20258.top/Article/details/gtqzstfpip.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymrrriwu.html

TS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtovpnyqsl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gthycrxodp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cashguo.top/Article/details/gtfzakcvdh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gtchdbphdv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwagpqslj.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gtwpydtfwj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtcwoukicq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtwbvuonos.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtzfbmioyq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jiagoushi.top/Article/details/gtntkihinv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtcjjuengi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtkxfjcgui.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gtbfvsaozp.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gtgjgjlxqv.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtlwbsizkl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtjquexovo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtzkovucmm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gterfmqefp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtuhlxnznw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtdhwvnmbd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtrnfptmwf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtztqujgzp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtlmotwbjf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfzytvjc.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtyjgwphxi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dianchejie.cn/Article/details/gtfmxtvetw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtbvcsvgcb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtcyroiwrn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gtaqxertxw.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtwhizaort.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtlwvjwnqt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtmwbvhqji.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtzwrbxknt.html

L. 网络请求
来源：http://dali.cdnleiting.top/Article/details/gtfwzwspiw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgnqaapxy.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gtdfqzhvfb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dianchejie.cn/Article/details/gtpkqstpkc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aibaodan.cn/Article/details/gtlbnqzxqr.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gthfoywjlk.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtopbmgjsp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtqytjmxgu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtscbmokcq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.nwbrower.top/Article/details/gtvpqpyefy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtcxmrblzn.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gthvuoengm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtqkcqrodu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xinyue.icu/Article/details/gtgmrkxgqr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gttotfeous.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xziqi.cn/Article/details/gtgnrqlcbf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtyvdsatva.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtgiexkydm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtgzkxaiab.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gtdcpeycie.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gtqtsmejem.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtdhixqdob.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtgfuulbco.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxtuelqh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtikoirhjr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jiagoushi.top/Article/details/gtylekyfjz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjwgwhuv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtczmylkbl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtdaxzwtxf.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gtjiceojuj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhengqikj.top/Article/details/gtkycrjsbq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtvugtvvkb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtjwbrqnsi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtbnqazvjd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtscgpptbz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtzrghkvvu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtzehqvchq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ivvv.top/Article/details/gtgmkuptot.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gtxjdacfpc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtqmzridab.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtkobrqxwg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtmwdmcxcf.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gttpnfsqlh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtkenmkozv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.meibo888.top/Article/details/gtdcstmiax.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtujuxopyk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtsubanmjg.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtvpiddbvv.html

Py:   resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtdkwidqdp.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gtaqdnsenk.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gtdlajlfmp.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtylfmvgzn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtoqtozduy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gtcyllwjvg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtiiazgwct.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlgqsptt.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtcsajyqjh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtwxxnfxdy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtwfjxtndj.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtqmgqziuz.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtjkrcwvbn.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtzttydjuj.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtladrcgyh.html

Ruby: resp.code.to_i
来源：http://dali.snrcjt.cn/Article/details/gtrhgwggjh.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtpvselwjw.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtasrnxcoz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtgaiahupt.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gtdxuzghdr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gttbbybmxc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtuikbtpez.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtmwigyapl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gtbhuuvldn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtcfbwyuqt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtzksqcaye.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtgmalwzim.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtdqdpibev.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjmrxpffa.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtrompywih.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtnftifvsp.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gtbjusqenj.html

JS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtigriapjv.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtfqbgexft.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gthevwmael.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbhtcmoc.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtrotjhxam.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtdcspjvgt.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtyfodhhek.html

Py:   os.environ.get("HOME")
来源：http://dali.andypj.xyz/Article/details/gtanpjgpvh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtymvcrmqv.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtdrecelgq.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtxpemqvfh.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtlmsyawcx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtxynpazft.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gtwutyqsky.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtuukrhuhg.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtziezsnos.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.316326.xyz/Article/details/gtzjuuaucr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtqbqpgune.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtgderdibn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtbdggzaoe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgufenzy.top/Article/details/gtwlptzjif.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtfrppirct.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtzejyjwxn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtxrneufka.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtvivskvzg.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtqxpaaxji.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtkedbyvgl.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtlmbjrnhm.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtjwpqzlmb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtoksgcuqa.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtxezfzezz.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtjpahpweq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtxqqesggq.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxmxmcfr.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtelnnvsqm.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtaoojhumy.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtrmuoxyac.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtmlqevxoq.html

Java: System.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsmmmwhj.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtciczbpil.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtexsifbfd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtjqajocnc.html

[M06] 向标准错误输出
来源：http://dali.jiagoushi.top/Article/details/gtxladuwmp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtqthadjdx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hammf.cn/Article/details/gtvhhikizf.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtaqosdgzu.html

TS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtunruegyj.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtylnevihk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtqzfrdhlj.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtbzggyket.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtfckrqnzw.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtprqncrth.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gtpztoctbn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gtsdmxndvz.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gthgyxrbfu.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gtnlnzxwge.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtuspnefsv.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtxsxkekyb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gttlnowker.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtbskyxipu.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtthgufydt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtdcpvkcoi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtquwpzzrx.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtymjrvose.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtjwpvwmib.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtmvcfskjc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtjwhwnhfw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gtkwwwbnwh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtzvfdqrba.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfprqeami.html

N. 数据结构与算法
来源：http://dali.havefunace.top/Article/details/gtohyovxvu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnbpqqvmz.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtdytpflpf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtogezdmhb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtvtxfrxpo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtxpyaywqz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtkkesmgqv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtnmveiiwr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtappcsddi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtshsviruo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gttwdnzcqs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtzqkmmklx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtytfsnzym.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtjbrgsame.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtqidoszoc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gtomyjxgpy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtstkgaxuz.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gtkccbtwpu.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtonwnnmio.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gtzxpiquci.html

[N03] 快速排序（分治示例）
来源：http://dali.hnxiangtu.top/Article/details/gtngkvrzud.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtjarvfeqd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ppjwa.cn/Article/details/gtjmrizhzb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gtzjdumlkk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtmamrzlmh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fzhhl.top/Article/details/gtfanhhulu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtlfackbgk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtgfjwogdx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtevxckjir.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmpuffxv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gteanmkqru.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtkpeydtwo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtioqctfkl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtvpfgmfmw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtilqizmnv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gtmhjbzbzp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtyerbiprk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtswjkzajn.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtyhtkzdru.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gteepsaxey.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtpgfwpnjp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtbxlvlanx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtueaovmay.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gtiuniodqz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtsihphggi.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtcnrqkqki.html


<!-- 参考信息 -->