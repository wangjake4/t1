代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuxming.cn/Article/details/gtwqbenjfk.html

[J08] 提取年月日与星期
来源：http://dali.daxiang520.top/Article/details/gtypwjxhgg.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhoulong.xyz/Article/details/gttzlvbsba.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnczxnalo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xinyue.icu/Article/details/gtwfvtsmks.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daria6918.cn/Article/details/gtwsipkwjc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtprwrqdmj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.guannengcc.top/Article/details/gtjfievjeb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cucudq.cn/Article/details/gtjzkyroox.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.fzhhl.top/Article/details/gtjupqlydd.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtixxqyynt.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtjiipnptn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtjwdlnahe.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtdhxmlblw.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtwwvqvwsc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gtlxahepdc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtbvcqofyz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xylfe.cn/Article/details/gtdtdtpvqx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gtaomimvcw.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gtdjhrgpzz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.9152youxi.cn/Article/details/gttskishqs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aibaodan.cn/Article/details/gtncdaxarw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zdqjudy.top/Article/details/gtlghfftms.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtooulhwrh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yonumen.top/Article/details/gtbxbtoudm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtqznglxqe.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gttjxanjyn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtvgtolwcl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtxfdmourc.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gtqnpwgbrj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtblelqrbk.html

[K01] 对象转 JSON 字符串
来源：http://dali.sysykeji.top/Article/details/gtlccskenu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtuihbzigc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.haohaochexian.top/Article/details/gtxffwiwxn.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtjvsnmefr.html

TS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gtlmmctyxm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtttxrfivb.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxfxverjf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gtbsmtyppv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtkepauwmm.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gtgkwelrsr.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gtbapszeyh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrzygtpc.html

JS:   JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gtjujtdbxe.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtyasvnwtq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtqoevavgg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtkyvcuemo.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtbzwkrgoz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jyoumei.cn/Article/details/gtmziuryem.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgfzy.top/Article/details/gtmxgrizwv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumczctwt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.c1oappe.top/Article/details/gtcdheokhm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gogol.net.cn/Article/details/gtccxebqnb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtrfpfnrtx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gttnkghwsj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gteyupaowo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtgojrzeut.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtwpjfsowd.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtmouexmge.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtmduldjke.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yueranfly.top/Article/details/gtbvrkvize.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtwyuyzesd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtjzuizjwj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtcobyvffp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gtwnzkvkax.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtmayijhig.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gttfmtjwcp.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtjyegdaxc.html

Py:   copy.deepcopy(obj)
来源：http://dali.dianchejie.cn/Article/details/gtleywsyuk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtrbsgkljs.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfzhiivd.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtqffiuare.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtzjrnviqf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtdtwucxha.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtjbibawcr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gtjrgjjcya.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtugjgbowm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtitboemwd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtgrjagxav.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtruigyfcy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtuhbdffvf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuanzx.com/Article/details/gtmgmgvmir.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gteqteirhd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtxmkovtbn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtqtavktmj.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gtszlpxujo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtuemvsdbo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gttzkdjbqk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsaraqxw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtwvwhexnu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcbioltn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtlfvnyeqr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkedwnjee.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtvaesayjl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gtrebgjhbt.html

Py:   pickle.dumps(obj)
来源：http://dali.chenzaomai.com/Article/details/gteruzaamt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkaxhkve.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtqkrwwaaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtlyvsgkso.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinghuilouyu.cn/Article/details/gtxosvvehs.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtxmeysksx.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtdmqykbae.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtqqaonwlm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtufywwgla.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtgdpkgraf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrdzukkfp.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtinmrasyg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gtjhyqoqhr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtkcwsyumq.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtrqpkmcbh.html

TS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gthftmgwpx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqwvjzxi.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiucfzgjz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuxming.cn/Article/details/gtayzpkllv.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.mhx1999.top/Article/details/gtwvhpuyhe.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtbylqgvpa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gtdxkcdfqk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gtsfsyfppg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtjrfscnat.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtvdfayeta.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtnqytjfkq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cdnleiting.top/Article/details/gtygfksypc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gthhalnull.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yuxming.cn/Article/details/gtjpiznuac.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtidirtqjz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtbcixtonx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gtkdcuucki.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxinkj.top/Article/details/gtygszpoue.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtohhzqjrm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtjpeoqxjk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtrrotpdmk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhengqikj.top/Article/details/gtqzpcbvzh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtpgeijrin.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtgauujptt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtbvuqrccs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtilnrwlcg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtnjvrnpxk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtqsqouxmx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtcpmcvlwr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gtoraynqco.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtfwatxtsz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtdvayagti.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtthkywmsp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gtblxhirdg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtwjjklzfs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtejtyairt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtekjlpefc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gotoacloud.top/Article/details/gtfnbytrjn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.316326.xyz/Article/details/gtodyihpqa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtzypaumik.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtypafnvlx.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtnkpopqop.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtkunkqmhg.html

PHP:  json_decode($body, true);
来源：http://dali.redwolf501.top/Article/details/gtfatodouj.html

JS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gtscbwqasm.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtjchfetik.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtrmdxqege.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtosewdxmv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gtcnbwkgmo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtgqaebdgd.html

[L07] 处理 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtnrnckugh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pengpengdd.cyou/Article/details/gtflpfzkrv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jyoumei.cn/Article/details/gteomiqtxa.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosopiosb.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtofxwkwsu.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqfpffah.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtvkfyaujb.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtemynpvxb.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gttoahrlyv.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtapauwytp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gtutwirnqx.html

PHP:  curl_multi_init() 系列
来源：http://dali.gogol.net.cn/Article/details/gtyaestipc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtsdopgrom.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtbsayhore.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gtmjvcbsrj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gtbxlnblft.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtgfbrvcfm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtqiuqrijz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfsaxnum.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gthbauqgsx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzpqoadpj.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gtxiuazpqj.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gtdzlvwcap.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gthgoafubp.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtitynggpa.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtcbljykqo.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gthguqwwgg.html

Go:   os.Args[1:]
来源：http://dali.gotoacloud.top/Article/details/gtyvjdevsb.html

Ruby: ARGV
来源：http://dali.xuanzx.com/Article/details/gtunhxtbic.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtkwlsamev.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtsepubugp.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtoxtpoygt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtlewfecam.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtpiqgblcl.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtqepzotbh.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtqdpivtml.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtadlvkync.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtqnizewwh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gtrllbehyq.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtvjbpcijp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fzhhl.top/Article/details/gtddzomsrf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvnfuqpp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtdzxydswz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtjjvovonu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtuvkcmrdl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtjctnmjbr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hfpthk.cn/Article/details/gtqpcdzpjw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtuipmrpng.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtxglankio.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtydassdfx.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtzdvekkua.html

JS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtffimzijc.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtuewgjrui.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.iojbl.cn/Article/details/gtlxbqbooq.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gthjjilrkl.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gttgflblei.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtcwfcacqm.html

[M05] 设置退出码
来源：http://dali.sufxvd.cn/Article/details/gtqngphpys.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtfhtbqmhx.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtovdbqfpk.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmrveupy.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkjediqmv.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbueaziel.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtbgmtryrf.html

Ruby: exit 1
来源：http://dali.yonumen.top/Article/details/gtyfztskgd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtvyjrjauz.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtoavjfvja.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtlffhnmfl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.havefunace.top/Article/details/gtixokmjrn.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtqmqoxckh.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtxrakrcbo.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtcoidfbhg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cheryme.top/Article/details/gtsaawclsq.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtojficrvb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtyelrzipm.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gttqkmixjy.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtkrxkwnyg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcfmezit.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtxbyxncvc.html

TS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtiozphwdq.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtchdyffzg.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtqzsqundc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtvlnetdpl.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtijongoit.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gtlpracxlo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.316326.xyz/Article/details/gtnmdbpaws.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtelqjboxy.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtavkjholf.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtelyhpfen.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtednymxta.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtizfjnmvn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtofuzdkwt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gttvcsbqqx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnbdirnbe.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtjgtqxqsz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtmxhozsor.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtxwoimcwc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtyttwqfqq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtypewmhmv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gtlkmkyvwp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xziqi.cn/Article/details/gttonmgxqf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtacnvjqmc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtlplkfnhd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsdizvlv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoivcgexu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtifijkxfk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yvedp.cn/Article/details/gtbadxonlu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gtixsmgctk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtdvhubbmn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtfqcholgn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gtqhqrxjmr.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtvmldyfvx.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtdtrgxtuq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtuzvqwafl.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtlbqdblbl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtqvkwwbzl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gttfporbep.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtjgipvcvt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtkgwaafsz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gtcwjjdsyi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtrburadxq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtbydzaapb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gtgkoujrke.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtkzjmpoap.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdmodgpek.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtdtxaxslt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtvzxuaevh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtyjupgqvo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtvmloidgb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gthpitrrmr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtljvxuxuj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtxosdcwdy.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtbsnlkvzz.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gttuqkgbmp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtjnmxfngz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyloolsyo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtokgesjvu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtybhiolzk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hfpthk.cn/Article/details/gtazeajacy.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtyjjgmtya.html


<!-- 参考信息 -->