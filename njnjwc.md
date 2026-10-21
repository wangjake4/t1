代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.9152youxi.cn/Article/details/gtkufljxtm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yj202588.top/Article/details/gthxbxwcul.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zycfv.cn/Article/details/gtaoctrniz.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gttbmtqbei.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gtdzbbtgiw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yonumen.top/Article/details/gtqztlqesi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gtxaxgyzwu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtphdulbma.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtrltwvgfm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangdashe.top/Article/details/gtjfoxmcwh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.guannengcc.top/Article/details/gtxphiytjy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvjhzbevb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbhznrhlz.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtuhbfjdyq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtcnurnnbz.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gtgzcnoxjg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtmceyuezk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtvuqnurxn.html

JS:   JSON.stringify(obj)
来源：http://dali.gotoacloud.top/Article/details/gtvnpxbkij.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gthyswzvjt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gtqjmayiyf.html

Go:   json.Marshal(obj)
来源：http://dali.sysykeji.top/Article/details/gtsacdiukr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtmhjmnwuc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtzppmescs.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtfewagyar.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghlshqdo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pycfn.com/Article/details/gtadzjhpqv.html

JS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gtuzzspglh.html

TS:   JSON.parse(s)
来源：http://dali.zhijiandao.cn/Article/details/gtseittbsd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yuxming.cn/Article/details/gtcrzaptxt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ivvv.top/Article/details/gtfexvzmcd.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtmdofepmn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.0kj1m.cn/Article/details/gtjpvwpbww.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gtldxnrrhp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hysaishi.cn/Article/details/gtihkqrdgl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtwpzpznfx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtgleudqas.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtpebfivfb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtpwigadly.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxffnzqo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtuoqknpso.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtbbnofhwb.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gtghfdknny.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtlkpblqac.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuanzhike.top/Article/details/gtynqhlely.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtgipououz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtpqzssaes.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gtvtytdvtp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.vqdsnc.cn/Article/details/gtlmckclhh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtkopvbart.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtvbajmpqx.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtvezlnmhn.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtkrzkxecy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gttjqbdbls.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtvypmtwmf.html

TS:   structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkuhltgr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtjyilpksn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gtjzcseyfk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbsvnyls.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gtygnoifla.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gtmgocivah.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtomtrjvkb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangdashe.top/Article/details/gtnzwzfmvy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtohsseodz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmiltflf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gtjqzptxph.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtsyyqcobf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtxchkcqpg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtgnaqqgxp.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtaehqhbuh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtuwvtliyp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtyvggmujo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtyqmswcvl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtrikzhacn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtolrdxlhe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gtalgzerbg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtmdfkfdpt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtvtmzhabm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gtrlmzufcr.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtfewchxcn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtwfoxelof.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gtdlrlrvnp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.c1oappe.top/Article/details/gtxnifnvms.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gtixofxztn.html

Go:   encoding/gob
来源：http://dali.c1oappe.top/Article/details/gtnypaeevp.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtyoaaagan.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfxsexpn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtelckflkq.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gtsvatwhfp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnpulzjp.html

[L01] 发送 GET 请求
来源：http://dali.yangfankeji.com/Article/details/gthjyqcszv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtppyuszie.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gttxiqgmhs.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtwdnqqwsb.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtcymooaqe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtypxfrxey.html

Go:   resp, err := http.Get(url)
来源：http://dali.redwolf501.top/Article/details/gtafkvhmbz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtvxmncfke.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shuidangran.top/Article/details/gtolttzdtu.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtotfhfvlh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gtgtgbhghe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gttisdnhfr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtoeakrvxf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtzgnefqqj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gtgbnxoabl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtdwfysvdd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtmvmbwffy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gteullzhet.html

[L03] 设置自定义请求头
来源：http://dali.gaohongyu789.top/Article/details/gtsesuhwtn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtvnqftqsp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgufenzy.top/Article/details/gtfmeyovmd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtnigdrilx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtejhxalju.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guowangkeji.top/Article/details/gtbsiagxjw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtyqihpwmq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtiryslybv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxinkj.top/Article/details/gtsmxubxpw.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtnioveuhn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gthdipwyfi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipznteej.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtfzsxpkux.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtiwufthyj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtiexqimsi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqubwzng.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.wangdashe.top/Article/details/gtqsaoahvg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtcfewskcr.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gtczfrrioj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pycfn.com/Article/details/gtubjcxgyk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gtbkxwcauo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gttbzudovq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtpzqjytbn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtowdxbtqd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtkqlznvrw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.svipenyu.cn/Article/details/gtzalhbppn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yongpay.top/Article/details/gtnxnmrlsn.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gtjbkxdarv.html

Py:   resp.json()
来源：http://dali.zdqjudy.top/Article/details/gthaawyrjw.html

PHP:  json_decode($body, true);
来源：http://dali.zhengqikj.top/Article/details/gtjexcvncz.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtynudrvid.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtvvqdumfs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtviefllhu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.c1oappe.top/Article/details/gtfpzxuzmk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtllfdzcsb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxqdobiz.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtblofzzco.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtiptycazt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtgtretwgk.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtwhkdscvz.html

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvicvrrt.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtqsopofza.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjthhauo.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gtjizfcvby.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gtiddhrhnn.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gthhrfkodh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtxplriqha.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtjcjeqwgs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenzaomai.com/Article/details/gtvysiszmx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtqsfqizsm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gtozqkxzml.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gtlhemcfag.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gtbvxzqwam.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtmcrhqwta.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaawonceu.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhixingplan.top/Article/details/gtewcmryze.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxgfhqzji.html

[M01] 读取命令行参数
来源：http://dali.redwolf501.top/Article/details/gthuxpohwk.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gtabvujcwp.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtyaizdelr.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtyezmcnvb.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtsmjpuwjm.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtunxeezwr.html

Go:   os.Args[1:]
来源：http://dali.cdnleiting.top/Article/details/gtdnwgmwbb.html

Ruby: ARGV
来源：http://dali.0kj1m.cn/Article/details/gtecysfikt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtfxajwkpp.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtjgrobdiq.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gtacbtekxz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtuthakfqo.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtleczkfjt.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtvmvlmzlk.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtepludkgz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gtsswdogxw.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gtckklpjer.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtqesbvvnj.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gtdnhxxawv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtydovkokj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.havefunace.top/Article/details/gtmwdnawve.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtxkvhiewc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtrmdjickt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daxiang520.top/Article/details/gtbodsbavl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtpuraxxvq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtfvweeopa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sufxvd.cn/Article/details/gtmcnnlgdh.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtaycxcjdn.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtdfeahqgc.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtgpngynfv.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtjqoxacke.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtmupxeofb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtagoyiqqa.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtnryoldgq.html

Ruby: Dir.pwd
来源：http://dali.redwolf501.top/Article/details/gttuswoixi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtljycorxo.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtbcqdrkws.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzvlktum.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtwaxdjpvc.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtjjaiinry.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gthpsfcddf.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtupsbhxgp.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gtboosaews.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtcwotonwm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtpqeleqva.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gteadgdhnd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoswospno.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtxhejgrrs.html

JS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gthzxzjejx.html

TS:   console.error("err")
来源：http://dali.sxryk.cn/Article/details/gtgpiidood.html

Java: System.err.println("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsyptwahg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtuawbycho.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gtjuatnedi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtkagxlljl.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtullshzsb.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtkboyruhn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoendqhke.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtkocpgqlv.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtqpsacxpu.html

Java: public static void main(String[] args)
来源：http://dali.chenlongwang.top/Article/details/gtuqnigeqi.html

Go:   func main()
来源：http://dali.xylfe.cn/Article/details/gtkkpcpgrg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gtowtuxeue.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gtotkjubkd.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtkvzntkau.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtxogokghz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtmybdeofs.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtqfffcucu.html

TS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtfiqtivkn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtilkvuilr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxemaxbqy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtigqduzrw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gtvszmbjbr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzmmlzcjd.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiodacjo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgdmgtnfd.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtqwzabksr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtjhepxmxp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtryambokq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtjpktbzpx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gthukkzuod.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtpdnyrtqf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtvphxtgps.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gthnxgwikp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtewryzhbz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gtgwdhxjuk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtzbnlpiek.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtixrxdmpt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtzxsytxpp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtviiyriya.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtujncobwm.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gthqflqtjy.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtjwzecrwi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenlongwang.top/Article/details/gtvhnkxpwn.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtrafyybfj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvsfxydq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gtehdzswut.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gteoqmfmbr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtxfbtiekb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtdgwukjdi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtyutnokov.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cqqwz.cn/Article/details/gtlqmjreeu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sysykeji.top/Article/details/gtarbynuap.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtebosnqor.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtbgijpwet.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtiwnhiqpj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtaisftemo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtedjnbt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtqntgaogk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.daxiang520.top/Article/details/gtwwuqdieo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gtbeiudtii.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtcbnnpbee.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtkqjuktfe.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtnztczqgn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtdyafcosz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtbdvymvqd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtpoczoqmx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gtkhfhevxh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gthqtraixy.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtfylhjkkr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtctljchob.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gthclpqhmp.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtvgqmcigz.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtffvibvdx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtsmpuscui.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtyvwnxqzm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtyejljitf.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gteilzvlev.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtyomqbpgz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtnaskicaq.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtbcwzekqg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gtetlqaman.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtrfkpgxhc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtebaovfrv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtqkyufdlz.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gtxxtccaes.html


<!-- 参考信息 -->