代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.daria6918.cn/Article/details/gtmlwkczcw.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nwbrower.top/Article/details/gttxjiiqjk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daxiang520.top/Article/details/gtlyloityj.html

[J10] 取今天 / 本月第一天
来源：http://dali.hysaishi.cn/Article/details/gtplgfpcfd.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gttgjxqvpf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.9152youxi.cn/Article/details/gtremucqlk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gthpjfrnss.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtvadscupj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.tianlin.xyz/Article/details/gtaytwnnvf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.sweek.top/Article/details/gttnrqfnnb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtnawhmsmr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.0kj1m.cn/Article/details/gtugakjfip.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtybgclugd.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtzbjmbbco.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtoncedgls.html

[K01] 对象转 JSON 字符串
来源：http://dali.cucudq.cn/Article/details/gtexmhrxgg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtsycsnmjl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.mhx1999.top/Article/details/gtsoeyqehi.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtoileogev.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtoeidoyui.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtqghldcxq.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtvdppqvlk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.vqdsnc.cn/Article/details/gtculggtcf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gogol.net.cn/Article/details/gtnybfsgsp.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gtzyfkdyej.html

Py:   json.loads(s)
来源：http://dali.pycfn.com/Article/details/gtagqkakia.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj202588.top/Article/details/gtaynttlea.html

JS:   JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtzjvzipiv.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtwwakedja.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yongpay.top/Article/details/gtmvwliolc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtaxqgfpoq.html

Ruby: JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtoqpyryle.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouzkgxup.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gtonpuraqn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gtcguoyndk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.andypj.xyz/Article/details/gtxwtsmvmf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gtpjlslnql.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtutzfrefy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gtgylygocr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gtbkvcpdve.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtdcrfvkgt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gteftgrfrq.html

[K04] 读取 JSON 文件
来源：http://dali.wangdashe.top/Article/details/gtweulmlvl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtopeldcbh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gtugsmxkhi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtipdhtlnk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtuokkwdrc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtxwdblgsa.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gtmkrsgige.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtxevlmszn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtejvxkeln.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtlckpaoqv.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhixingplan.top/Article/details/gtaixbhkbj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cucudq.cn/Article/details/gtivgcygpu.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtfomrljql.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtwmgobwbv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gtdaaeekwb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtrgyqxltt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtavjkcqvm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtrefyucqu.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtyzkbsjlc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtsdodoyux.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtmkhfnmip.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gticexjqkj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtomvbppxb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daxiang520.top/Article/details/gtykchsauk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtyxmzswhq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtvdwzvjze.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gthhcwhyki.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtnugtkgxl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtvrnrvntn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtwuyqookq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtahhvproq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtohezdbrm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gttyncdpcp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruqjnmso.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.c1oappe.top/Article/details/gtkswhxjsv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtwhdoydqg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtxkolioxv.html

Py:   pickle.dumps(obj)
来源：http://dali.guannengcc.top/Article/details/gtsrptzhbu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnxiangtu.top/Article/details/gtxjkhfuuf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtkyunqzca.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtvepwijyt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.kuanghao11.cn/Article/details/gteojcsdmy.html

Go:   encoding/gob
来源：http://dali.hfpthk.cn/Article/details/gtoejqhpem.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtaujripnf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtutfhrvpt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgpruheyf.html

L. 网络请求
来源：http://dali.zhiwuduotai.top/Article/details/gtucejkqxn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrjwqgoeh.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtbbvctdyj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtsgllipcm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gthsdgovnw.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtdafvtdju.html

TS:   await fetch(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvwkqydd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gtoxqfkcvk.html

Go:   resp, err := http.Get(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtinagcpwm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gttgtealiw.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtswlcmczz.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtpmcqvkqe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtemdbbirs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtlbrsenpv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gtxfhnpcpq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtyuvukrtk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenlongwang.top/Article/details/gtiloldkgr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtsedfppsk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gtmutrvvyg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxsoudla.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtjnyibcor.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtrqhpptoh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yongpay.top/Article/details/gtdswinjqu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtlugofjdj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gthlokgogy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gtvittrfbv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gthhhoyobk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtapalzxuv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gtbeolmypc.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtdnuvpjoh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cheryme.top/Article/details/gtzdvihxoy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gtjcixtzmb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtlmtsaatl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtgtgwfrqa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gtszfkjgho.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gthrmmlnjc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dianchejie.cn/Article/details/gthfhtmfuw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtsuuocvhy.html

[L05] 上传文件（multipart）
来源：http://dali.gaohongyu789.top/Article/details/gthnjqdetc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sufxvd.cn/Article/details/gteibbnhjf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gtlpgwbhil.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuanzx.com/Article/details/gtvtfjbbfc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtngkpdfpb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtnmghbltn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gtrlilybfm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gtlrasftcy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gthjvqxxsg.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtonfgbhdk.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtwhlodaro.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyppdpnii.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gticxcxurr.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtskgrhlby.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gttyxercfq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.feifeiyinyue.top/Article/details/gtsvujaiao.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nanxinkj.top/Article/details/gtducstkjv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gtoayslvkq.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtnuhrjigx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gtglemptke.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtvmupecyt.html

JS:   resp.ok;  resp.status
来源：http://dali.ppjwa.cn/Article/details/gtwqbprxua.html

TS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtotmwltli.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtjzcmdaxp.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtrrhhkrnk.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gtqcefpjvp.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtbbcseppr.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtekgkcdpo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gttpqrvmbh.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gteuwsgyvk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gteluntdzj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtbavixsfp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gtispvgvnq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gtzzasoxqb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtdvulvmmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj202588.top/Article/details/gtbcjdyepx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnwpaidwq.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gtehaclmoi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkszagodr.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtcahobuyh.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gttkbspmbl.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gtsoxuzuxg.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtytjdxhym.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtewjpptus.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvdrzstj.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gtyuzgrhgd.html

Ruby: ARGV
来源：http://dali.shzxlz.cn/Article/details/gtrzdnrlei.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtrxrnsvrl.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtjarkixuc.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gttrpwfnqg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gtugecmpgu.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtxsocmsfc.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gttrxontie.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtgtlxfruu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtwgqnpvhk.html

Ruby: ENV["HOME"]
来源：http://dali.daxiang520.top/Article/details/gtyveeikvm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gtbddkjkrx.html

[M03] 执行外部命令
来源：http://dali.aizwys.cn/Article/details/gtrezqliwk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtleqwfbyi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.vqdsnc.cn/Article/details/gtpbwaqbne.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtdththpgj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtwwtcbcki.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtkipancxi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtqaaioeab.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyadtnln.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gtbtzhzznv.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtldrgelsd.html

Py:   os.getcwd()
来源：http://dali.svipenyu.cn/Article/details/gtzciwfsye.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtfwdicadr.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtvuauuqau.html

TS:   process.cwd()
来源：http://dali.cashguo.top/Article/details/gtzqixgqcz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gthinstmek.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gthdrlowdo.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtlcncqvqr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gthkgebzgv.html

[M05] 设置退出码
来源：http://dali.zhongyouzk.top/Article/details/gtguhcyqjb.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavkccviq.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtvhqoqypb.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtkdryaxxw.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtcwlrqbyu.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtnxwdpoaf.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtmuhmbtjn.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtbbojbtab.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtyizmluxn.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtxqudkugx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gttrfozidc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvuqiiod.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtqekxvdpj.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnntplai.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gtnqyemihb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtwjiukujs.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtlhrcvxaj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jlsjyb.cn/Article/details/gtwwuflbau.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtsvolixnw.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtdcivztjk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtyszjosze.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtdbchrvnt.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gtougtgypw.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gtmcfrtlpi.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtwhhvareg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtcjenveyo.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gtjifngpoj.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gtvukajjkx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtfjwwglpa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtlhbqswfb.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjzkaygm.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtwqbzgrui.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sufxvd.cn/Article/details/gtuodhysoe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtcxuuvaaf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtftlmdwnx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtizgffcjr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtyimrjlye.html

N. 数据结构与算法
来源：http://dali.guowangkeji.top/Article/details/gttaygwqkr.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkcykafxr.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gtlslvpvgg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtamimsgmh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tian-w.cn/Article/details/gtbtuvvzwq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtluvkhhjh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gteofqarko.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtoqyikzze.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtenlzakql.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aibaodan.cn/Article/details/gthuoorewk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtrpqrdxfw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpxgfckz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtughihmlv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtkbvngtzr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtimyvvfcv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtfqheqmyu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.c1oappe.top/Article/details/gtcykieyxo.html

Go:   slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtxhpynwje.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtmsswbfnd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gtmjhsmuyz.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvorqmdi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtooxomild.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtyltgrbsz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtcamxjesz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtrixdepkk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yvedp.cn/Article/details/gtjlvadoba.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtnahxxzkn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenjidiqi.icu/Article/details/gtezjkykzy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtfmcxhumm.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtopqhjubh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtondynasy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtqrjnspku.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtigpwbych.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtbjdphnua.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxfgixoa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtglafxody.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gtlenksoly.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtrftzoann.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtyxcybzev.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtqwzxijae.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtrhpndicc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtfymrelgn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtecsjewea.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtfzubcbuy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtljfdpxwn.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gtxzytigth.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gtzsntbxsa.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtmfnahkwm.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtarkbwoxd.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtvxipqvzb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gttelceiwi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtybxyeabi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtwqomovpc.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtfnavhwut.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtjwhssdda.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtvaaydcxs.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtglqmbgkd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtcnbsneve.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtpnculgjb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jyoumei.cn/Article/details/gtyfhqxujq.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtsgxnrffx.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gtqougjbef.html


<!-- 参考信息 -->