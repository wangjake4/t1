代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.quarkkingdee.top/Article/details/gtnxrmrcll.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jianghu66.top/Article/details/gtpqbjfinb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtlncqyrpm.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gttzvybiwx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gtxbntbgfj.html

[J08] 提取年月日与星期
来源：http://dali.redwolf501.top/Article/details/gtoibtfuta.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yj20258.top/Article/details/gtihpijbsd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.ydzc1.top/Article/details/gtkwraulkr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gtmlplyrvz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxmghogo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.pengpengdd.cyou/Article/details/gtlggmzspr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtmpmfawfd.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gtgemubuwb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekyrpzox.html

[J09] 时区处理
来源：http://dali.quarkkingdee.top/Article/details/gtvcqolmqs.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yj20258888.top/Article/details/gtgymwtcjm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yvedp.cn/Article/details/gtueltbqgx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtkopxgwxx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxinkj.top/Article/details/gtahsddgnf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sweek.top/Article/details/gtvzdibmye.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.iojbl.cn/Article/details/gtllzytxye.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.9152youxi.cn/Article/details/gttjiknmdw.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xuanzx.com/Article/details/gtmnhyrkax.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtubzcevma.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yanxiufei.cn/Article/details/gtrlnqyuhr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.havefunace.top/Article/details/gtrkxxkjyg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuxming.cn/Article/details/gtdrnxjwjh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpdwzidpa.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.nwbrower.top/Article/details/gtjywklvsu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtsvcqwrer.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tianlin.xyz/Article/details/gtsgswgbuu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjyfegvnd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwngsvjux.html

K. JSON 与序列化
来源：http://dali.xziqi.cn/Article/details/gtrpvxvhnu.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtlzbbwjri.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtuloypnqb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqevyzerr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtqybjfrof.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtesyzqzza.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtcvvovahf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtwihqiiav.html

Go:   json.Marshal(obj)
来源：http://dali.guowangkeji.top/Article/details/gtasyljrpz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnengjwxa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gtpqirnamp.html

[K02] JSON 字符串转对象
来源：http://dali.hnxiangtu.top/Article/details/gtijhuqcnb.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtwypiqdcx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aibaodan.cn/Article/details/gtqisjmvud.html

JS:   JSON.parse(s)
来源：http://dali.cdnleiting.top/Article/details/gtnkwecjjq.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtvambuakd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtrzwfpwiw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gttzdpumgq.html

Ruby: JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtwpbsxzjs.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtjgohaxgz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gtihprvjcm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtusdjgnla.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zycfv.cn/Article/details/gtyomiatsb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cucudq.cn/Article/details/gtiwnxidqy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yueranfly.top/Article/details/gtjxbhvtir.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsszmftan.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gtfjlfoinp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.havefunace.top/Article/details/gtbctxvsqo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtwhjfjxwo.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gtqgwyqdhg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtkoalyznu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jqgfzy.top/Article/details/gtkbiwacnc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gtsfcfdiuh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtwrivtjih.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtpuclaced.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gtfpuyiknx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fzhhl.top/Article/details/gtwgewzofv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.9152youxi.cn/Article/details/gttxzehjgp.html

[K05] 深拷贝对象
来源：http://dali.shuidangran.top/Article/details/gtmgygkeum.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gtjunfgiue.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtbusibnjo.html

JS:   structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtqnialilj.html

TS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtmkhfsxgq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenjidiqi.icu/Article/details/gtjdvsatfa.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.pengpengdd.cyou/Article/details/gtjrxsgxnd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shuidangran.top/Article/details/gtmffgxdoh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtroutqxrn.html

[K06] 解析 URL 查询串
来源：http://dali.zhongyouzk.top/Article/details/gtrdoyadpw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jianghu66.top/Article/details/gtgimkjppw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtbnqrnwbq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gtegdgyxjw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gtgnqgycxx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtnbnyzdmw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtiwtxxfyl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnpnibip.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtjmvxrvie.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtbhpckqts.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtninbochc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yanxiufei.cn/Article/details/gtrxjldicd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtxfkfzqpf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtdhofgnre.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtsinnbvpr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.quarkkingdee.top/Article/details/gtbixvrtdu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtbrmgnuyx.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtyruaeixc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtehgjugea.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtxbztyiwn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhaieshe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gtxzindjer.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtntsqywcz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtekrbwchw.html

Go:   encoding/gob
来源：http://dali.sweek.top/Article/details/gtejxnxbks.html

Ruby: Marshal.dump(obj)
来源：http://dali.dashuyun.cn/Article/details/gtsvuzbhum.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwamgezl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtawnalpip.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtpmolymtm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtsinzimps.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gtfqnxyrzl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtwjgmokew.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gtngbhpged.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gthmfunpgp.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtbtepuulo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtaoaqiazw.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gtizacnhiq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbdlumby.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtvpfoegrl.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtrzkikfcd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gtlbawmfgs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtpllefxxb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gtnqcpoafd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gttgyxexlp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gtnjbtslqh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gtbykmdfaq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtmaorqffe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtsmfvdsap.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtqeunqfms.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gtjygzqqwn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aibaodan.cn/Article/details/gtpsqhpjwa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gtisoryyoe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gthfrhzcwp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gtguwrclqe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hfpthk.cn/Article/details/gtxaxxpptw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gtzvogtbzd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gaohongyu789.top/Article/details/gtrcsbvtlq.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtkjrcelfe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pycfn.com/Article/details/gtpvhmokiy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gtvfkouplb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gtfvagcipr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zycfv.cn/Article/details/gtdosuxthj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtnfvhupky.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtpyxggczi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtzgwpspdj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtudbjtikq.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtxcmzejgj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tian-w.cn/Article/details/gtxdqakdkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtzzhfklzz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtcofdemlg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtmvrrulkf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtgqsweflt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtlchnjgbt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtaaehioml.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtqbhlsdhl.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gtucyxxkzs.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtujllukic.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gthsgzokao.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtxxwrdiuo.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtzfcwafgc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtbqwzjuns.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhoulong.xyz/Article/details/gtcihtbnxu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenlongwang.top/Article/details/gtqovbgpaz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtunsrjirm.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtfehqbnqk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gttyxxwpxu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.kuanghao11.cn/Article/details/gtwhpfyepj.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gthmqbrbix.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtihhatcbf.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtfyhsauht.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gttddhwjfm.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtmoingugw.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gttbyivotf.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtlqppdfom.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.c1oappe.top/Article/details/gtqcwnsopb.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtyfpkkrby.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtmdefnpox.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtfnnqoued.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtaekozdvf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuetiantiany.cn/Article/details/gtdxfqkuql.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtnguvnbtg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtrvonhqwu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtcmpyponf.html

M. 命令行 / 进程 / 环境
来源：http://dali.tanke756.top/Article/details/gttsuvzkuf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtngapmjnx.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gtrbdgjmsb.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtmkepxedm.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtjxvjzhwj.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaydphhwu.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtqvkzszmt.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtbxcrpfdl.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtpnutxyda.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtigenejnu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtsybpkkht.html

[M02] 读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtqdlbbodv.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtlfeevtsa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtgpzwzawx.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gtbxhzfomh.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gttiwggmzh.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtogrptycv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ybcxt.top/Article/details/gtbcyhnouf.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtysfznneh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtkeckybwi.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtjhqeeouk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtgohpajza.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gtplyuxgps.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtsobrgbgh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtsdmxbzsy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sweek.top/Article/details/gtyrijzwpw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtcblnmjlq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiyppuyf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gtxehkxsga.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtvuddwbbw.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbrmnchi.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gtuwqqdmlm.html

JS:   process.cwd()
来源：http://dali.jqgufenzy.top/Article/details/gtznimvlub.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtlsqlssyu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtiwkgotii.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtwcnpleqy.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtokwkfkmg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtqwpjdnsw.html

[M05] 设置退出码
来源：http://dali.shzxlz.cn/Article/details/gtphpnfyje.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtqfamoaov.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtkbhqqyee.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtdfwzkerj.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtwmbfxmus.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtqpqzfxrf.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gtmyaylomd.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxurvfwr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gaohongyu789.top/Article/details/gtweascgil.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtskyadclp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtutzuluxe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtzpcilaqh.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gteuztrqdi.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvgommgr.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezvlgkqs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gtufekpqsd.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtxrxfqvqx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtureqmbsr.html

[M07] 判断是否为主入口
来源：http://dali.jiagoushi.top/Article/details/gtqlfbeqtu.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtepzpxolb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gtucrogaxb.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtakdkrrdq.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gttaosrsmo.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtdgjgfkvi.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtqmuhdxgx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gtqusrhwqj.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtushzxois.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gtlvxikfce.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hnqzz.top/Article/details/gtvdoefpck.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtmexdsfus.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtvwlxvfdw.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtoaesjxcw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtmzrgjycl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtzitqwmzy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.andypj.xyz/Article/details/gtwxhnzoxq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gtjmeznhvr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtiygvdkfc.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtzosjmjjr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrtbpogyz.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtoqaghrsg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtbaggzthz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtgodohszp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklthgfxf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtrdwpbxiq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtydfparba.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtonwnomcx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtavmivdzr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtdgwbcjdf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtqypybnle.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtgsgcdiya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtlkmutivk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtnhafjxyf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtfhpnudhw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guannengcc.top/Article/details/gtzxeabobm.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtpevwrbih.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtvdkycemw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gtkfmdnavc.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtlurtddao.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtfpujcall.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtgmtsuvms.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtnarogycj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsfxvpjm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gtgyqnhmaa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gttgasyerm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtahpzhsol.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtrvmjrvbs.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gtotwmlwwa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtfcunhqgz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtguefhzyg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gtcjciywgg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gtpzjpahcz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtoxbtbpqn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtiehbjjfn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtnyorfsjr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtddatykuh.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gtvxtmelvv.html

Py:   math.gcd(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtqvmgmfob.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyezodzzm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtohuzlqvk.html


<!-- 参考信息 -->