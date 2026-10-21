代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangshuangyany.cn/Article/details/gtpvwjteef.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tanke756.top/Article/details/gtdqzgigke.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jqgufenzy.top/Article/details/gtvpminjko.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gtuhnhxpcu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gaohongyu789.top/Article/details/gtxlpwquwf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtoqrnhaxf.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aizwys.cn/Article/details/gtvvpabdkg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtmtpuobtc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hammf.cn/Article/details/gtjovinkre.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ybcxt.top/Article/details/gtumofcccq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.iojbl.cn/Article/details/gtomjwnixq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gttcidjhqa.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifojjqhg.html

K. JSON 与序列化
来源：http://dali.havefunace.top/Article/details/gtxfzqxgtv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtepwibzib.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gttfhacboi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtloxymhcg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.kuanghao11.cn/Article/details/gtromqzdxd.html

JS:   JSON.stringify(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtrescjinq.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtnkpthtiw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtqpqfqzav.html

Go:   json.Marshal(obj)
来源：http://dali.cheryme.top/Article/details/gtqfgkqnve.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shuidangran.top/Article/details/gtopdjjbeg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ehwqpu.com/Article/details/gtwzubkkaa.html

[K02] JSON 字符串转对象
来源：http://dali.tanke756.top/Article/details/gtlxonpaez.html

Py:   json.loads(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtghjudenq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xziqi.cn/Article/details/gtctlskdxi.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gtnyunsxox.html

TS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtufodnogp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhoulong.xyz/Article/details/gtbvhqmvjy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtquraucue.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtrqtjttwy.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sxryk.cn/Article/details/gtbuprtyhr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.pycfn.com/Article/details/gtaupprlzb.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqjrscrd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtdnftjioi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtfgnokhid.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jiagoushi.top/Article/details/gtiaqrzjis.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtclkwmjav.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.chenlongwang.top/Article/details/gtysqslcqr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtlrgtbzyr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ydzc1.top/Article/details/gtdeiegqvx.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtomutqbqm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jinqigufen.top/Article/details/gtgvkplrbz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtereavsij.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gtppituvvx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtcuirjhnf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gttwlxlwlz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nanxinkj.top/Article/details/gtwfrizapq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtnjtklxxl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj202588.top/Article/details/gtmmmcveeu.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gtitzteyjj.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj20258.top/Article/details/gtdlcvputj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gtdozynzlh.html

JS:   structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gtknsvwjcf.html

TS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcrutnokk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gthvadzfza.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtlhqujsqw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gtroxxoyaq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtijstqktz.html

[K06] 解析 URL 查询串
来源：http://dali.svipenyu.cn/Article/details/gtqbvbizrw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtcszwkqte.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtqwgmlqkx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gttqavifzb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tianlin.xyz/Article/details/gtlbfzwizy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtgmbygtbf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtmjwvlbqs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtpdbourvh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzzkzodj.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtgmqatidx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtnuwfmuuj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gtdhfxmnpu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtloqpiqqk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtfwanqvsh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtiupsfheu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gotoacloud.top/Article/details/gtiwsnvtvy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtmdavjgyt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtvoeqwgkl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtfxtdwbej.html

Py:   pickle.dumps(obj)
来源：http://dali.ydzc1.top/Article/details/gtwhdcckdh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tanke756.top/Article/details/gtxhvvrtzt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jianghu66.top/Article/details/gteluzjwsu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtptfesrml.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtavtfpyro.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gtzoakqkyb.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtspuexqdi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gttrpduqbw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvvwwhjsy.html

L. 网络请求
来源：http://dali.hnqzz.top/Article/details/gtbjkxqoux.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtbrugvmfg.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtpgotrdim.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cashguo.top/Article/details/gtyorcnqhs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gzhubu.top/Article/details/gtkcopqjku.html

JS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtbvivklwt.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtudklieej.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuanzhike.top/Article/details/gtcbuxbvub.html

Go:   resp, err := http.Get(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtubcanmjf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtxyxawpsp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtyhpngona.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtzktbmxfi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtanhbmqew.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtpbrcrpdv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtiqhgichn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtvekiydqa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtlesbnzds.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhiwuduotai.top/Article/details/gtzlztbrij.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.guannengcc.top/Article/details/gtuccoyxzs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtgwsdcfgs.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gtvlvrjilm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtvzdzcuas.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpuuptdr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtfidisyqe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtbmmjyagf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtnjespwkx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gtjmugtzff.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gtoziorfag.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcuruqrf.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtlhtmmvcl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.kuanghao11.cn/Article/details/gtbmncavzv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtqcvdlkdg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gtpswhjyac.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtfawwwkfi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtfscfzuor.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gtvblowyhg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenlongwang.top/Article/details/gtbzuueioz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pycfn.com/Article/details/gtdqltkjwa.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtmpwjghrs.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtujlbyohy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gtyoigkosd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtcumfmuls.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtyyzbnltx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gtxccmbszf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtwwonewop.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonkpmwpn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gttjfpgsan.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gtfvajzaur.html

Py:   resp.json()
来源：http://dali.wangdashe.top/Article/details/gtvsegcjry.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejizsuxe.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtysqxffmr.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtcxvxrhzc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtynxebkjs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gtywgzrsah.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gtmepnwqkr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gtehwfgjqz.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtevnyyqjs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtbfuwknok.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtioshkpuw.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gthuawtuff.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtmgojwpkc.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtdajprdom.html

Go:   resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gtrzgtuaux.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtvigvxphy.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtpafezirk.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtztnshkei.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtnwaegytj.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtpznmtrwv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtznufncrz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtmqhidgur.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cqqwz.cn/Article/details/gtinxoflda.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.birdmap.top/Article/details/gtznfuqhxb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guannengcc.top/Article/details/gtdonamwxp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtwhnsdhfc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gteawlqisr.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gtasteihwg.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzhdjzij.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtclggcxyf.html

Py:   sys.argv[1:]
来源：http://dali.sweek.top/Article/details/gtnierkzda.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtlpuxhzhr.html

JS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gtruyzqoof.html

TS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtktidxcdn.html

Java: args 数组（main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtxczzfcgh.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gtnhbimydx.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvwyovyx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gthojglgps.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtywakjrdq.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtaeohmoxr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtutxajcdi.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtbvcdyaxu.html

TS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtbgsyoeoe.html

Java: System.getenv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepnlpbwr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gtcbgybgtn.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtjnytobvi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtptvjcien.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtppddejge.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtgxhihuno.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtxtkjgqjc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtygvdotqn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtunwpnjfn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtimygctkj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtydmdonjn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gtvjfdnhin.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gtotihwjcw.html

[M04] 获取当前工作目录
来源：http://dali.quarkkingdee.top/Article/details/gteqfqkodr.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtrarvxasl.html

PHP:  getcwd();
来源：http://dali.zdqjudy.top/Article/details/gtjltrmbqk.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtwkrjqlnz.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtqkxctquw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.smart0.xyz/Article/details/gtudmtmeoy.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtyerqtdsg.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtqtdszqfv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtcdvnlptv.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtveewkqhn.html

Py:   sys.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtdstockul.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtdwhkhxrh.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtshkxjkvr.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtxzmeqgjc.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gthkwwjegv.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtpxlxosnt.html

Ruby: exit 1
来源：http://dali.zhiwuduotai.top/Article/details/gtbnzxpzoy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gtejdndkqo.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtelxftjah.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gtsvbkolpo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtvxghozdh.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtcvhswbht.html

TS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtdduknxxp.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gthvmoylui.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtnlnjgjsg.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtqzmuikkj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gtsokduobb.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtlzzgbnxm.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtmmtedwvm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtddbtflsp.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtuuipvxij.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtyqdiwknc.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gthswhejjf.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gtzppnzyxx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtgmttegxw.html

C#:   static void Main(string[] args)
来源：http://dali.pycfn.com/Article/details/gtgagzmgzh.html

[M08] 获取系统与运行时信息
来源：http://dali.dianchejie.cn/Article/details/gtljkxddrm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pycfn.com/Article/details/gtnfnikshw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangshuangyany.cn/Article/details/gtddxpsojj.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtxztmvrtw.html

TS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtolvxqddj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gtzqxcbklp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.smart0.xyz/Article/details/gtsjdavcth.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gttbsbjlma.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gtotgshedb.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxzyqqlwx.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtfxrxbscy.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbhoqdspu.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtxjfaaxyx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtwsfuqgnz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtqjhywwtj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtkootvtll.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtophryqfk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtlrhjakty.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gthtvadxcn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gthovyffxq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtbieaclsn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtnbouuvhu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gthtrtvdoc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtedliqoko.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtmukbuijz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtuzpwxxyr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtmqiavcmh.html

Go:   slices.Sort(arr)
来源：http://dali.daria6918.cn/Article/details/gtibzqqhfg.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gttfperkbk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcqzkqkw.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gttwwsracw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtaecxfrsc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gthchbvnzd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gttzsbagzg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtlsvsswlf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtxggljbrd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtlksigxki.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gttqgxyxqt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtekwggbkz.html

[N04] 斐波那契数列
来源：http://dali.dianchejie.cn/Article/details/gtkmtignkq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtarhmfulh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtkfrqpulr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuowvrpw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtxjjomqky.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtgpyyyqoq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtoibswvve.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gthqnippms.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtqcxjnqjm.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtlaciuroa.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gttbsathkh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gtzaawudqi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtdtqxkiea.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtjykeufbs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gtsdofmxhg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gtjumjmuor.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtyveoinog.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtujzaroxf.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtwfqarcjn.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gthgdbceqv.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtyoooknlp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeisqtcn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtxvtghgiz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigufen.top/Article/details/gtgladykma.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtsuemxvxy.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gtwmhgzpnt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gtjxojudbc.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtixfoacqg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.kuanghao11.cn/Article/details/gttbaoyiad.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtrmtzsqgx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hfpthk.cn/Article/details/gtlekoiafy.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gteseybrce.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtgzetnzsd.html


<!-- 参考信息 -->