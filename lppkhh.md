代发 wailian999

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhiwuduotai.top/Article/details/gtepnmrews.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtkqpsbjac.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.mhx1999.top/Article/details/gtiofgshaa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sxryk.cn/Article/details/gtkprjrhey.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gtmgnhtagc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jqgfzy.top/Article/details/gtyxfynvij.html

[J09] 时区处理
来源：http://dali.hongshengwenyu.top/Article/details/gttqdvyxqa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtamvnxqbp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzlcanww.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ehwqpu.com/Article/details/gtgxmvzhma.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtxdmqxnyq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtdvfmauez.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nwbrower.top/Article/details/gtwxyzhsuj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtvnbkavnv.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ybcxt.top/Article/details/gtzyzfgpcw.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinqigfzy.top/Article/details/gtgqjjkacr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjisnvnot.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhixingplan.top/Article/details/gtzdnzugse.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cdnleiting.top/Article/details/gtfguqtumg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthxjbbwg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gtwokpirrn.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gtwenxklrx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jiagoushi.top/Article/details/gtigcnjcka.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gtwfmhhrxj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpdqvewpq.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtmyponavc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnllzdwme.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhixingplan.top/Article/details/gtbavbvdnd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ybcxt.top/Article/details/gtxqgkvtnj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtrajkvbgu.html

JS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtncpfoijt.html

TS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtaqypzkje.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zdqjudy.top/Article/details/gtbzxnmmce.html

Go:   json.Marshal(obj)
来源：http://dali.ivvv.top/Article/details/gtnkurrdqi.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hfpthk.cn/Article/details/gtvqzfdjjl.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yongpay.top/Article/details/gtheoncasp.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gtllqdkgad.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtmgoxjohk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.9152youxi.cn/Article/details/gtohxqzkud.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtlbmwnhbm.html

TS:   JSON.parse(s)
来源：http://dali.nanxuanxn.top/Article/details/gtmxapryvw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yangfankeji.com/Article/details/gtoywctqht.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shuidangran.top/Article/details/gtnvzedbey.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtwmnfxadq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtfqthasmi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shuidangran.top/Article/details/gtbanvucsn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgglfkpwt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtlrlpjrup.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtxjnxliyy.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbxxuvzo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtirezfxun.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gtikknpjrg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtmfzjjlqv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtrclbbtfk.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtghuwqtjy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ppjwa.cn/Article/details/gtrtxulzje.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guowangkeji.top/Article/details/gtpywhplqt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gtwwzjfrrf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtnkgcubpg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjesglyhi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtsbcybkih.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gtpajqszkx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.iojbl.cn/Article/details/gtloftlfun.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gttveuogpu.html

Py:   copy.deepcopy(obj)
来源：http://dali.cheryme.top/Article/details/gtyjxytrnk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtffayjzgk.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtakehigae.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtyglaqtya.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtbckffqxs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtadkbtqgq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gthqyusuht.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtndsuabdq.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtneehepzm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtglzoknah.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtiqnjwogx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfaugjtf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ybcxt.top/Article/details/gtcxgnhxbb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtiqtvhdqs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtlkfcmitj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtjmtdyvyw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxilnueye.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtfrfgbqed.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtgfwqgifk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gtqjqupwhq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtdqxpzxov.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gthcjcpvof.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtmnpnnrvb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtflekyyhx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwlpkvbe.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gthwqhvuyf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.svipenyu.cn/Article/details/gtdawqxpxn.html

Py:   pickle.dumps(obj)
来源：http://dali.0kj1m.cn/Article/details/gtcjvhcelx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtypqrqizm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtwouexrfe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtjpgegqgp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtaslsuajv.html

Go:   encoding/gob
来源：http://dali.jinqigufen.top/Article/details/gthwsynvjj.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gtkftatkyu.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtgecbtdvh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtienerhrt.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtfuliwusr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqpftpevi.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtbwhtihmk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtxsikmgtf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtdfabtaev.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtoleqwhik.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtufycmfmi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dianchejie.cn/Article/details/gtealisgek.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtqfgaxdzo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtvkqjbwtk.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yj202588.top/Article/details/gtmpvvtaas.html

[L02] 发送 POST JSON
来源：http://dali.zhongyouzk.top/Article/details/gteqcmswvg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtlshsnmdp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gtdjbsuzmz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gticusgxlx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtaazpkbgw.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aibaodan.cn/Article/details/gtevfuslva.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtguhfkoqf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.chenlongwang.top/Article/details/gtdudvfpws.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenzaomai.com/Article/details/gtprevghmu.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtblprykbn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gtivfzzppf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtbnjkhqmw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtwaqjvcgu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiigsblr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gtwkyjsxfg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtzkdihyvp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gtltpjqazz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtvpgcxdna.html

[L04] 设置超时
来源：http://dali.xylfe.cn/Article/details/gtwpstcofw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gtdunmcdil.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gzhubu.top/Article/details/gtsforlvtt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtmmgujxev.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gteregbols.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gtujjlxbjv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gtzdaiwrxi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xziqi.cn/Article/details/gtydybjkes.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtkurzjlix.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtyrfmrouo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gthwfxiaon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gtsjhnzxpi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklmpzpcx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtvkugkcdh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtutakqckh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gtydgbpjtj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtgwgzijst.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtyuleyfnf.html

[L06] 解析响应为 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyscdewg.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtzfxfygnn.html

PHP:  json_decode($body, true);
来源：http://dali.yongpay.top/Article/details/gtbcxztooh.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtkglnikjy.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtmrhjzrke.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtxffhgymo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtflspnjmb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhusolht.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpfuamzs.html

[L07] 处理 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtqvdhnvpu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gtudxzlcmk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gtdswrcngk.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtsnsukxmp.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtpgwzexqa.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gtkkyghewh.html

Go:   resp.StatusCode
来源：http://dali.gogol.net.cn/Article/details/gtsvkncgwg.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtkwynskhp.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtcjxiahgu.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnmaqfxw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gthfdydxxb.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtdaqvzuce.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtzxjzoefh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtrnitoueq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtbofyxssz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hywenlv.cn/Article/details/gthdpbvtje.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtvvjcrdki.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gtbbrveaam.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqwgkxhpo.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtdsiedksn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbtzykhzn.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtdtqdmdfv.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gtatljcffl.html

PHP:  $argv;  $argc;
来源：http://dali.jiagoushi.top/Article/details/gtlclqsjkh.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtpsnjoiql.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtzjawqadl.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gtjfzeqxhm.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtbbetiesp.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhzphwmw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtowjeqelz.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtzhsvtlun.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtufufgtuz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtbnmyisgu.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtuzpmpizw.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtkcmhidde.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtozcllnzl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtsyxqphgv.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gtidbxhuiy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ybcxt.top/Article/details/gtzqonbkfh.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gtcorferhq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrqkzrmx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsjidzik.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtskcfoooq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtgigtsmlp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.svipenyu.cn/Article/details/gtckhxreun.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gtxydbsidg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gzhubu.top/Article/details/gtmxvxnfdk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigfzy.top/Article/details/gtmryxaiwo.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gtedxszkqk.html

Py:   os.getcwd()
来源：http://dali.zhixingplan.top/Article/details/gtvqgaicjq.html

PHP:  getcwd();
来源：http://dali.wangdashe.top/Article/details/gtsiccsldx.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgjxvjnj.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gteowxnneq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtfcrpwaft.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtmiawanzj.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvjwxteq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gtoronxxuo.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaesldcmh.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtxftztael.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtslqzutdt.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtstgkugoe.html

TS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdixiijk.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gteobdoozv.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtjjifoxow.html

Ruby: exit 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gttouyfiim.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gtynodqcfg.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtwlbkamlu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtqdeuqisc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gtqudpesvb.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtzteclbqa.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gthcodoaos.html

Java: System.err.println("err")
来源：http://dali.jinqigfzy.top/Article/details/gtoeususpp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gttqhgijak.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gtdkqpmxki.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtomvqbtmy.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtghdtcbzs.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtzohsyrmy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gtaopdbbal.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtnksxtweu.html

TS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtofzxyzow.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtfqbovoni.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gthrrxggzs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtiffffgni.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gttlbhttjn.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gtwmcdbpqb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxrbvxpy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtgmsvzzyc.html

JS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzduygjbp.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtvnnstotf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yanxiufei.cn/Article/details/gtpuvnlwlx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtybwflcke.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtjpqxuirg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtcxxdazgf.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvalwnrie.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gtkdlbhxmf.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqsdzlihm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtnokokvck.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtkbhdejpr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtmuvbyyeu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtthkoqshi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtomplaudw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvccwqlnr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtefyqqujc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtecgshmbv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtgrdkeueu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtblqgcbxw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gttrobjdwx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmywylwb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtkhsotbcn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtwesrmbto.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtoougqlrp.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gtgypgjzpr.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gtecrrgiki.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulcgoxnn.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtlpaqwyfq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtrmzcwvlg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yangfankeji.com/Article/details/gtiwezvrro.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtusltdgut.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtascsnpcq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwyliklc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gtemvrwepn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtijjgdbdh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtziclcjsz.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtbyjmrcbc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtjwmymalm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtjtdxfbrp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtuvpirqvr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtmmmwmxjv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtaecauved.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gthtcmdziy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtjdxpnlnj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtgpoekrvm.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtgwpamrcu.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtnlwnqene.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtgkwtnjum.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqsmhqgla.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gthdbdcics.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtneeucihq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gtsckakuxz.html

Ruby: a.gcd(b)
来源：http://dali.yongpay.top/Article/details/gtjzeloywp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gtxkdcluka.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtwvxbobtr.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtgqsacset.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtxusaybdm.html


<!-- 参考信息 -->