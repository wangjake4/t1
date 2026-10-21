代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtqntxavox.html

[J08] 提取年月日与星期
来源：http://dali.cucudq.cn/Article/details/gtahrgfpyv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtccckmwjs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtuulidzge.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nwbrower.top/Article/details/gttkphkngg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtrmgczfvm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hfpthk.cn/Article/details/gtlfurjfzr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtpqobahsf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yangfankeji.com/Article/details/gtqhxhsdlt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gtqnmmzkjw.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gtlkorqysr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.andypj.xyz/Article/details/gtyzxilwfb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwiztfrf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtxyjdbepb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtwisqmfiw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daxiang520.top/Article/details/gtwjaknwfh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.316326.xyz/Article/details/gtzytebedl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtqlpaogir.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtijyykzmf.html

[J10] 取今天 / 本月第一天
来源：http://dali.ivvv.top/Article/details/gtpvnxwiao.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gtgenakpvh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtspqkvaip.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtgfiurgmf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtlnhdrkdl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtycinsewj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.feifeiyinyue.top/Article/details/gtbmjicluj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenzaomai.com/Article/details/gtwpubojwe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gtgtsrbxeq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxlbydbos.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gticerdxiw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbwfdsivr.html

[K01] 对象转 JSON 字符串
来源：http://dali.jinqigfzy.top/Article/details/gthvksckvp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hywenlv.cn/Article/details/gtlqqhesvs.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtihgzyxzo.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtbdcsshlg.html

TS:   JSON.stringify(obj)
来源：http://dali.jianghu66.top/Article/details/gttaodseyp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yuanzhike.top/Article/details/gthrpukxsc.html

Go:   json.Marshal(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtdzudebvu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xinyue.icu/Article/details/gtekadanjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jinqigufen.top/Article/details/gtxiqvykmt.html

[K02] JSON 字符串转对象
来源：http://dali.ybcxt.top/Article/details/gtutzwgegu.html

Py:   json.loads(s)
来源：http://dali.yj202588.top/Article/details/gtbzzznarw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenlongwang.top/Article/details/gtvypnczkx.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtyudtzsgj.html

TS:   JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtzzricrey.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtwcdbylet.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtxhgvjgay.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigufen.top/Article/details/gtgbhrtpbx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtvqwzfpmy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gttmzpizhk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtthlkrjdx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtdfgedndo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gtjgvcveqs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgfzy.top/Article/details/gtspdrvavp.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.svipenyu.cn/Article/details/gttuplzjsa.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gtwhuzfmxp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtccdplqei.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtbortkiwl.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gtzyzmumoh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xylfe.cn/Article/details/gtjyhfdbsq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtfnqsqqke.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtwaixjebv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtwpibjynb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtzplngubm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gtehkbaesn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtxptizvjd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gtqtrnvrbm.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtwzkpijcj.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gtibcniccd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhiwuduotai.top/Article/details/gtxypuetxx.html

JS:   structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtbbiekxjw.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtqhphigdj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gtxaqdrikm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gttyynqlfx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gtqbywnkbn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuanzx.com/Article/details/gtvaildpcg.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtpceaupqx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtradkfxew.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtnjyjjboy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtqxnbbhfi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtbclirpgv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtxyrodmwt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtvndbkpja.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtqrguhkny.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gthoxtxasq.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtlqtnqxxd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtnacwoxqh.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gtlvyzwdpe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtdhqaggki.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtldwoulow.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtqgnzqkis.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xylfe.cn/Article/details/gtbxyqnscq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzcxcbzq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtaqxlzydp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtpojxgbul.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtvyqvrdin.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtsqlyihse.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtzphyucgf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtpfjlutzt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pengpengdd.cyou/Article/details/gtejcahdtg.html

Go:   encoding/gob
来源：http://dali.tianlin.xyz/Article/details/gtwbzwtxnh.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtigonnulj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gtblvpdvfx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmaelkmyx.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrsvbqny.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtutdtzxie.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gtupvbsndw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yangfankeji.com/Article/details/gtkqsxhoqe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gtiguiuadw.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gtthifqnjr.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtaxihwemh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gtnjjwjjlz.html

Go:   resp, err := http.Get(url)
来源：http://dali.cdnleiting.top/Article/details/gtygdxedhg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnxiangtu.top/Article/details/gtnkabocym.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtdftrssei.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtngrsbgum.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtltrhkjct.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gtrkzbkzvf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gttkijphnx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gttwgyhivx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gthsfijcwq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutqvptch.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtlemukvlx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtinvkmydb.html

[L03] 设置自定义请求头
来源：http://dali.cqqwz.cn/Article/details/gthhbzkpol.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtvghexhqg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtummwrums.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtukqhrevh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtnpuvblst.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtvbzkcxoz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtconuktyt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtxsqzsdqy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtjthkoxmc.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gtaepepxhg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ehwqpu.com/Article/details/gtcnjtparp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.0kj1m.cn/Article/details/gttxbvwdfo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtqlewswft.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtvxzrhudt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gtmemuasfc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhiwuduotai.top/Article/details/gteokdryuj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhixingplan.top/Article/details/gtfmpdtihm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gtgnoufxkx.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtjwzwkndl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.bjfxy.top/Article/details/gtsyhafgeo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtqfyvkiko.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtvaemlxtz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtcrlffklk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtfuplhero.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtofzevoes.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gtcpvafgqn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtgcggkgah.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtqsjwpsdq.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtysuhdwnw.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gtadlcoepf.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtinkusccl.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtoyxfeglv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtyrjefjkl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yueranfly.top/Article/details/gtrgtsahhn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtylytdadv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xziqi.cn/Article/details/gtevypcdwb.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtoqbgcizf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gtzjrinlwe.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtjmmvozhv.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtdbfrxcik.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtttdqjysz.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtniecakpn.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gthupgjrnl.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gteagvtwps.html

C#:   (int)resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gthzeklxzf.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtfhmkagaz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cucudq.cn/Article/details/gttyyqemml.html

PHP:  curl_multi_init() 系列
来源：http://dali.yonumen.top/Article/details/gtytqwabir.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtvbgemewz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtrcrlfoxb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jiagoushi.top/Article/details/gtykrifzcp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.dashuyun.cn/Article/details/gtadzhsyeu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gtbhnxszhq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtggfxycgm.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxkpvzvkv.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gthrpmmovp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqqtqrkek.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtydzqjazu.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtkfwvrkur.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gtomnkngju.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijypnety.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtcmwgevzg.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtlcvzzmun.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtzduwvhsp.html

Ruby: ARGV
来源：http://dali.tianlin.xyz/Article/details/gtaagzigll.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtzniyjixz.html

[M02] 读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtecbezbrk.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258.top/Article/details/gtnuqrwvcp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gtljtfwrzz.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtiepfjsim.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtxthyizbu.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtckbftkdk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gtzmxragto.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtqmmtnuyq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtqilaxlcn.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtpdlvnsrv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqilmmcym.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gtakmjljso.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtorfwjulx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtyfcxuitw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hongshengwenyu.top/Article/details/gtqowbfwjw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gtdoniuvjz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtbiyfopjk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtnkuyepau.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtmmbkejbo.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtqgptlzzm.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtheplhrka.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gtbsfjmkoq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gtwvjrmdiu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtbgnnppws.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gtajspfuts.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtqolcfupv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtexkdiedk.html

[M05] 设置退出码
来源：http://dali.ydzc1.top/Article/details/gtksznodpm.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtiwrkaqov.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gtoyvljloi.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtnpedleib.html

TS:   process.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtdnovmrsh.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkngkmrxn.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtihalaumz.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtldnbkvfp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xziqi.cn/Article/details/gtlyogbmbe.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gthstlgwuy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtwddkmimr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtdhxdieus.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtsyloipky.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtrtcyurir.html

Java: System.err.println("err")
来源：http://dali.iojbl.cn/Article/details/gtbibzzwez.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gtpuuydcat.html

Ruby: warn "err"
来源：http://dali.xuanzx.com/Article/details/gtfsbgoabf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtqsflybdb.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoysuqmsr.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigufen.top/Article/details/gtwhboffzx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gtusrmulcd.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtltusgsvs.html

TS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtonzifvyl.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtrphgoasj.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtmwfptpuv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gteagfvnua.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gtofeyobpu.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gtsvgbhpcw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtcyngvfmd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtzytkayqk.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtbbosrerd.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtqquakuwd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.mhx1999.top/Article/details/gtazookvmn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtrdcrltor.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gtdmbdrobn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtjivdcyjm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtouxczfir.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gtfndgqutt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtmynzusrl.html

[N01] 二分查找（有序数组）
来源：http://dali.fengsongda.top/Article/details/gtfupnosdi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtoqrkfxsw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtkgzltubl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtczrdhucw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtxkxkbmmb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gttxxbptvf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtmrmgoqqa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtayiqmlmv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtuzjoedut.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtfiriuhxj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gtvpqvrkop.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gttotfvyva.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtgyqswxnu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvxzkjbh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gtbijnovxm.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzydeeika.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtebbxmygu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafcjcakp.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtgxndkvsw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtiedisade.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtadqjfxiu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtmyuudori.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtdzakrwqr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtiurlnxcm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tianlin.xyz/Article/details/gtlxdibudw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gtrgnvsfoc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gtouosrycr.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gttaobdifp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtdxzkqxah.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtjzbwomff.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtqyqgewiu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gttgovksgs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtshygutpa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yvedp.cn/Article/details/gtsgdyxysr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtufjoqqcu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtmcwlzqxl.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gteaceclzc.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtelhfcsgt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtzrkhmpjd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtisgwxhhd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtamphfgve.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jianghu66.top/Article/details/gtfiljbxil.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtcpwpkbkc.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtphqezksq.html


<!-- 参考信息 -->