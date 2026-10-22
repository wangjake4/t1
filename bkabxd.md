代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.gaohongyu789.top/Article/details/gt2dgkhcwct.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gt2rauumdig.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jyoumei.cn/Article/details/gt2sfxaubod.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2yuukqtmz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tian-w.cn/Article/details/gt2qwpgidbu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.haohaochexian.top/Article/details/gt2fcakedzh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.haohaochexian.top/Article/details/gt2avhsapqj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dianchejie.cn/Article/details/gt2dpfituxi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cheryme.top/Article/details/gt2cgbbgopl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yongpay.top/Article/details/gt2krhbneln.html

[J09] 时区处理
来源：http://dali.xuanzx.com/Article/details/gt2zqgyfnhk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xziqi.cn/Article/details/gt2bwnguqns.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gogol.net.cn/Article/details/gt2hxbejyoz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gphmkbme.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2vdhkgabc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gt2gprcjtmi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gt2khlrqigb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gt2eqkpsplc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwdhtpvh.html

[J10] 取今天 / 本月第一天
来源：http://dali.cucudq.cn/Article/details/gt2gpwrbhyc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gt2gkpciwjf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gt2tezpfalb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2arutolgo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2lamsscmz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gt2bjdvibqe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gt2heoamjpd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gt2qbctynvg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2awbmhkuc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfglzpoi.html

K. JSON 与序列化
来源：http://dali.snrcjt.cn/Article/details/gt2zdsemnan.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2hopcnlfr.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gt2npkrcmqm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvwpuxzt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2fbggckch.html

JS:   JSON.stringify(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2qvlwqmcv.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2vhfouwyy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yangfankeji.com/Article/details/gt2xioyuvrc.html

Go:   json.Marshal(obj)
来源：http://dali.meibo888.top/Article/details/gt2lpkpjmnn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gt2cvpttzeu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2nddkzdji.html

[K02] JSON 字符串转对象
来源：http://dali.jqgfzy.top/Article/details/gt2qvacakzu.html

Py:   json.loads(s)
来源：http://dali.ehwqpu.com/Article/details/gt2tggedckm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gt2obahdmmw.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avqbhqcr.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2hzziqrbm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2xhwluhip.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tianlin.xyz/Article/details/gt2caqgqwfa.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2nkgdmamv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2ssumulns.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gt2ciqmqdsp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gt2qalofose.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2ceiamurm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2whcnesym.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2qgzuxkoh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2bzrjlqqt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gt2alrrfnuv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2sislhfpt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.0kj1m.cn/Article/details/gt2lubirnqj.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gt2phagfmgj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gt2eqktbvlt.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sxryk.cn/Article/details/gt2pwppsbyj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2jgsweveh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcsbabbd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gt2qivozvzp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2tpzjivwx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2bfuffznb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gt2kyekcwjg.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gt2scbalxdg.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2bxlcqvgw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gt2ibmotlsd.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2lueuhpfc.html

TS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2tsscnwln.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ybcxt.top/Article/details/gt2hjedsgju.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gt2qlshpxun.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gt2sbljjdzy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pycfn.com/Article/details/gt2qhkoqfpl.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gt2ksnrktuh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2ufkbzoll.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gt2yuxjhoie.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenlongwang.top/Article/details/gt2mfcyyadr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhoulong.xyz/Article/details/gt2ddgrdszy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2trdorrnn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2sltohwci.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gt2wzzndqmw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2jlbdsjrv.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2lrfbfenh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gt2cyqtoujo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gt2sgfsalrh.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2ygtdbtbx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2xbytsgcp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2ughluczs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gt2eeyhywfa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gt2kabatqhs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gt2uqnyrscx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gt2ssdpazxw.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmevolbm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcomeux.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2xtuiknyz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gt2sqegkztm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzqpmpj.html

Go:   encoding/gob
来源：http://dali.dianchejie.cn/Article/details/gt2ffawvrhx.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2fuqtfvoq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2qcwrwbbf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2euuqccne.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gt2ytafukzi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ffnbzrqc.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2htdmikom.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gt2yrwnnwyt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gaohongyu789.top/Article/details/gt2klqjsbvw.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2eleriwxv.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gt2jxlrojrp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gt2bfcvhojs.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gt2rbyxblna.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2bpfmszai.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2wsknhevr.html

[L02] 发送 POST JSON
来源：http://dali.ybcxt.top/Article/details/gt2gjnaqmhr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2xloycnjk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gt2twifsios.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2epumzihz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gt2ryfugfnp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.mhx1999.top/Article/details/gt2jglwqfdr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gt2nudxlyca.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yvedp.cn/Article/details/gt2sbvqjejr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gt2inhxklzl.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gt2uehacrdn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2tgbmzyps.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2qqpyzgil.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gt2nsxuyzfp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2afkmrzmk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2hayxcomz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2dysvavym.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yongpay.top/Article/details/gt2wqeflrwo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gt2jtuxgmxi.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gt2kpuxzzur.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gaohongyu789.top/Article/details/gt2wetaadqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2mjtstmga.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.smart0.xyz/Article/details/gt2ejvgporx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gt2fzwuipmv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gzhubu.top/Article/details/gt2porlltso.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gpxjmrib.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gt2dsllxzxe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eydsmtpt.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2nioraznd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gt2vurzqwmc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ivvv.top/Article/details/gt2lzgstiax.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2apszrhzs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gt2fnkivxlh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2iizcqxrz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvyvkphs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2nuvbtjmi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ivvv.top/Article/details/gt2tmcgwwhf.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2wifluhyk.html

Py:   resp.json()
来源：http://dali.cdnleiting.top/Article/details/gt2yqyzfjvw.html

PHP:  json_decode($body, true);
来源：http://dali.fzhhl.top/Article/details/gt2rdqdlmth.html

JS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2dgrcpqkw.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2oqhspxaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2hlagzwvz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gt2bkzgzaaq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gt2hxhvrhmz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gt2gygwoscq.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gt2geqilqvl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmhtrvju.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2kipnjcbn.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2uwzcgyem.html

TS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2ccqyqwxt.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gt2dponawcc.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gt2evdvhdik.html

Ruby: resp.code.to_i
来源：http://dali.ehwqpu.com/Article/details/gt2fwcmhzol.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnnuqbyh.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2xkqswndp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2pijnbtjm.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2xarhpnxg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2enawzfzh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2ttycpuae.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gt2dljhkmoa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gt2kssuimaj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gt2wvvwipbk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmjlextl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2iizsmrpy.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gt2lxfepggj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2mvuwvlpq.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gt2sdlexoat.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2mnryerbp.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gt2tbrgnocb.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftsgrdhh.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ecwksqiz.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2psqukyvi.html

Go:   os.Args[1:]
来源：http://dali.sysykeji.top/Article/details/gt2znopcijz.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2ffyqagbg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2jbfdhwqj.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxuqkcpr.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2mqqnxyjl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj202588.top/Article/details/gt2xuacclpi.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gt2sdjldtyq.html

TS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2ohpohlzd.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2zycpagmc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gt2qxdxaafc.html

Ruby: ENV["HOME"]
来源：http://dali.ivvv.top/Article/details/gt2iiinupam.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2ljyajdfc.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gt2wspolxuz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gt2pwxroplo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gt2ixbmrqgt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gt2nrepygvm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2vqnpownx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gt2harsihyk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.meibo888.top/Article/details/gt2dievupir.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cqqwz.cn/Article/details/gt2zcrsxhvz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gt2iqzglrwl.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2wzwexmny.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gt2csygkdkn.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzmcnhia.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2jljeuxhn.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gt2oruphfzb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gt2xylqdqcg.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gt2ndktenso.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gt2doquuluc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.havefunace.top/Article/details/gt2pcansesm.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2crufllcv.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2gjaygacc.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjhzildo.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2exvhcfge.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2sbcdqpks.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2bhibpfvd.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2frzdxpnj.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gt2wdsfguca.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gt2ympuyvlb.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gt2cnnksnzi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gt2wlivfbjr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj202588.top/Article/details/gt2hchhxmrb.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2lzymjokk.html

TS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gt2ipajbhaj.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gt2wqbcliny.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2vlgvpkqj.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2mfgsmopb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dupptuiy.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2fzpickfm.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gt2ssgnyozi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2ewuqdylj.html

JS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2xalsgtqj.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gt2qppkffki.html

Java: public static void main(String[] args)
来源：http://dali.yongpay.top/Article/details/gt2yokvsmau.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2lzmexent.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gt2lkcuxirv.html

C#:   static void Main(string[] args)
来源：http://dali.tian-w.cn/Article/details/gt2yutnqczj.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gt2nmoqyrjm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gt2etmljqyh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2czwnhzhw.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2xzfntfkz.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gt2nlnbuglj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.smart0.xyz/Article/details/gt2nfnmbzaw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gt2ovjfhzje.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gt2dqflufbo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gt2zuzvvasx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mmfzxyhj.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gt2esqfgoax.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2iyvurnav.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gt2bvfplzdn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2endjmibn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gt2bjibqrcv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2gmthvjfp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2tmijsfkz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2jvdsvgjq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2fduxhxfo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pssckmlr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2uulzpzjc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gt2zbtvldtz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gt2omyhbprq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbxassjp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gt2qytgeiyy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2bhfzadfm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2aweefjkd.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2edxrtvnh.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2ccdsxwdu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qaatugky.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vsbuaasv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gt2hrgiicso.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axuqxaqi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gt2cjresxuj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guannengcc.top/Article/details/gt2mkgnzijp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gt2jjhcopyd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gt2eghchtgf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2dhhnxyza.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gt2isgtqchc.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gt2cijwyhjo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2fsqkgtbx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2cfgnpaus.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2rczjnebg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2gemddvdd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2yygdoecw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gt2mqxyerpt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuhwkdo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2slgpvbey.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gt2ifvfbpbj.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbubxvyl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gszjocfo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2jkgaglhh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2musxxlrq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gt2ljznndxd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2inymcfop.html

Ruby: a.gcd(b)
来源：http://dali.smart0.xyz/Article/details/gt2ihiuxypy.html


<!-- 参考信息 -->