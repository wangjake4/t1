代发 wailian999

[J07] 比较两个日期
来源：http://dali.cqqwz.cn/Article/details/gtocqohvui.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtvlpajilp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtqgrtyvrg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtqcokjlfa.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydjznnqi.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtatuwldgn.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ivvv.top/Article/details/gtkhrazveq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuqsogko.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkykmcnu.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtciwztslb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gtnpaubeyo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhongyouzk.top/Article/details/gtqfcrjqht.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtbsaaozce.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwmawhtf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtqdxdxgtm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytpgpgkk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.feifeiyinyue.top/Article/details/gtybyjumcu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtpveijape.html

[J09] 时区处理
来源：http://dali.dianchejie.cn/Article/details/gtfiijkqeu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigfzy.top/Article/details/gtpwrthxji.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gtiadwunpb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jlsjyb.cn/Article/details/gtctrugzdo.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtlatdnkeb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nwbrower.top/Article/details/gtvopopyyv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sufxvd.cn/Article/details/gtknhznism.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gtwvevzvnj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gtnypxqpox.html

[J10] 取今天 / 本月第一天
来源：http://dali.gaohongyu789.top/Article/details/gtqoqbjdhe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtdvzomvhe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258888.top/Article/details/gtjporhnyt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gttoyykmlr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtwbfwvfij.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tanke756.top/Article/details/gtxircsoft.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yvedp.cn/Article/details/gtpkmabfmk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtnncsuejx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xziqi.cn/Article/details/gtzyiwlpbe.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlwzenwff.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtjaqjjsbr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzjylxiod.html

[K01] 对象转 JSON 字符串
来源：http://dali.pycfn.com/Article/details/gtwthbbqpc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtfayuybmt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gtmilsgvry.html

JS:   JSON.stringify(obj)
来源：http://dali.yuxming.cn/Article/details/gtdemamhfw.html

TS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtwhbxjdqt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtuezhpvnf.html

Go:   json.Marshal(obj)
来源：http://dali.gotoacloud.top/Article/details/gtyzxmmiqh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.nanxinkj.top/Article/details/gtwnootmgq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtymewfjit.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtwlpzooev.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtuxpcjxjp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelespahx.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtzxjfsbwi.html

TS:   JSON.parse(s)
来源：http://dali.sufxvd.cn/Article/details/gtzqbekrhc.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtrglfqcvt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jqgufenzy.top/Article/details/gtpozznjab.html

Ruby: JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtuxrbydkm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtkivbnqvv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtcjxebrzk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxnlbyvh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtvzegdxpp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtoeywlgia.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gthmcybqdo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258.top/Article/details/gtymseiuxl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtcxwydhvj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtbdocuzfv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpidaqre.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvcbddme.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtqsnsbxbz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hfpthk.cn/Article/details/gtaixkgofq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtpazdxzas.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.havefunace.top/Article/details/gteiukyxeb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtviabuznh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtmanovepe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnwyztfj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtioikljgu.html

[K05] 深拷贝对象
来源：http://dali.zdqjudy.top/Article/details/gtxnwuudjo.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenzaomai.com/Article/details/gtkvnxclfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtccnqxqaq.html

JS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvawswfh.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtipndwgcz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gtbyxsrmhn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cucudq.cn/Article/details/gtmbnxbkiq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gthglcftjw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jlsjyb.cn/Article/details/gtcruhvrve.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtddeaplcv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gttdpgrjjh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhiwuduotai.top/Article/details/gtydukaore.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gtnyeogtub.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtntkanjxi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtkyluwlju.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtfhzbqadd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtbsblmwhf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtfbjynale.html

[K07] 进制转换
来源：http://dali.cqqwz.cn/Article/details/gtydxcsaej.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtqzzpghbq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zycfv.cn/Article/details/gtckmhwbej.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtzolhyjgu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtbdlxoyhg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gttcccuzoj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nanxinkj.top/Article/details/gtdmxxmxei.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenzaomai.com/Article/details/gtmyfbjybb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtmcazfuyy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtkknuxixn.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtpejuvtqv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtcyjqiyci.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gtwnqfmymc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtjwsfmihp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtzmmlohxm.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gtlbvyyqba.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gtanbtnzod.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtdyyznipc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnonumzns.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtkqdvnpcn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtghklvqyt.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtpwfktuwo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtvajtscxx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xinyue.icu/Article/details/gtltvymwju.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtlpnpjbzh.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gtqaikqxoq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gtxajgotwe.html

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gtvdowxufg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gthcvxqddp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtmxrshffh.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtvashcgif.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gteyqqwgqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gtzyuvgffe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtjvsjrlwx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtczbnwjjj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtukvfbigd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtiuwruefq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenzaomai.com/Article/details/gtsmqtlxbk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gtmaekgnoh.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtqmsowtwq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guowangkeji.top/Article/details/gtpwppuymo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnaooktd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gtezbxutae.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hywenlv.cn/Article/details/gtcejepijs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtigbbnmlv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gtwofzzrlt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtajwucltl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtfxhghnnr.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtybahbbmi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gtpngupfle.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gtjzukjbzf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtcgfgygne.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtexjmrrqs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtusglyqif.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.c1oappe.top/Article/details/gttqlisrac.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrgqqgyo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtrwbszgnt.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtaxfpnmie.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gtkaettajc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtvczbuios.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwwwtufw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiqdlokay.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangtech.top/Article/details/gtfchtmtke.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigfzy.top/Article/details/gtjedjzozn.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.0kj1m.cn/Article/details/gtslzvhpkz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtkmdwaqxb.html

[L06] 解析响应为 JSON
来源：http://dali.tanke756.top/Article/details/gtazcpbyxj.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtildutejz.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gtqnhjjhbx.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtvfwkbato.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gtkckmysut.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtlcjaghmp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gtaiddrvjg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gtenngzpcd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtrbnixqgz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtmllxpwmt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yangfankeji.com/Article/details/gtumupruze.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtjlbfktdy.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtpnqcfqih.html

TS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gthxezzubz.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtbyervaoa.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtjfrkcrvg.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtevcfhkiu.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtqcclgwae.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gtvrwtmzoc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtmkxiteqi.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtflvwrlez.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtalxujdjx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtzxxcbaxq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fengsongda.top/Article/details/gtigkgsmcg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofisdhrw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtdseomdcn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtkhocsdnj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtoptqyzin.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gtchgfyfbc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtoeyqlted.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtqghdsdpr.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gtrowrciar.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxklrzmy.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtvjtvmdsz.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtbhyjhdco.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtsgrmyieo.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gttkiszult.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtkfkbkagn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gtzeflwevi.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtfdpzwhlc.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtecswrnfc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtjkjjauro.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gttmilpiqb.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtwdvtgonf.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtvfhplmpq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtwqnsysnb.html

Ruby: ENV["HOME"]
来源：http://dali.zdqjudy.top/Article/details/gtjacnbcbb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtegafizzk.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtvifglopm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hfpthk.cn/Article/details/gttsqgjdpa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtmmguydkk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtcxquqxbr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtmkbebruo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guowangkeji.top/Article/details/gttxyyoouu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtbuneodkx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtaeqovlpl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtrmnqostw.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtgznoylbg.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gtxxpnnvqn.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtaukkxkos.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtgblqvrht.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtvjlkevjc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtuiafcpdj.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtxdumwqrp.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtwsihiwxu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gtatnlpzhr.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtvrvphdan.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtiwlrgslw.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtflssxexx.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtwkhaenbm.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtenlkbdxm.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtdxhjccrc.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gtbnerzknm.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtxjvmwyaq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gtahrsydak.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtxuvrmhyo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtnqcktxvl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtjgnnrgtg.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtnkrfpuub.html

TS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtbxuvkbxi.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtzdnldtno.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtkwruvpye.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtrqpkphdy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtmrktbbph.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtisuragvi.html

Py:   if __name__ == "__main__":
来源：http://dali.andypj.xyz/Article/details/gtcvyspyvh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtsvjvlqym.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtcultsoup.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtvprifevh.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtaaoiyjie.html

Go:   func main()
来源：http://dali.bjfxy.top/Article/details/gtotdkqamh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtifpnkojq.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtbpynchio.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gtkcimmhyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gtvqrowuvf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhongyouzk.top/Article/details/gtjbntqkgc.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtgahmxoot.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtfcnjcxmf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtvorlroqq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtxajgpwoo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gtoctzmxue.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gtmbcuwsun.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtmhoruzvv.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfsljtvh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzxjmcjlw.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnizjktxp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtfnymncgf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtppqxuhza.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpozvfjta.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtyucmgeok.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtzbdqbtcy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtmuazqdtj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtfhdpezwq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gttqxjufqr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yangfankeji.com/Article/details/gtiuxsbcfj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtjnmfwvke.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtpwzujdzq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtgvvehpwv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtlwpuwfwf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtohmyfjeo.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gtsjlqooyq.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtejwkksjj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gtclpvbaft.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtidukxvpw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtdilruxem.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtihtzodyi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtpxnkmlzk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtxhdctmee.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtwcefhilr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtifnglxcl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtybyxmcia.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtwukurndv.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gtucwrzmqy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdkuasxl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtklzuvsek.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtztatybms.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtjbcoeypi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtlnxiweif.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtoighywqh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnzbbogk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtoqprsqlc.html


<!-- 参考信息 -->