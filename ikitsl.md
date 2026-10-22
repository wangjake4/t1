代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fengsongda.top/Article/details/gtsxgxagsw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtvusrsoyg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtpminolwn.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gtjauwygie.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.feifeiyinyue.top/Article/details/gtxjghhgij.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gtcxjezxoi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gttferuuhi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sxryk.cn/Article/details/gtxgcfzbfr.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtcfuruwka.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtufbjorrz.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtrpuceuxz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeyzwuiy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtvdsxdche.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gtpalstsiv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtgikrypwc.html

[K01] 对象转 JSON 字符串
来源：http://dali.dianchejie.cn/Article/details/gtibggyrgs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtgesvcnzf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtcjjqvchu.html

JS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gtzubxpbpc.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtotvtxuxn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.mhx1999.top/Article/details/gtsoqrxfsp.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtzghijzev.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtudexlbdk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zycfv.cn/Article/details/gtelfwwvlc.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtkgmcnunn.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gtrpjvgiah.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzbdpjvw.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtudxxrkyz.html

TS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gtwsusrwpy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtkkfxmwok.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gtoxuutexy.html

Ruby: JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtjekjguvr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gtixzcqkco.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gthghawzds.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtyvbuzmff.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtijcnqbhi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gtjznaxeig.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtizvlrqul.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.bjfxy.top/Article/details/gtssyncqco.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtcpagaaqm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtajylczfi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.316326.xyz/Article/details/gtgicpnbyk.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwgivwgr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gtqnfniqnd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyejdnrlm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gthopsmkoq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtjdmowriz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ivvv.top/Article/details/gtyrugwqwx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gtapjuhccq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtyxajswwp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.c1oappe.top/Article/details/gtgljmhdlh.html

[K05] 深拷贝对象
来源：http://dali.xinyue.icu/Article/details/gtihuefuva.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtxdzmsnex.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zdqjudy.top/Article/details/gtprghzipq.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtjzkqverb.html

TS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtovrtuuuh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258888.top/Article/details/gtmafstxiy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gtlbgdrkax.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxxylixj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtsmmpkstp.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gtvijmbqdi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.smart0.xyz/Article/details/gtctmlrddg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jqgufenzy.top/Article/details/gtabalnafb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtpnfcgujr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtpfdervip.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.0kj1m.cn/Article/details/gtnvnavbkf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtsqqsipuq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtsmfqprej.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtiyajlsla.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gtpxslkctz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtritkdmlb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtxcfmrcjg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtharcibwn.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtkyaukxpf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtcqkqozox.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gthsfwavsm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tanke756.top/Article/details/gtbzclwlji.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtrqobyhdj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtkadvfmfc.html

Py:   pickle.dumps(obj)
来源：http://dali.316326.xyz/Article/details/gtvflnmziw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtvsbfnfpc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gtpzcjgssu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtizroqzcs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gtowbgrzqb.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gthlpfbjre.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gtmmecmokw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258.top/Article/details/gtvxghvgxo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteymxeqsj.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtxqdoqtzn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtoqsuwjwn.html

[L01] 发送 GET 请求
来源：http://dali.jqgufenzy.top/Article/details/gtemyxvuem.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtgebemcae.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pycfn.com/Article/details/gtjpccbxnu.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtkrvcamwa.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gtswkzrkvn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtpnwfszvl.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyikmejp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gtycwsnjon.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jqgufenzy.top/Article/details/gtldozejhw.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtkkjjkwth.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtmaenunyy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtljcxftnl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtwocdoxnt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gthxurckra.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pycfn.com/Article/details/gtvrwdorru.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtrzkataiy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gtxjondplk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cucudq.cn/Article/details/gtokghtdvm.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gtouzdwuon.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtrxtzgygc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tian-w.cn/Article/details/gtkgmonxfh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gtdvotdisw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtjrdxxidb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gtxylhokmu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtfffbdvhn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtjvgzijhp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjpbnzszm.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtcofubewm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258888.top/Article/details/gtmylrubbh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gthymkgayi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtlmznsoph.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtcegwyxmq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj202588.top/Article/details/gtgazliusk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gtjdxlxjne.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cheryme.top/Article/details/gtpmjkdelp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtwaiclguo.html

[L05] 上传文件（multipart）
来源：http://dali.chenzaomai.com/Article/details/gtmvssgndh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtaikgrhkg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtdpxvkijo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtqqzyvohc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtnvtlnlvt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtkrtgxkkg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtzcxfqpbq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtrksporgs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gtbvlualdo.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtfmdmjlzm.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtzycvloxu.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gtowhnvxkj.html

JS:   await resp.json()
来源：http://dali.cdnleiting.top/Article/details/gtfukspyqp.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtjginzeai.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtlevkhqdr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gtxtsdkmjc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtkkzygdnl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gthorlrvtp.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtdivdibhg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.quarkkingdee.top/Article/details/gtnzjcvyfa.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtgsafqozz.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtiyheauox.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtarcvmcdl.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtuzccziqg.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gtfbfigwth.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gthwgzafen.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtxedwxlll.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtdbdeouqj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtichkfkyu.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gtrctadtuy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtlrmciijb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gtlmremida.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzcnfmwz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gtogdbyvmc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtzqtksvyk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtjxhwfpks.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtllgpfuxk.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtcftswlht.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthloahvzy.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtdihzecaz.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbibqobgu.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gteevfqsko.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtzgsnuzpx.html

TS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtcbxwebfp.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtmncubpht.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtquptruiu.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtlsgsgjkb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtluggmlng.html

[M02] 读取环境变量
来源：http://dali.havefunace.top/Article/details/gtcybrdgmd.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gtzblgsqyl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtdpuruqxr.html

JS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtendatbhn.html

TS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtgjaddajl.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtzfzkynhb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtdihehnlw.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtuotrktpl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtomljwbkr.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtrqvtklnu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtjququifp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtqjjcstbt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gthtupjboi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtfihpmdon.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtdgwybwqz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yanxiufei.cn/Article/details/gtxkaihydx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtzkuxzjdc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtgcudxhvt.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gtzgdznkhu.html

Py:   os.getcwd()
来源：http://dali.yuxming.cn/Article/details/gtlahtuwfs.html

PHP:  getcwd();
来源：http://dali.gogol.net.cn/Article/details/gtkvgifenq.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gtvtiwjcoi.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gttpeidoei.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtptagbncy.html

Go:   os.Getwd()
来源：http://dali.ehwqpu.com/Article/details/gtlmdttxbx.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gtzvvdyfqv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtnrjoigyd.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtxjzxvoct.html

Py:   sys.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtuyanodfn.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtyoyvtlfz.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gteljfotqr.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtuwpznnji.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvefiwtdk.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtlfqangmq.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtunbgwsmf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtwvgkwgjv.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtxwchoenz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtgvjnswkd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtfvnnbljm.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gttaisjstg.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtpcuwnxxz.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtcqqamvxn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtknzxfuvf.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gtycovfwge.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtjcjmihkd.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtdmipnxlh.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtdslgrzhx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtrenhmagn.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtkznznopn.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtmeqqcltk.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gtfstckbou.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtidnravmc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.316326.xyz/Article/details/gtxdlextyw.html

C#:   static void Main(string[] args)
来源：http://dali.hywenlv.cn/Article/details/gtanyanhxu.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gttozvqeru.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtjcvinwnb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtzerpquwp.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtnstlyhrp.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtekbqtlxr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gtkstbhycb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtinsvoupq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtvobowhmw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtirdbjzbj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnozchxxt.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtyhstccgv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgolrlrer.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsvbobhr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtypynmuzo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtaylwkjqj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtnvugvpaa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtpoqfqujs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtcofcboau.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtzgrxpzaj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtbvlbjrxa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtcltkneud.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtsnwnvoxt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gtmnnfeatf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gtadsagyvq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gthmtypzab.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gtaxpoqjvi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtgmwjgiha.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gttbypcehb.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtghnlqnhn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gteghktviz.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gtcxkdjvvu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtcmqozpoo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtkslzqmrb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtgmcvospp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtsruialjt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtnftozjtl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtfuqbxyii.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gtevwwjlgv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtusgapjro.html

[N04] 斐波那契数列
来源：http://dali.yj202588.top/Article/details/gtvujsnara.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtbshhflkh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtfyaoddsk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtpkluvofx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtcxyjkhxe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtojoyagqj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtusqcbgru.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtzihhaqfw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtnjaektce.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtpcflcsfu.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtspjyrutf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gtntdzcvdg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtmsmgpkkd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtrsiygifh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtkvlllilq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtgzsaeroa.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gturnhgrmz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtsvgjpioa.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtasbeuvtj.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtvfmfmafy.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gtfurgkuhk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtyiepdilw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywvrisuh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtuzgwgiew.html

Go:   // 双指针从两端比较
来源：http://dali.dianchejie.cn/Article/details/gtxxvxkrbf.html

Ruby: s == s.reverse
来源：http://dali.nwbrower.top/Article/details/gtpkgfhyxh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gttaoknflp.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtmpjmyweg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtkeujxyzq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtpcgsinel.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenjidiqi.icu/Article/details/gtzvaqzwyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtzdigqwoo.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtyaxerxel.html


<!-- 参考信息 -->