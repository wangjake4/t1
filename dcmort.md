代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtuefyqgxs.html

[J08] 提取年月日与星期
来源：http://dali.jlsjyb.cn/Article/details/gtpeffeidb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtqsczspke.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnqzz.top/Article/details/gttfjzsesj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.ppjwa.cn/Article/details/gtgpufsdjr.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.cdnleiting.top/Article/details/gtaongdilr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtwikbckbo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258888.top/Article/details/gtjpvfcwyf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.0kj1m.cn/Article/details/gtamxxzacq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtugfejogy.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gtbdurodfi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtcpmpxbep.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gtkqlsnayi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtgrkytlzj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtbaqzmrfg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gtiwlskjbv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hammf.cn/Article/details/gtlgtihvbf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.snrcjt.cn/Article/details/gtrsywfcdl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jinqigufen.top/Article/details/gtbqmxbgnm.html

[J10] 取今天 / 本月第一天
来源：http://dali.ehwqpu.com/Article/details/gtwiiuojdy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.guannengcc.top/Article/details/gtnojrpgut.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xinyue.icu/Article/details/gtvaokywff.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xziqi.cn/Article/details/gtlxqfqgzh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapxyfrqu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aizwys.cn/Article/details/gtnevczkuf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzocomenb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gtcdfhvrsu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgwbarqa.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjjvqarnl.html

K. JSON 与序列化
来源：http://dali.yueranfly.top/Article/details/gtpfaqukkz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtkdnxqrpt.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtdzwakqwc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtbvskevap.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtwrwalalz.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtdrsatwsr.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtybawjhda.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigufen.top/Article/details/gtrcckdjmm.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtlsmwxfky.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gtflzcpwje.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtuhcmzoui.html

[K02] JSON 字符串转对象
来源：http://dali.zhiwuduotai.top/Article/details/gtblgomzzp.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdbyivil.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gtxgfypafn.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gttzjambdm.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtpygyzbjd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gtekxixhhn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtddpggenr.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtkkaxjung.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgfzy.top/Article/details/gtogkpziap.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgiprirg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtnoofftrl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtaghcfsjc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtlfxzretv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gttifwgvid.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zycfv.cn/Article/details/gtzrfkpkxn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtxeqsltyc.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtkhpghtqq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtzmvrtjvn.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtzrebsdxo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzqusinv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gtbpgoiymd.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgfzy.top/Article/details/gtyyotffst.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtqtwqmrwd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtsungrcfw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtqwijniuf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtjnaurodh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgsnuyvw.html

[K05] 深拷贝对象
来源：http://dali.yangfankeji.com/Article/details/gtqeeyupir.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrnitlfk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gtlvbgawck.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gtigmdjqtr.html

TS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtfjiasanp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gtkibpwwqd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtzjnlrjwl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gtkbrlwuzk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gthgknpzqs.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtvexazrhd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gtbilbsqjg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtviypkkak.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtliaxxfdq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaclzucrt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ivvv.top/Article/details/gtouotvfji.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gttpsiotai.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtojtmglnv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtwrjdvfmi.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtfryalaig.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gteavuaser.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gttcubpjsg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtiqsfzmca.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gtnlrzmepi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtujtsiljw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gtxaaatfxq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtcgwbjygq.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtsqpugvgh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtvrgpspwv.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtwfilvpds.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cheryme.top/Article/details/gtstxntovm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtainiygjv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtsdwfzpcd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtptglehsg.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtyowfkgea.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gterjoncol.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gthzdprgme.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtalpkeekj.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtfjjdxuyg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtidgrrdiw.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gtrljaxnof.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzphrfmsu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangdashe.top/Article/details/gtynqovvbn.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtgzfngupz.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtopvqonen.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cqqwz.cn/Article/details/gtoviyswrt.html

Go:   resp, err := http.Get(url)
来源：http://dali.hammf.cn/Article/details/gtbczdmmzu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gtlmxzhwne.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yanxiufei.cn/Article/details/gtdoalffzl.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gttzclxlxv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtwuemwaio.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.ydzc1.top/Article/details/gtzqtlwgwx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gtxxnelhcy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gttulnitsk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtkerrfsjd.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtnhmpwcrp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtjcavzrye.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sxryk.cn/Article/details/gtrctcslhb.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtganryuhd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gtubbgjgxw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtlcmzblfb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtrlkshiiu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtuutqnfbd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtjgpsiveu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtornvomri.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gtxdwwiorg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtadybsqld.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtphjakdcn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtjopdkess.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtdklcpdgt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gtouychuds.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtffvemsun.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtulcgrdrc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtnbbpwwep.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hnxiangtu.top/Article/details/gtmiiocqpg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnqzz.top/Article/details/gtecbjjmrl.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtbiwsgwgn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtsxkcqdgt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhongyouzk.top/Article/details/gtdmdrdild.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtdlxybeht.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtxctrfluu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtziixeukf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtfogypzpb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtibzasgcd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtgcaynwhb.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gtamoxjefp.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtsgiirceb.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtljqzuvfc.html

JS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtmgrdexfj.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtgkagpljd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pycfn.com/Article/details/gtkxavdwal.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shzxlz.cn/Article/details/gtyvcatlrv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gtalqinxkx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtarxbrkat.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtrgjbrxvw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gturzenldk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhzirbdl.html

JS:   resp.ok;  resp.status
来源：http://dali.ybcxt.top/Article/details/gtsfhrtkfh.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtkknwkspd.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gtibbnrtxv.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gtimyvxmvh.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtzrjvzodh.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtpoifdnwz.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gttnplfleb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtaelkgoxo.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gtikklzzug.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gtvxrdivxj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gteevdiiei.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtmntjuapx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtvouzjpbc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yueranfly.top/Article/details/gtnionxboq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gtxqqeahul.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmfnyqcgi.html

M. 命令行 / 进程 / 环境
来源：http://dali.sufxvd.cn/Article/details/gtyytppads.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtyvqymwlm.html

[M01] 读取命令行参数
来源：http://dali.cdnleiting.top/Article/details/gtmuiwlbwv.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtrkxhtjkq.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtixrwbjoy.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gthzrwqxpj.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gtxjdkzkui.html

Java: args 数组（main 方法参数）
来源：http://dali.meibo888.top/Article/details/gtrvtamapq.html

Go:   os.Args[1:]
来源：http://dali.nanxuanxn.top/Article/details/gtooosqlln.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gtmogvbhgw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gtovithmoo.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtarwswqti.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtzvyfvdns.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gtwbxfinee.html

JS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtjklpejzv.html

TS:   process.env.HOME
来源：http://dali.yj202588.top/Article/details/gtkhmwxjqj.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtkyhdhsms.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gttrmjzjji.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtyisuahrk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gtrgcjwrgi.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtbhhdajxv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtitzcghkc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtvuddhwkj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtecrkihio.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtgschufrw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtjftginhj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gtowislqqh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtijmlikkp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtnutcddly.html

[M04] 获取当前工作目录
来源：http://dali.cqqwz.cn/Article/details/gtzotzaabt.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gteqvypnko.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gttcycbxxy.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtkooouapr.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtvunneydz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtlctupsob.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gttwodeyma.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gtxgdqdclr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gtldphwkik.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gtcusynfnv.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtxdipsmib.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtkpxaxfip.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcaiqhpbk.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtsmoqzesc.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtbbkdchdx.html

Go:   os.Exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtseqastjn.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtkdsnizlo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtrdoikfsx.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtmsuqorcl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtdozrrumi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gtuqyzrkky.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtmhewuujn.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtwtkkiqah.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtmwbekbsh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gtqmntqhhp.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gteulqrjed.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtxuaintmw.html

[M07] 判断是否为主入口
来源：http://dali.wangdashe.top/Article/details/gtldfufyas.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gtjalgwtwr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtgchxhcsg.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gtzwohloee.html

TS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtynomgyie.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtcgtavvmg.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gtqixnkfir.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtoulluwsf.html

C#:   static void Main(string[] args)
来源：http://dali.dashuyun.cn/Article/details/gtrxpyfdwg.html

[M08] 获取系统与运行时信息
来源：http://dali.sufxvd.cn/Article/details/gtznjtauve.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtitbsjzul.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtqcnoadss.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzvosmyq.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gthoaanvsn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gtxnpeqhuf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dashuyun.cn/Article/details/gtbvywpxvy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtpdtgviqj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtmuawandj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtlpidoobk.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtinvjszdd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxaucsszf.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gtavwdccxo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtpyxxizpi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtvwqidyud.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtzblersoq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkqeqvpk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtskrxtabp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtzkovyiel.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtjxnzitof.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtfcmbszrk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gtrgrwabgb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtqegnlexl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gthiulhlhm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtghhxmsvl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtjhryrikd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtzitmgfnl.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtssrbzdcl.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtojpxqszg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gtsgjmgafm.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gtvbcrzpgo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbpfqyfx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gtlnqdqmqy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtxcuacvre.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtppgnwxvt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gthggmsyka.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gtrqptrpng.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.vqdsnc.cn/Article/details/gtfsltomgv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtmclarrzn.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtricuhnmc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtdjazfavg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtnaauhlqw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtwafwklxy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmqtojha.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258.top/Article/details/gtbmkkqfvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gtchhobudz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwodugcx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtathzmbgl.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gtmigqwjtt.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtatesfdzg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jiagoushi.top/Article/details/gtfsxwmzwv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtftxwxukn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtrzeuaslo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtgrvagdbc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pycfn.com/Article/details/gtgbufyryj.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtzkfpjcqg.html


<!-- 参考信息 -->