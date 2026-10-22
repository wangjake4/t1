代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtubiblw.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhijiandao.cn/Article/details/gt2mslaedjx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbxsvem.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwlgidh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwiinuz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhijiandao.cn/Article/details/gt2kobqcqcd.html

[J09] 时区处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdxltje.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgikebbl.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdoyvbpq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2jusjwdtt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgkgdfi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqhfcxq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2grnipfsh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyoaifby.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhijiandao.cn/Article/details/gt2htfaxfxo.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyrxxws.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxflnivm.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrqesus.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zttwpxay.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqmrozz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2riurbzxo.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmqsrpi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhijiandao.cn/Article/details/gt2apribdni.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oivwhyum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbbqpsu.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2hjztcvwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjbwbop.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2meyvnjuv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwpbsgb.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpecevnb.html

JS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2npvcuhxi.html

TS:   JSON.stringify(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzerknzl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbvkxjc.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tutmdjiz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmyljzz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpmtlst.html

[K02] JSON 字符串转对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvajprp.html

Py:   json.loads(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epcmbdkb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpbxwro.html

JS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwejqhn.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiimvmkg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqjcvuw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2gasbaryg.html

Ruby: JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyveqcw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdztocrq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2soiycemz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxlltqe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfvgwuy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hokofsrc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybluhqxl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2anispqvm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjalrpkk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2raizqgpm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gt2neekeszw.html

[K04] 读取 JSON 文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umdfuadq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvrenfd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyqffsz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgwrkpd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyzegaq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyymzsow.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmgausg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvawmdh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmruvqnf.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhxqntp.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2chzpzulv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnlscep.html

JS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnwgrol.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfaqgubc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2efzechmy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhijiandao.cn/Article/details/gt2evqvjfky.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fchxopaw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gt2fjggejft.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqtvgvd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2axikavqc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaurvab.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbjiolf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzhgkmn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2upduaill.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkefkpz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqnowxl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2svgrswwb.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gt2buhwddfx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrwkdit.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhewqgqq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2djufoizc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qblkqfnd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvkpvjf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyorxxp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgsbozf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxobcbhz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyobebit.html

Py:   pickle.dumps(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufegpltq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaxvbio.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xaralkpj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2muneixwu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2hodtcjox.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2qxihovgj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2clvgbmhi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpriztt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snigugvn.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cmohzmdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhxmmbb.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2deqljjxf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gt2kecfstui.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxpkity.html

JS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgogbwef.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2orybuior.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gt2upaejoan.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfsbasj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxwgtvs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpsyndp.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dwykxfeu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhefqa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhugiqe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdkwibl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqkemlz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcahmkz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2epclzvit.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2fyotynyq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxewgoee.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2wapmwmyh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxeejvz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkixrwhg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ioswlroa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcbnawi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhobiuxc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2yheoprrb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzytklff.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2wixiszzx.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2glrdakct.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2inotkwmf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpmlhed.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mupajjws.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yzaidqvn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2srmsugdc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnfyced.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpfsntk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncylteha.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2osutpgym.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdkcfhi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrumcgwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2zywmqyrx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjowmar.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbfdapm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuytgdph.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2wonvqkgq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjecqgjy.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2synftogj.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjclkoty.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjoelnp.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2xadhubpb.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuketzd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvjrnai.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2voycjvvc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdvpwju.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2livxaqfs.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2asnutfto.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2idwicibn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2tphpfetr.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeduuyf.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2wogreunr.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2odkgbzrp.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2isczgikk.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2vaagrlcp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2qteuoomg.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxxocww.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2utfecetp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2mabwjzvq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuikwgr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxvynry.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2layswpgu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhthoda.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzguwvu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfelybhz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uksfcazh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbixpkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hecxzjqc.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyztrgtp.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2mieqadnc.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2svaxpoul.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgohqir.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjjtupr.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2somcqclq.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qupbmnuy.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2svkwmmqa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2cciyxpgl.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpdyeyb.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnhkzxd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjxmeez.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cciqzqsi.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzcwmpl.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxbgshw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmthcdx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzprplo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fydfteqb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuzlpqy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2drjufypz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfjjylv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nobtbapy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2csgnogmh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2doerhlta.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlyxyrn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2juztcfew.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rilkqony.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiyamin.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nslqwmzl.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkpkpuf.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfovvdlz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfrthmbu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlprezkq.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnhwsvo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpfbmjq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2triydafl.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2rpodwlao.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rillzzlg.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkoygzf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vztvhnel.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaqbwls.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2twrumhex.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmqtzdm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpgndgb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2adxikopr.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rtelgges.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhnjyhk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhkyaeh.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvofupu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdpwnev.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrecugbg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rimvwnch.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2acmahtkm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2abyowwfj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2alvenfdk.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbzroff.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iklutqjb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pudpnxri.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dyftpglw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxljylcb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvejwdyq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvidohw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2rshasmqv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2knzhxjvi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2texkxpap.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gabfkxjw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkaxrrs.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmksuhi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhqkmyz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmowizfg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gknybmuf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2akmizjrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdccoliy.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyxldwl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgwykwo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtkmeyl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cobkitns.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvvuoky.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2npmzyrvx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2foyluuge.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mipbdqqo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2euqhtryr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsnaixw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vivynmxg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yavmfgsn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2whcyglne.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2htnyoawn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2umptkbzb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2idyscewq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2txiimsgo.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyodpxrh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbwbkry.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufecjhle.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiscqgfn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ufblxiou.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkufbio.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2shweqvbp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvjknlx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcaacsf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jscajyot.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2znzlhazu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2snnbxrlm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2alghetjs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2azcqjbim.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhbgwit.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wduyyudz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvcmdid.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdugben.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctloklau.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjactjhq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtjjyef.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2azzaiouw.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfogjhko.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kphtvupw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmqjaqi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvboxwgf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaoqkdn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2chqqzubj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyixahd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebckwhjc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2syjffoku.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbonnwd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgqdlre.html


<!-- 参考信息 -->