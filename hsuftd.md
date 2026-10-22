代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2vawpigbn.html

[J08] 提取年月日与星期
来源：http://dali.chenzaomai.com/Article/details/gt2bvzlfcis.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shzxlz.cn/Article/details/gt2bqnkfhev.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2qvmyyoyp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gt2jqujzfcs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pycfn.com/Article/details/gt2urjjsirh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gt2zkvqmybr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gt2uovnqlkh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.xuetiantiany.cn/Article/details/gt2xiagqeit.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.iojbl.cn/Article/details/gt2toijplkl.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gt2bngpbwdb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gt2hxhdfqpg.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.quarkkingdee.top/Article/details/gt2btnlmevf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gt2ppcgedre.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2nmuuaxaw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gt2btwdcgkd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.andypj.xyz/Article/details/gt2gluvwwmm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gt2dvpukypu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gt2frqfplsh.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2qghrtayx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yuanzhike.top/Article/details/gt2kyxyklcx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gt2ordhxbwx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.snrcjt.cn/Article/details/gt2qjxqkbdt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecpaonkk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnarceqc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2vdyeaveu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gt2djktwtuo.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gt2ewifptoe.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2serhqcoi.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2rsfklqud.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vxpmvbjj.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gt2nssgidut.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2nogkdsik.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2odmfjdzs.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2kgnbvupb.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gt2vcdnhmuc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2dgdkieqg.html

Go:   json.Marshal(obj)
来源：http://dali.aizwys.cn/Article/details/gt2cninkoun.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuanzx.com/Article/details/gt2rxgxlhxj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2vbvyokwa.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2hxjhxmbc.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2lumrxxzx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cdnleiting.top/Article/details/gt2atcsmfnl.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ufxgillf.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2vguwmedr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fengsongda.top/Article/details/gt2krbtwtsm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spfohuxv.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2istyokgi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gt2efcnnzsa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gt2aahlkyig.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2ekhmqtps.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2emwrhxlf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2fcdcsszw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2pmcjuske.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gt2etletjme.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gt2eqwtkfml.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sysykeji.top/Article/details/gt2wixrfzaj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dianchejie.cn/Article/details/gt2uqenbqwy.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2tvfxufne.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gt2vudkeyvb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cucudq.cn/Article/details/gt2nfaaoydo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gt2vfinqorp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gt2wojrjiuu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2iyxmroby.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2mqursqhb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2vcrebkih.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2edhqfsyp.html

[K05] 深拷贝对象
来源：http://dali.andypj.xyz/Article/details/gt2reeupolf.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2rwjuxwwc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gt2xstteput.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2yfrxvego.html

TS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2mqsakywi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ccshayos.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gt2sgbdrbpc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zdqjudy.top/Article/details/gt2zldruobt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gt2woiegdpb.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gt2kaezrlzr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cdnleiting.top/Article/details/gt2jsetxbry.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.quarkkingdee.top/Article/details/gt2odlpywwd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aibaodan.cn/Article/details/gt2gdgcrfoh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2rcgbzywf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2adxwabci.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xukgruyb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjckqqce.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2skhsqlzp.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bqbslqhj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2ztnykfix.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gt2hpfupbea.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2lobjpyri.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gt2goyizqyd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2cjyndtbt.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yongpay.top/Article/details/gt2egkeypce.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2shkmyhem.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2qkeojssd.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2xmhfhkvd.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2eyiouoyx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzdsoqxc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2xhhewjle.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2bhpgindw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hnqzz.top/Article/details/gt2xenwqbhp.html

Go:   encoding/gob
来源：http://dali.yvedp.cn/Article/details/gt2zxgiukfp.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2hylcodhf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2fcplbanq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2frrjztaq.html

L. 网络请求
来源：http://dali.cheryme.top/Article/details/gt2bewpdlmn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2wgkwsiei.html

[L01] 发送 GET 请求
来源：http://dali.aibaodan.cn/Article/details/gt2zxdzrivz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2vlzozwbh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gt2deozuhue.html

JS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gt2nlplllwi.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2spsburpf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gt2odxmgviq.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangdashe.top/Article/details/gt2aqvrrbrs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gt2taotutcw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenzaomai.com/Article/details/gt2ovebarws.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2deyutjin.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2rumppoba.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258.top/Article/details/gt2iytuvyzw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2xbpinndu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2pvwdghbm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gt2tknagffv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gt2wllazcqs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2dsanuiwx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gt2sjhkvlbv.html

[L03] 设置自定义请求头
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnjtxzwc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gt2xhyjdvdz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2yfkrbtqo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xylfe.cn/Article/details/gt2iopfkyvd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2izbvzspz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2gfjiqrlf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2dwgdzifm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gt2htqirtrx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2cvdqwqqu.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2vuvzvtfj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gt2vhgjuaud.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.mhx1999.top/Article/details/gt2lxmjzvde.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2ipdliira.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gt2fxhpmxzo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gt2ltdgedmy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnxmldmb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2oifnyrsc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cydvtgrk.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gt2hbrdqxlr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gt2qizbopnn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2rlspsazw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2byxjmrbd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2ogweoasu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paioacia.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gt2bsngdhcx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gt2qtcmrwib.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2hvkygqly.html

[L06] 解析响应为 JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmwiaxou.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2jhtrlitm.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2qxjafwsj.html

JS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkvkelnw.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2ccmljodk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuxming.cn/Article/details/gt2xjyhodfp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.daria6918.cn/Article/details/gt2yzlurrau.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2hwamevmr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gt2bdoqoekd.html

[L07] 处理 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gt2delevfxa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2zguqetad.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdrnapak.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2fjnqcjar.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqasnlel.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gt2govugjve.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2sjhityuj.html

Ruby: resp.code.to_i
来源：http://dali.redwolf501.top/Article/details/gt2wkexandc.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gt2cvymrlog.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gt2fijhzopi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shuidangran.top/Article/details/gt2zpvgnqlt.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gt2hfsijiou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2gcxqhyth.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2hzdgxpui.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gt2cguwmaet.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gt2ykandnqj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gt2funabfiy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2faztpnhw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2dsotqmfz.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gt2sheedufp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2wifishfe.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gt2ozhlggmc.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2tyuovnct.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gt2yvhndjpu.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gt2pgdxzwxi.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2ocuknrcs.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2uawjisca.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gt2ouwmshlo.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2cwgiewtd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gt2jlffybtn.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gt2aiinyzpg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cekxhgpb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2cdapkyrz.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2ndnarisz.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2wdzylyuu.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2wlvcxdpy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2jisxwnas.html

Ruby: ENV["HOME"]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyscgcjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2pwgwjlbc.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2ajibinqj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2dlgegmwb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gt2avdhkmtz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2qqgtrqzl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2anbwfmty.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nxqscwdw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2uhbqcqvv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gt2jdkqojfv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2mggbuhvd.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gt2ycxlldmb.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gt2korevwnx.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybdajyws.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2hbhjltav.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2nfgxrayb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gt2xcriborf.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2jxymptnz.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2uiimvyuv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gt2ltleftpc.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gt2felqihyo.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2otjubaix.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gt2bpvkgsfz.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ldyqvviu.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2rqlkttrt.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2tolwlrry.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2jmwbkfqo.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gt2gbhrgqbs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnbzkzgi.html

[M06] 向标准错误输出
来源：http://dali.cheryme.top/Article/details/gt2kcmdtvpc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gt2ywsxsjtt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sxryk.cn/Article/details/gt2xnjzvzch.html

JS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2holmhcha.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evrgexcs.html

Java: System.err.println("err")
来源：http://dali.jinqigufen.top/Article/details/gt2hoxycvep.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gt2plptfpcd.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gt2hemabplx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gt2gusifcqc.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2qbpklvey.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gt2ijrvoumz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gt2vrubgacy.html

JS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2qzjksvhf.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2msjkebay.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2mpjcdfrj.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2epmvifsu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gt2ptynyaon.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2zppjseob.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2itazbbnm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pytqspux.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2amotiqvn.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2kdrxmmff.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2dawscsok.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zdqjudy.top/Article/details/gt2yxiffpjx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gt2myxqgtvz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gt2ohsyvedx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gt2qqacbxjv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2lunnfpqg.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbyenhpm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2pfuxydyv.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gt2tmivmfhp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2qosijbvj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2uqvvcjzg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2kbkihjpz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2uwuasvox.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2dbbworjk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2jstpqtub.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gt2wtyjcpsz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2gdhdcced.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gt2auwrjqhb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hykroohj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gt2miscoxvh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2tgrpuxrb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2fqnomxia.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gt2wmfeywej.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2srjgfwus.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2izommomr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2phsujkad.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwrxzosd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cqqwz.cn/Article/details/gt2cswiqhdy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.pengpengdd.cyou/Article/details/gt2abwnnqyb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2itzkdavm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2scegfmrl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drfapsae.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gt2hxclmhgj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gt2xaenyixy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fengsongda.top/Article/details/gt2sxlaxczk.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gt2aemfnnpn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2ylgmhudl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2dimzmkmx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2btfxkknv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2adblrjcf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2temriouy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2fwireoan.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2suynlrih.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrpdaew.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvvgwqps.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2jmjreobq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zgomgglj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2jxftpqca.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2wlqebvhb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gt2qwqwxbhx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gt2koyowrih.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gt2ytpytapb.html


<!-- 参考信息 -->