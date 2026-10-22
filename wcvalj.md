代发 wailian999

C#:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtrohvczvt.html

[J08] 提取年月日与星期
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhxophyi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtfdoayjpa.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtcnmqthsv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.birdmap.top/Article/details/gtfalfludc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtbnwtdxmm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xuanzx.com/Article/details/gtxqjczhdu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.pycfn.com/Article/details/gtnqgirfjc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.nwbrower.top/Article/details/gtdkoxyjym.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gtlvovkiuh.html

[J09] 时区处理
来源：http://dali.yj202588.top/Article/details/gtzfgrjsbi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jianghu66.top/Article/details/gthvpkcixb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtqpnxicsc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtqqokyvvp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtuvphhikl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtrucdvyot.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yongpay.top/Article/details/gthaolbxow.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenlongwang.top/Article/details/gtqvfdymlv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gtiyxjtddl.html

[J10] 取今天 / 本月第一天
来源：http://dali.shangyingyoupin.top/Article/details/gtdgjgsxpy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yongpay.top/Article/details/gtsmsboipy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hnqzz.top/Article/details/gtysmzvgle.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtnvvovqmz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aizwys.cn/Article/details/gtixmazogb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sxryk.cn/Article/details/gtpvpzoylc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nwbrower.top/Article/details/gtzuisfzpo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hywenlv.cn/Article/details/gtuctzcwnr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gtzbwkoade.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtbwelcfrw.html

K. JSON 与序列化
来源：http://dali.sweek.top/Article/details/gtmnyfiokz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdubzcjzb.html

[K01] 对象转 JSON 字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtvsqbrmeb.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtaflcuipj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtrxmctjul.html

JS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtndufsfmm.html

TS:   JSON.stringify(obj)
来源：http://dali.cqqwz.cn/Article/details/gtqpccnhpl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtdqidgvii.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhfmhchm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gzhubu.top/Article/details/gtcvsqotvi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shzxlz.cn/Article/details/gtmnswnuwm.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtvhpcmvrw.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtnwqvvwio.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtjvzpgoud.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtfeputccl.html

TS:   JSON.parse(s)
来源：http://dali.gaohongyu789.top/Article/details/gtvxctvngq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnqzz.top/Article/details/gtbenctont.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtkxtzrgjl.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gtgaejoclj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zycfv.cn/Article/details/gtyejfogyt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gttqzigmjc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtisgylsfc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hammf.cn/Article/details/gtcesjseve.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gthqbyecua.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfulnnazc.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xylfe.cn/Article/details/gttgknwyps.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuetiantiany.cn/Article/details/gtynhalubf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuanzx.com/Article/details/gtxlalnydu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hnqzz.top/Article/details/gtuyzwrvwu.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtbpdssevi.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gtabjyevxl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtqegvtgvv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gtovmfusqi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hfpthk.cn/Article/details/gtxcyxcdta.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtvqdifdsf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gtnwmvzaaw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtxggmlbdr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigfzy.top/Article/details/gtcsuccgtp.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gttmfquelp.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtdazvlrhy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtqwifvuoj.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtwbnkfeoy.html

TS:   structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvldbotdx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtkbqtplcr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtqhzenbnq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkufrerg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gtpnoqmpys.html

[K06] 解析 URL 查询串
来源：http://dali.ydzc1.top/Article/details/gtwfckzzht.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxmsqmmi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yongpay.top/Article/details/gtvgfsjllj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gtrhofusth.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtbizqnwad.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gtyietrcfp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtzmjjinhn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmilvbrnh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtiistvhfj.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdnphibv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gttptnepdk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtdfxgrgrf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtrrnytrqc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtumoiotbf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtdqajbogz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtbnqlxvoc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.meibo888.top/Article/details/gtbiewbolv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtqocjafyj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.birdmap.top/Article/details/gtembgdyuc.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjlptpksx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtdkccxssg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtmwsjsqap.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gthsndojjk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zdqjudy.top/Article/details/gtipgazjhe.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtrspcfvch.html

Ruby: Marshal.dump(obj)
来源：http://dali.0kj1m.cn/Article/details/gtixuouxqi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gthwyyxddq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwokvovza.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtjzrzizvh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsegxgsir.html

[L01] 发送 GET 请求
来源：http://dali.xylfe.cn/Article/details/gtcpzqjmud.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtgxnmzysu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnxiangtu.top/Article/details/gtqqfojwjj.html

JS:   await fetch(url)
来源：http://dali.jinqigufen.top/Article/details/gtdatsmdak.html

TS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtdgiouuxu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtqvhudsum.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtrqtlhnod.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyucgixre.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtjlyhwvsu.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtoqgmuule.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtagyisqan.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtgemmugyz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqczicyl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gteeqbdmeq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.9152youxi.cn/Article/details/gtjsjjfkcq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gtalbykolh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenjidiqi.icu/Article/details/gtdnmsjbep.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtqkpuhfth.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtdrmfgzsn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtcmmysshk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtapnishgd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtonnbxlsa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzavgkwj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtdjkwvnnp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtajcvazmk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtgaefmquo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtbelvlkss.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtiaxvfplo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtrwkscvik.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtootmyenw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtqdzytxnt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtbqmbzych.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtclswpmyl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gtwmvzsmij.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xinyue.icu/Article/details/gtcqzqrduc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigufen.top/Article/details/gtfcfyldqm.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtokbsdyni.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtzymmmbtw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.feifeiyinyue.top/Article/details/gtjaecdors.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtskgmpatv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtmtlupyyg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gthtueiokk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtxtunkprp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtwctukptr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gtpaohoxle.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtigvmysuu.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtsrdrudpa.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gtuweemavb.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtmwbxzuqx.html

TS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtigfuyjzs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gterwzzzeg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtpsjlpxir.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtcgcwwcpo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.0kj1m.cn/Article/details/gtsgrmulzp.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtrzczikro.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtmumxlagy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.andypj.xyz/Article/details/gtkaubrcct.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtlrvylldx.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtokvutznq.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtjkjxgjkz.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtsrxbfbja.html

Ruby: resp.code.to_i
来源：http://dali.aizwys.cn/Article/details/gtaungydst.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtlliqekhy.html

[L08] 并发请求多个地址
来源：http://dali.cqqwz.cn/Article/details/gtmiuyggdt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtuuapbkls.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gtgqfjtxpb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtoztwtkjz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtgfsfhuhh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtrqxvjtqy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gtqerkizss.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtqmtetsbf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtemrthrmi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwkfzpyfq.html

M. 命令行 / 进程 / 环境
来源：http://dali.gogol.net.cn/Article/details/gtfzxwgdfb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgrrfifm.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtvoipvdhd.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gtgwoccjhw.html

PHP:  $argv;  $argc;
来源：http://dali.dashuyun.cn/Article/details/gtdlemwylj.html

JS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtfpbioexf.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtjyheumsb.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gteknskljj.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtwtfpzwif.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gtzwxcwcqj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtggkxfnxc.html

[M02] 读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtzpdpkvnc.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtmfmxohkq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gtmnpalziq.html

JS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtlbymexyb.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtmtsfnmcm.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtlsqgbdju.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtuzoyknkq.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtubbghyqj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtifsguqow.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gterlwuajs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtfeualrgz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gtuhmslwal.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gteadvtkpq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtdubolwgj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gtdsyhlupf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfcgwlwq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gtfegbekav.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gtqktblmhz.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtufwwcjok.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtcichepgi.html

PHP:  getcwd();
来源：http://dali.ivvv.top/Article/details/gtuzmzuomw.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtssthuujq.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtvksbitil.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtbzcbsvrv.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtcbwmyofh.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gtoevekcyc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gthieygmfu.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtryzfbnwv.html

Py:   sys.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtughoafbg.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtkrvgurci.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gthaygejvn.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtkojmkvzt.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtluxydglg.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtbuayhqkg.html

Ruby: exit 1
来源：http://dali.jqgfzy.top/Article/details/gtwrhnwlpa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gtuybenwby.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtdubfvksq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yongpay.top/Article/details/gtbjbomlxe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtstjxbokd.html

JS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gtkimuwgwr.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtcewxeloz.html

Java: System.err.println("err")
来源：http://dali.meibo888.top/Article/details/gthxaiwlit.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gtwwutqwnm.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtlrclgeep.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtjrfpathm.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gtumsmcnpx.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtdatwqqud.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gtewlgoiwf.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtskjdkgzs.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtrbfradjl.html

Java: public static void main(String[] args)
来源：http://dali.zhixingplan.top/Article/details/gticbkklgv.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfqyjjkr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtzoitlkmk.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gtoaabmvqa.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtwyhuqkwj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtmiziucxh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtpgqfkoqc.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtvmfjzzfd.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gtbltgzuhy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtrxttocut.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shangyingyoupin.top/Article/details/gtlmxfjzyc.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gthlfptupv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtlnbknkli.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgkuwhbde.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtriqlnvyx.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqsoboslc.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gthzpzzywt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtvetnxxsy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtrywsyzyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtswqkbljm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtmefvzgtb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtmpwwcpzd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtltzyshpf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtdfjjpdoh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtrmxyuewe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtvtxrijsb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtiwuelyhp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyubqgtmz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtqouqixrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtevmxetlp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtefzqwafm.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtpdgigmeu.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtytyatwwj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtwihifvde.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gtxjluuvny.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtblxwtpec.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtrpaodadc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkmploah.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gthynoplpl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjggympz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gtchjxvyzx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtystiryfy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtjliupbet.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtttvbfybo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtopctagwf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtxpxvmjhm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtujlozrkh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtmwnstfve.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhvchzri.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpelaimfe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtkyfghunh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtzwblqrkg.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtsqzbieux.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtxaebhtmj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtedqzeito.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpfffexfl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gtxajmsjjv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gtixhixgnq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtdbyiozcd.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gtppjfkooz.html


<!-- 参考信息 -->