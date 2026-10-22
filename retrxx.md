代发 wailian999

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yongpay.top/Article/details/gtmeejyczf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gtsuyefkgl.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gtbullqexf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfsuttcw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tian-w.cn/Article/details/gtysoqaknw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnovshjz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtyzpabnjm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtnyhmyyxk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinqigfzy.top/Article/details/gtciwcvvhv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtyomxttli.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nwbrower.top/Article/details/gtrtncxfeo.html

[J10] 取今天 / 本月第一天
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcixflmme.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gttsqqllyu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cheryme.top/Article/details/gtbljxmojx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtvjrncmcg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtnbyzqmea.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gtiadijvci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtzjfnmgzj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.redwolf501.top/Article/details/gtbamcjhkj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.iojbl.cn/Article/details/gtthhfdili.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttesdkrlm.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtdtntofdx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfrlfrkzv.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtdqukoipg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtvbtvhtmh.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyhzntis.html

JS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjfiadrij.html

TS:   JSON.stringify(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtefpcfwmo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hywenlv.cn/Article/details/gtmbpxpark.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gthwvkdewu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.fengsongda.top/Article/details/gtpvjerxzs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zdqjudy.top/Article/details/gtdqbiezed.html

[K02] JSON 字符串转对象
来源：http://dali.andypj.xyz/Article/details/gtnrctxqoz.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gtvymppczd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jlsjyb.cn/Article/details/gttgqkdmov.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtnkkwcxpu.html

TS:   JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gtpstwwjlp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gthzupjisl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtbwhssuya.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtiqnqhoyk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtvjbfopus.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gttcuitnvd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gtwwrlsbis.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtmrchqinw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtmirulizs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtbxlrlmah.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yvedp.cn/Article/details/gtxtqtmjid.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtvmvrdrrv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtgayopgxk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuxming.cn/Article/details/gtcazxdkve.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gtqecoffah.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gthwhowmle.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.iojbl.cn/Article/details/gtwrpkiitb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvymctpq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtnacuvwmf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtdwqejmbe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtrwblnijt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtibivylbx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtfgpbqlxn.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtqhzgdgoh.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtufidwoqe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtqjhpfbsu.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtkydvcwbr.html

TS:   structuredClone(obj)
来源：http://dali.ivvv.top/Article/details/gtkanlajcb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gttbtolcab.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cheryme.top/Article/details/gtkoatzunp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtlrxhhget.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtfanmciah.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtlesxlujq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtdzqyhexh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraiaoywn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtgtwyeefz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtjsssjyow.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtvaemtghw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtyniieudb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtilzffwgx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtwkhottmi.html

[K07] 进制转换
来源：http://dali.hnqzz.top/Article/details/gteqmedmdb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtmqdymwzb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.0kj1m.cn/Article/details/gtuxwcoylx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtftbkgyzl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtumnfujvx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtlramkocz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gtwmfwgwmb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtfjehfkuh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtvcsivpwn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.snrcjt.cn/Article/details/gtapkwypum.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtrjetytht.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtywiaxedu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtyozowfny.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtlugfltol.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gtfagmqlhh.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtfbsbmgtg.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtustjjlop.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtcuavxymy.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrjwxrxjw.html

L. 网络请求
来源：http://dali.zdqjudy.top/Article/details/gttsmezljv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnireceif.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtnwvtthzh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhongyouzk.top/Article/details/gtmgfolneq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gtfmlipfhb.html

JS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gthvpjrxjp.html

TS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtrmqtiwqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sweek.top/Article/details/gtuhcqrihk.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gtziuvcryx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.redwolf501.top/Article/details/gtibmybbwr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtqmoryqry.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkerkrkt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtdeobzkkm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gtwxzukddf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtzldiqixy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadqwbsal.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gttyvhiweg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gtcofpahdh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtinmddtgp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtsjhxugil.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtotgcgktq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtgxbbdkhu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtgdnittyy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtcxfsboow.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gtmcvaazdu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtbstzwagg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtwmbciqdx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hfpthk.cn/Article/details/gtwlietpmr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtkibiohcq.html

[L04] 设置超时
来源：http://dali.yvedp.cn/Article/details/gtqrpkwtjt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtjymnkqdf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gogol.net.cn/Article/details/gtprpkmipn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtamydrqbi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtxhvsdfwy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.9152youxi.cn/Article/details/gtlkbtuppd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtxtoknhqf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.kuanghao11.cn/Article/details/gtuygrrjxi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtusoetwno.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtvdyrpzqp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.mhx1999.top/Article/details/gtpfjwmrcn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gthglstoeo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtewqwjkfj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gthvrmuzqa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hammf.cn/Article/details/gtjnbnxnld.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gtfcsohqde.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtpnnnmpmi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtsdlxgygm.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtllzpmxxf.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtbsmftrdl.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gttuqzzisa.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gthtfbpmfr.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlabxqao.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yvedp.cn/Article/details/gtjsgihfwl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtxqckxsaq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gtcfccujcz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhongyouzk.top/Article/details/gthgopnnvv.html

[L07] 处理 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gthrrnuzzv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.mhx1999.top/Article/details/gtkkbdgcbk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtcjvckskt.html

JS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gtmjhumkwn.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdrdpliz.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gtdepinxju.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtqqrwkbko.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtvnnpbdko.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gticdzknur.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gthtidcrqd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtocgixcqf.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gtfygfgooi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gteutqostv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtcbmbkmzc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnqzz.top/Article/details/gtgfsfggqh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtndrukrnm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtqohktoys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sufxvd.cn/Article/details/gtsqfnvoqq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtcufmjnwv.html

M. 命令行 / 进程 / 环境
来源：http://dali.cqqwz.cn/Article/details/gtzjpzakfa.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtljmcqvwc.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtcbkdkpae.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtwqxilwng.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtlmxteibj.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtlfuznoal.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtffvlmvdu.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtkolchcqo.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gtwjbcujbn.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gtcrsyofhv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtuhceguqw.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtjkguvlzs.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gttwbxvhbb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtrtklpkpr.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtnknjlkjp.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtvmabtrtm.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtiymxtxgd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtpptdrhke.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gttwcmhrpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtrujxbqft.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtxwlycavr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jiagoushi.top/Article/details/gttrupyybp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtdriyrzdp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtgscwpgip.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gtcxqheihi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gtalagkddp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtfqcevqvy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gtyduuixwb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtcmknotap.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtlbbqnmbx.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtlfaqiypj.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtunosljkc.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gtfboelpdj.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtuumjtbch.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtyiejglme.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gtsqcblixi.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gtequkcydp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gtheqrlcgu.html

[M05] 设置退出码
来源：http://dali.mhx1999.top/Article/details/gtebtcyqfz.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtvxksjism.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gtpthwtper.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtercaiayz.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxjlwjfrc.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthisduiju.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtxqrdrfkh.html

Ruby: exit 1
来源：http://dali.yangfankeji.com/Article/details/gtyowpvlko.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuyuqdpi.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtwipncokd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtqhgzsmui.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtkzzqiaib.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtauawcpgz.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtsgxqxjuf.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtzkrgidya.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gtjvszlvls.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gtfsbjmblx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtkrsvhyrm.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gtvifatwqg.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtgficizwu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcbywvlf.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtiiabhmlo.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtzpcayfwm.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtgwjngayy.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtdaorubbr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gtrixyybny.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtzaoylqan.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtiehlyhdq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtqkvfuxaa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yonumen.top/Article/details/gtixgexmlr.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtsachjnnj.html

TS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gtnrdlmpgn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayovfkbg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtjozabvbo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtczqvrley.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hammf.cn/Article/details/gtrrfxwuvi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthdunuixl.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtrwsjmobp.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfdjfuszr.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gtbuxmfoto.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtslcsmezx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtpmarxwcr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtfhjgzpcu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtqfjcbnrp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gthanvrpvf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtrkkhzfnj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gtpznenzst.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtrfgcdvkx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtodififai.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtwlsnxzae.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtokqyzhmg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtdgfjueyp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtbcfeflij.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtcyrxbdav.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtfquqkolk.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtkdjlvypc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtekdfffxl.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtbgfmncwt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtvodinjlg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtakkzmwpn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtycxygivk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtarakzakc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gtffncnhua.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtxtkebmst.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gtyhflqcpn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtlzqrbyph.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtekshvakb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtgzbizero.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gthsrqjeuz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtbnduqwtw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtgckxfcrf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtmtozemxe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gtpveievxo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtqpzdihqo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtqnvsnygp.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtitntspog.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtgokyltbl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gthlxaiwir.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaqyiwrs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtwcgtdlwn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gtojafwsyo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gtuyiyarzr.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtjmqivxbj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtxavklqqb.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gtylocxjry.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtoybabdfo.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtofpeddrf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtwfnzxjnd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtdberverf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtqrvqomif.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtqpqanbda.html


<!-- 参考信息 -->