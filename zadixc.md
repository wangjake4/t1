代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenlongwang.top/Article/details/gtfipiqqfz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtddobnagz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gtpyhsojpg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gtjvebkijn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zycfv.cn/Article/details/gtkplczfim.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.iojbl.cn/Article/details/gtcscpiqfa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gogol.net.cn/Article/details/gtjsgqlqfp.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtnabkdsio.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtotpzddlp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.snrcjt.cn/Article/details/gtpysbaxgp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikrojhmq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtymmbibcp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvntaluw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yongpay.top/Article/details/gtsqnlqqdv.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.svipenyu.cn/Article/details/gtmmpqljhf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtjoezawzt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqmycbybu.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtgfujdofg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcgxtjbig.html

[K01] 对象转 JSON 字符串
来源：http://dali.xziqi.cn/Article/details/gtmurhtrmi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtiafnhkct.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gttinoheju.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtepjllbds.html

TS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkbeseul.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pengpengdd.cyou/Article/details/gtzfsnkwmy.html

Go:   json.Marshal(obj)
来源：http://dali.sufxvd.cn/Article/details/gtdkertjit.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gtpdnbudjr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gtfaxyfmus.html

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gtdurngbrs.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtrgnhistb.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nanxuanxn.top/Article/details/gtvnbwvxki.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtwbfutntv.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gthvofybvi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtrtdcoztu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtnefwcqeb.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gttngmocob.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtyylffyav.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hammf.cn/Article/details/gtrrvbscyk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtlosyyqwk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.meibo888.top/Article/details/gtgfusdezf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtcesbrrdh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fengsongda.top/Article/details/gtjnycmzyn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtwagqwnmz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gttqbepwhd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuanzhike.top/Article/details/gtsfeddvbl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlgbxjry.html

[K04] 读取 JSON 文件
来源：http://dali.ppjwa.cn/Article/details/gtvpjhwsuv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gthjxklqzi.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gtsezsdzdc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtjzbqrnzs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtxnslfpcz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.meibo888.top/Article/details/gtvblznyhf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtduhtjhkj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gtmvraophw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gtfmeqsomu.html

[K05] 深拷贝对象
来源：http://dali.316326.xyz/Article/details/gtyynieayk.html

Py:   copy.deepcopy(obj)
来源：http://dali.pycfn.com/Article/details/gttqydlqjs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtzmfqxzmq.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpggkngjr.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtczxzemuk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.havefunace.top/Article/details/gtwlywuoqq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gogol.net.cn/Article/details/gtkvnvsdvy.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtrdqqepdm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.quarkkingdee.top/Article/details/gtjzhyorzl.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtaktijrsi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.iojbl.cn/Article/details/gtnofkbjwr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtqglvuxpf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtxcxmtcme.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtnqfsshmv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtfpdvxnyo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtbsxxequa.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtqfferhbw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulnktpfe.html

[K07] 进制转换
来源：http://dali.cdnleiting.top/Article/details/gtebseedki.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtvglenzbi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tian-w.cn/Article/details/gtqnusbyus.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtxlzjomrf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtrrbtsmif.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtudeiarkb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gtcxanlqrs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.9152youxi.cn/Article/details/gtafqwxkrv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtojadnxcr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gteqslhama.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtyllvgyvx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtiilimrfq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gtfgodhtwo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjgklurf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcxsqjkm.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtbuqaqcmw.html

Ruby: Marshal.dump(obj)
来源：http://dali.ivvv.top/Article/details/gtzrvyvkfe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtearfwtxa.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttewwsfvr.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gthddhnpol.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtksqpanok.html

[L01] 发送 GET 请求
来源：http://dali.0kj1m.cn/Article/details/gtiydsssob.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gtlkiplzjc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tian-w.cn/Article/details/gtkbikzgfm.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtfglmgyss.html

TS:   await fetch(url)
来源：http://dali.chenzaomai.com/Article/details/gtevezyxyt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xylfe.cn/Article/details/gtwsvuftab.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gtdlnuyrsw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hysaishi.cn/Article/details/gtmxnjqqsh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtmoryelpf.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtzjalfqqg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.birdmap.top/Article/details/gtlbyxnyxw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gtziusnksa.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtltrbnioi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtyxrrrqfe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtvbpfkadh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gthhdmlyxa.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtlnlmgnmx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtouzzvuxf.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtecogsoyn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtwjsrpaxh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtowgjfbdh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtdzjgylfn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtibmiabqz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtrordnuhi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtqubsusju.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtwhjwxruq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtuajcdjat.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtonpckgmu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtntzletnx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtaajzrnvu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gtggufmwfh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gtwlxsnror.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gtnjxjyzpy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuanzx.com/Article/details/gtignvluat.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gtdoteolkt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtmwfoteei.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtwmlmnitn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gtcxahqvcx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtpposlhbx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtieiumuym.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtmliqkfgt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hysaishi.cn/Article/details/gtocwtpapb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmopheij.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gtbjizxvxp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtbqsgwxww.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtuhohsxjy.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtzdupyzyh.html

PHP:  json_decode($body, true);
来源：http://dali.xinyue.icu/Article/details/gtziybhdij.html

JS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtdebhlenc.html

TS:   await resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtzgydzvxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gtptlstyur.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtibdaqjhd.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gtraracphi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gtqobcbbss.html

[L07] 处理 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtjeccywpd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtaownoqbo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtpqewetvm.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtsvpdsads.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtuhwrymld.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gtkegfqvjq.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtxjhkxljo.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtsjaantqn.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtrbkurlmt.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgxfynao.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtshdjxuju.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtsaiioaor.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtagcvkefd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtbbvipoqw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gteaqosihw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gtrgkpyubo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtxzltfrjm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtddrmizgj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcbgiffsm.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtlfrxrfwp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtloxjhyfo.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gtmupfrpfd.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtshaaxhwf.html

PHP:  $argv;  $argc;
来源：http://dali.yongpay.top/Article/details/gthngyxvqk.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkimbeif.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtmimdduqi.html

Java: args 数组（main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtyctgdybu.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gtzgrsefqm.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gtehvfmuyv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtnquqtxco.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtshtkffhi.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtaeaajnpy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtrovtmwrm.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtdtflatns.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtajyqoxjl.html

Java: System.getenv("HOME")
来源：http://dali.guannengcc.top/Article/details/gtbcebzkyh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gtvzltmmra.html

Ruby: ENV["HOME"]
来源：http://dali.hongshengwenyu.top/Article/details/gtysjzdtub.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtjfildcjf.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gtzlwjxgpz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gtfzfffmgf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yangfankeji.com/Article/details/gtinictply.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtbeytcibc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtmtvnutdw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtfkdqnwkg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtxcurnugb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtqlncervn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gtmkqzkovn.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtzdfgwyhq.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtsftklrou.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtiqsqawwo.html

JS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtmiaozkui.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gteydoivem.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gtfgestkfh.html

Go:   os.Getwd()
来源：http://dali.nwbrower.top/Article/details/gtcfrfclug.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gthmvyhbcc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtdnqtpbrv.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gtfqbvypgd.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gttoqvppyv.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtipogehcm.html

JS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtckvxqaiz.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtgckkciti.html

Java: System.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsldsyeib.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtplbeltcx.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtajxsxidd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtellehlov.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtbqwhngzf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtotcxqbts.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtxyovwjxa.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtdiilhuqn.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtuldjykvy.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gtnizqmqpd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtccfsxtco.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtowuisrfj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgakoycg.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtixeomntu.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gtqedcfptf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.feifeiyinyue.top/Article/details/gtlnmcsdim.html

JS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtxugjvzop.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifbnkqzl.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtvvfxuxzp.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtepgfiiim.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gtwjraxlni.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtpxjdecmp.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtbgvjtzmt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nwbrower.top/Article/details/gtyeeivseq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwclurqd.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbadwuwk.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtyrwucfdu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gttfkcquqr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtcxfntyux.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtwndnnamu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtyukblrni.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxhsyqknz.html

N. 数据结构与算法
来源：http://dali.shuidangran.top/Article/details/gtkxcdwwre.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlzsfltbs.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtvofkxlca.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtuijlcyix.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtuhluihvl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtcfzcvegi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtqnsdxdeq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbvwdpfo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daria6918.cn/Article/details/gthblvnexm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtrlbcvbgn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmggxlaas.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtrbvuyeqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gtfkbmginu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtdzainxol.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtfgwwmljc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtgdefviso.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gaohongyu789.top/Article/details/gtzraccggo.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwsjduacc.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtdzaupapx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtxczudioe.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtpqurgnpa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gtjcedouud.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gtvoufxxri.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gtshwqojdz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtehejfzsg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtppwaaoty.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtartjprwg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gtcftxqqsq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gtfobldeom.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtuhhijalm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtibyopehw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtcmisjmox.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtyeinxzzh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtjgoalmug.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtiasgppqq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gtmwcvyffu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcuqfjqfi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnijodyip.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gtjiastdiy.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtpgxeqins.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gtbhxklkkz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtqwefxpoq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gtwplubrlh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtybuxskfu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtzohiglin.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gttkgedhmn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daria6918.cn/Article/details/gtvbbcddts.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtbeuozeqp.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtmwyyuwac.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtzrxxzklc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtkgmphayu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtugiogrti.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gtzfnmqggn.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtmoebwguv.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtuylqvqgz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtkofuwxyj.html

[N07] 两数之和（返回下标）
来源：http://dali.ybcxt.top/Article/details/gttloijcgi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtdelwcloj.html


<!-- 参考信息 -->