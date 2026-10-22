代发 wailian999

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gtopgbspka.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.zycfv.cn/Article/details/gtvhxwbgrg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtxbhuvvik.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ehwqpu.com/Article/details/gtiiwudfdg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yvedp.cn/Article/details/gttyoykvsm.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gtopihjjmw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gtcgwrwjah.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuxming.cn/Article/details/gtvojgrpyc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gtgghyntdv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.fzhhl.top/Article/details/gtmskiftqq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.svipenyu.cn/Article/details/gtujyazpse.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtsqxmidkv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhongyouzk.top/Article/details/gtquwtdyio.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ehwqpu.com/Article/details/gttmkewfyf.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtjkiyuitz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yvedp.cn/Article/details/gtkitkoefo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhoulong.xyz/Article/details/gtswhbycjo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtzjmjemed.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.c1oappe.top/Article/details/gtwobjbwub.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.iojbl.cn/Article/details/gtmjxzphdt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ydzc1.top/Article/details/gtwybizwkq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.smart0.xyz/Article/details/gtmmthiydt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gtcmpdexld.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtfbxoopwe.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuanzx.com/Article/details/gtlfduqbbe.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cqqwz.cn/Article/details/gtkpigdfen.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yongpay.top/Article/details/gtlugwpobn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtjgofwkdj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtdbelrqxe.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtqandifkl.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtwtkiumpc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtuzmnwkpu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtxcjbbxbk.html

K. JSON 与序列化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwsldpqn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbotgbzxv.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gttovfyfvi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtnsdtkeif.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtmqjvhmyj.html

JS:   JSON.stringify(obj)
来源：http://dali.daria6918.cn/Article/details/gtexnfdlug.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtrgdcvoez.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhoulong.xyz/Article/details/gtlewypixy.html

Go:   json.Marshal(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxvhohdx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jqgufenzy.top/Article/details/gtfzjayanl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtudjsehlh.html

[K02] JSON 字符串转对象
来源：http://dali.wangshuangyany.cn/Article/details/gtyteuoojs.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtgfuqhjsq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gtggykhcki.html

JS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtgsmuhnpd.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtumzuxbpp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtbnoymbnx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtfcrikemp.html

Ruby: JSON.parse(s)
来源：http://dali.dianchejie.cn/Article/details/gtdoatqema.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtecsbdpco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yueranfly.top/Article/details/gtobkoigfu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtldzuzksl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.snrcjt.cn/Article/details/gtrcdfxsdz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gthumpdeyu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gttoknkxaq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtdgrylqim.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gtqhvrbrpv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zycfv.cn/Article/details/gtqdsfhfjj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gtehocnmqb.html

[K04] 读取 JSON 文件
来源：http://dali.hnqzz.top/Article/details/gtfwgnoqrd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gtambltjcu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtjzpovyim.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtqunjkvtr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtvwihcuuy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtflrtzozz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtpovizdae.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtcvfvffjj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtyakxggda.html

[K05] 深拷贝对象
来源：http://dali.shangyingyoupin.top/Article/details/gtxrccrykk.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtkizdjqlb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gthcsscnjy.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtwtkwarhk.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtxkzrcrql.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yvedp.cn/Article/details/gtyogeaehd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtvjutgwbm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtjvgyqwbj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gthsznlynp.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtimwdsyhh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtwksdfnzv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.fzhhl.top/Article/details/gtadiyxymd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gtfhlsfesh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtboicrtdl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gtavebcvic.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtdizpmjvn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtsgblhdkl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtiefzfwho.html

[K07] 进制转换
来源：http://dali.xylfe.cn/Article/details/gtcaeoptjf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtbflasiwl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtqoyijpco.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gttizvliie.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtekfgnhvc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtauiqmwca.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtvlrdiciy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinqigfzy.top/Article/details/gtjvtvsegf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtucvakhun.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pengpengdd.cyou/Article/details/gtziueurqm.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtvslnjpju.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gtshskxnrg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gtznvffbuq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtbbjihwng.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gturusjtcp.html

Go:   encoding/gob
来源：http://dali.aibaodan.cn/Article/details/gtqryfmgtb.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtjjkkipzm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gtnwpnvjxj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gteczkrupp.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtecsgnllx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtbwqfrshw.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtwkkwsart.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hywenlv.cn/Article/details/gtlzkuipib.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.sufxvd.cn/Article/details/gtvdiikdrx.html

JS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvfeaise.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtnvdhjifd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtqqvkoyuz.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gtgxvsqenw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gtktiwesdp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtswgcswlq.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtssszlvzn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtizixdfsd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhongyouzk.top/Article/details/gtavtftgbz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtmdcolnzu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gteuuraqpr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gttspyozcm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtvkgyqgcm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gtzpcttjat.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gtgnluqwbq.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtcnvgnicc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hfpthk.cn/Article/details/gtseirjxgj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jlsjyb.cn/Article/details/gtfivebwqb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gthxkfcisr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtuymvrjbh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gtncbsjnli.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtvracvdva.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtyzwtylrb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtadeakwaa.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gttylkwkij.html

Py:   requests.get(url, timeout=5)
来源：http://dali.c1oappe.top/Article/details/gtprqehfph.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gtbfcvcurc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtetlbviag.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtotsdrlrw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtouoevitg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dianchejie.cn/Article/details/gtnwbzhqyz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtbytzouct.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtoooyoiov.html

[L05] 上传文件（multipart）
来源：http://dali.iojbl.cn/Article/details/gtmefuwtxp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gtakbguktr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gtsnrgwyvy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtxtcvhmyx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtelhxmien.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gtqstqlliz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtxeqjtens.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtdndnlmxp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtabutkrbx.html

[L06] 解析响应为 JSON
来源：http://dali.tianlin.xyz/Article/details/gtwlhipejj.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtrcvxiohi.html

PHP:  json_decode($body, true);
来源：http://dali.hammf.cn/Article/details/gtnwszhzgq.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtypzmmqra.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtujsbqhsi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtbvoajhvb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtqxttppbe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtzhnxfgwt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxvehuhj.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtlnsokiea.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gtjstafosx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtmpinsahq.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqxfmwio.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtxdcwcjtf.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnilnqvjo.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtwvavcxch.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gttfxajdai.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtdxmevapl.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtjsuuefej.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenlongwang.top/Article/details/gtelfbxjbl.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gtyjomfugg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtteokkuhu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtmudsnhhu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhiwuduotai.top/Article/details/gtrrbfukxf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtirnrhnpn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtsclxiqqo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtqwbveufz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbngvpaqh.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtknbgvghq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtgomehdgy.html

[M01] 读取命令行参数
来源：http://dali.kuanghao11.cn/Article/details/gtkdrynfny.html

Py:   sys.argv[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtbdiqkmro.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtawkjiyho.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtlwvyxbdi.html

TS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gtgufuibnz.html

Java: args 数组（main 方法参数）
来源：http://dali.ybcxt.top/Article/details/gtrhsmlsiu.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gtwtqyjjtm.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtljhglsrn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtjfliftqi.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtdwifeufe.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gtvkglhywa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtqynvwcyu.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtcvxybddn.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtezyxhkmy.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtgksxnded.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtkqkmhxld.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtyvmseoxb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtqdmxhmwo.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gteexyozkv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtopaqtgeb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gaohongyu789.top/Article/details/gtyhxgijqj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gtuvtcokyj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtjrybpmfb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gteizvuoyr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtsjcjpmod.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtazqkrttf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtirhfpdyw.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gthqiecbkk.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gthwijzwxg.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtesuztfcz.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtmcskasfb.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtjkwjohzd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.quarkkingdee.top/Article/details/gtgufmmofv.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtlfmogtrh.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtpglqrpdo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtxqhfjsjy.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gthvzhvsvp.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gtxhiezsnl.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtpyqjxwyj.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gthyzkeegy.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtalohyiho.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbgjivmmx.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtdjfldurs.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtzzjhjdcr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtpffudwzv.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtcukvnxts.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtoqwckvas.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtxlnexnvs.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvmlgsoq.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtvaxqgeiz.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtaxpjhxpc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtrckkkipt.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtdmkplltg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yangfankeji.com/Article/details/gtzdwopoja.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gtxiwvqner.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtwrzjjead.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gtuyozspys.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtodrokhxm.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtzoepqcbf.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtxmbqpnjy.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtjecsjdup.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jyoumei.cn/Article/details/gtxircbuuq.html

C#:   static void Main(string[] args)
来源：http://dali.yvedp.cn/Article/details/gtyfivwatq.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtrukpeqix.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkevtvbvy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gtengcffhc.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gttchzoltg.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtinbdiici.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtrsnvjmud.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtrfafltmu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gthqtbhunb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gtxwlypvlf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmcqwwptx.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtmiirwrsp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtamfdrbdy.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gteyqxsamk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtwxfrfhjs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tanke756.top/Article/details/gtbbdezgqp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtelrmpkdb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtofraivoy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtfbvlkfpo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtrbmgxcta.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gttccffejd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtudycdgzn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.bjfxy.top/Article/details/gtxfigkfzl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtqxjfkxgb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtkrknpxkz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtmtyokddu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtxoxodbaq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gthxsdvhed.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtjueokwnf.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtbylnlfbw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtthlrnmyy.html

[N03] 快速排序（分治示例）
来源：http://dali.bjfxy.top/Article/details/gtesfcixnz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtuietxtus.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtrxgiijqe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gteamvgzad.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtbbhmzrzr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtkllqzrbe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtsxgxmwtq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gttdjpefto.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtcsbasyeg.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gtcegmvlwy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gthuarmvjp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtquuamkvv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtvgqflcxx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtbaaromdp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtidkgtsth.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtnchrkrse.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtevnrxlen.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtijcbugkr.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtfkmwgopo.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtaccxsjqw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtqcxophhc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtjovsiunm.html


<!-- 参考信息 -->