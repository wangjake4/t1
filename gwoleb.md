代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nanxinkj.top/Article/details/gtltdtmknt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cdnleiting.top/Article/details/gtnvyfmqoa.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gtigghuwvm.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gtitiyksnk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuanzhike.top/Article/details/gtrugklsmh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jiagoushi.top/Article/details/gtqegskugp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhongyouzk.top/Article/details/gtrxchxejv.html

[J10] 取今天 / 本月第一天
来源：http://dali.sweek.top/Article/details/gtjqmzzodf.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shuidangran.top/Article/details/gtzxrjrtnp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtvgaougey.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gtvvidrflx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtlreqnans.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gtvqqrjhfc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ivvv.top/Article/details/gtprhlxjfc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gtvfbsqkbt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtfyqtyklf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthdjlhnzr.html

K. JSON 与序列化
来源：http://dali.cdnleiting.top/Article/details/gtasfjklww.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcbbotbpk.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gtijkrzjhw.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxuanxn.top/Article/details/gtgfrvpmra.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gtzdmzrbyv.html

JS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gtatjmrafi.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtrmqhkbnt.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jiagoushi.top/Article/details/gtgdgscqdm.html

Go:   json.Marshal(obj)
来源：http://dali.xziqi.cn/Article/details/gtbthniact.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gtmaxyetkm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yangfankeji.com/Article/details/gtkrwbvzxo.html

[K02] JSON 字符串转对象
来源：http://dali.yuanzhike.top/Article/details/gtpivihswg.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvxoaqqoe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddrimalx.html

JS:   JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtconxfkdv.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtniiyenew.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtembvybsq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtfytsxvct.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtrloxxign.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gturtjscle.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtdlfvbjld.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtpzccrmkq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtqgxsrbpa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwqhbwipo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtppmgsyra.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hammf.cn/Article/details/gthkvhhtxh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nwbrower.top/Article/details/gtopnrvqdw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowvedyqw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gthuvglbvd.html

[K04] 读取 JSON 文件
来源：http://dali.cucudq.cn/Article/details/gtyuaapezj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtddvcffvu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxuanxn.top/Article/details/gtnekasxve.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtmkjvkjbr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtawfjbqme.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gtcdivpzhl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtmfzkqxns.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtzkeikjfb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvosvwwm.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhtymflf.html

Py:   copy.deepcopy(obj)
来源：http://dali.yuxming.cn/Article/details/gtpfnzyljp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtbpvdefma.html

JS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtyygmkval.html

TS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gttpeozpjd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtjymthpba.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.feifeiyinyue.top/Article/details/gtghlfwoyf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gtwapjwivg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hongshengwenyu.top/Article/details/gtgyzwmwth.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gtgkyocepb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtqmzgvaus.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shzxlz.cn/Article/details/gtuzqwkdcm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtbhpeybol.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtnqkybqmy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtexepsmbe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtwaobmgtk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtjuttqefk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtrvoobynz.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gthhfhoyjd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtocpfknnu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gtskmnabwe.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtxpfalina.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gtutdmocpr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gttlbrpmnn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gtzitbmakk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gtnnfrzikp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtrdmcpqrt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxinkj.top/Article/details/gtwwjmigou.html

Py:   pickle.dumps(obj)
来源：http://dali.sweek.top/Article/details/gtzmsbyvgr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gthrugydhg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtcziygkul.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtezazstnu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gtaoulshio.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gtqraiygjz.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtwwxvizgl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gttjudkgul.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlovuszlm.html

L. 网络请求
来源：http://dali.316326.xyz/Article/details/gtgmkfpgeu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqgqmglqh.html

[L01] 发送 GET 请求
来源：http://dali.xziqi.cn/Article/details/gtyrrrjutv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtooavzejc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gtjvvujegf.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtydcqxahw.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtgiisfkuz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtqcaeujjz.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258888.top/Article/details/gtudyjuwqi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gtvblmagli.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yueranfly.top/Article/details/gtpikojpen.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtfdkikvzc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtygqkprsl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.haohaochexian.top/Article/details/gtjazzsgzt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtndlwhltf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtcnfmmuzy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtpgkdzsgv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gthxikzzfe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtdlpwlmmp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gtlgevtdug.html

[L03] 设置自定义请求头
来源：http://dali.tanke756.top/Article/details/gtojvygxla.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenzaomai.com/Article/details/gtzqylrvau.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xinyue.icu/Article/details/gtxsycilky.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gttcyvrzqo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gttuvnhfgk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtwwyvrmvs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtzemiynyc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtjybqoztb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zdqjudy.top/Article/details/gtjnkrsqou.html

[L04] 设置超时
来源：http://dali.xuanzx.com/Article/details/gtokdinwow.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtmqwmsbtt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gttfboeclx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gtkynmestj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndvgwmze.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtbgulsxsi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtwuwkuihb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtdhxurcqx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258888.top/Article/details/gtqdpiwygo.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtcetyclbx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtbxvpudip.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.kuanghao11.cn/Article/details/gtdemikudg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtidbbleeh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtvitkgaxd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gtkiolaofb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtvspiyazc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtdyvnfomu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtvmfxuulf.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gthsukeehe.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtascxkwkm.html

PHP:  json_decode($body, true);
来源：http://dali.ybcxt.top/Article/details/gtsuysdefv.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtvmzhpbdk.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gtoediygub.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gtppykxqpz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaoaeltv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtlygiycuv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtnleqgdtt.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtmcfagsje.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tanke756.top/Article/details/gtnyythreg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shzxlz.cn/Article/details/gtxqpixmmc.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtnhsklhfo.html

TS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtzmpvhzay.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gtydlkiogv.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gtmlvdthfv.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtosjvjpwa.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gtzlmvurmi.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gtmtmwzhff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtjoliortn.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtqqsdxkgk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtniehelxf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtjbgqcejd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gttaamwdco.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zdqjudy.top/Article/details/gtyjgoowll.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtyrpcemdf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtsvwmcper.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttqzgvasc.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gtbtgpcvmu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgkkojquf.html

[M01] 读取命令行参数
来源：http://dali.nanxinkj.top/Article/details/gtyuqqfosl.html

Py:   sys.argv[1:]
来源：http://dali.yvedp.cn/Article/details/gtlbbuecuh.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gtkgjovbnz.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtzysqbyiy.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtaxymxmjl.html

Java: args 数组（main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gtmpcpqtnb.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtdzxfdibg.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqchlvek.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtjovokyqv.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtlswyfsgf.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtmgjeikte.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtglqtnwjw.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtrxbnchaj.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gttvqikppv.html

Java: System.getenv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtgvcduqri.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtepwuvnww.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gtkkmkcjzj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtwjlaacwr.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtepdmhabh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtgudgxvcc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gtcolzgbhn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtowmpmuyr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtudqbfvya.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtnnshzvyy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gtmdmgnffj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtbxhetftg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gthaultlfs.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gtkzsrifvi.html

Py:   os.getcwd()
来源：http://dali.quarkkingdee.top/Article/details/gtbdttwcrj.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtyditimnu.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gttspfceyi.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtxjumaais.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gtresprvur.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtgfjrnqke.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gtcxdpcxei.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gthplldage.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtjnoyugjs.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtmikvquqe.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtebhacafj.html

JS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtguyoqxmd.html

TS:   process.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtujcwxjao.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtbtcdnlkt.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttscxojxw.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtoxjrsuvz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtplsqixiy.html

[M06] 向标准错误输出
来源：http://dali.sxryk.cn/Article/details/gtmhgdzydc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtmkrwnwac.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtnmyvyvrm.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtuxnwkbgx.html

TS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtgsjcvhvh.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtlgrgozxf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtxssqkgne.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtvlfdcxrc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ybcxt.top/Article/details/gttaiqhmfp.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtlkqojxie.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gthoedyawm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhnoebhb.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtmvefoqoy.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtnqupviob.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gthvtywcht.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtirhyteys.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gtvvlryqnk.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvuidogu.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtrevoytin.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtlmcswmtc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.havefunace.top/Article/details/gtjjlbyurm.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtvqzvnykd.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtqqopfipn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gtukyjmujf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258888.top/Article/details/gtktjydnlf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.iojbl.cn/Article/details/gtsxqtfylv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtpihpilpp.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtltqxlsqa.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtatnbsfve.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfhbddooo.html

[N01] 二分查找（有序数组）
来源：http://dali.kuanghao11.cn/Article/details/gtwfqvjqhn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtrzibfgvy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtpaetxocz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtvopkvney.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtobqrlwrf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gttyfkdgmq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtihphqatp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtyqpklswo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtimjomntv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtirninsou.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtmhweffcn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtlcazjmow.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghqarhsy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gttsotyoxv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtfqmxdkir.html

Go:   slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtsjscwejx.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtrkznfeny.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gtszzhedkm.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtunvtfrhy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtycgfzjja.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtsuksrtne.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtmrtjxwkj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtblpodvca.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtzofqisnu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtmvgbcnlm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gtcblukirv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gttbmjedxt.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtvqqqcqwd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gtylufofvh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtqujfuxcn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gthprzkizf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtvvuwsijj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtkbtjozcx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtjiewejrf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtakxhwdnq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtzadlcyzj.html

[N05] 最大公约数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbuukmbr.html

Py:   math.gcd(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtvqqeawln.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtruetxoot.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gthyhyrdbj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtgtgxjqid.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtngzhcmya.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gthfsyigza.html

Ruby: a.gcd(b)
来源：http://dali.bjfxy.top/Article/details/gtajctseox.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gtsrzzbham.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtdahopfce.html

Py:   s == s[::-1]
来源：http://dali.fengsongda.top/Article/details/gtdwtlxlug.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtdfgeapbg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtxxfmaibq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtklhxiism.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtnjuymdcj.html

Go:   // 双指针从两端比较
来源：http://dali.hfpthk.cn/Article/details/gtwpwualfu.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtthrxoqfi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuanzx.com/Article/details/gtzvqnxgzp.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtnftlrwgr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gteblncevn.html


<!-- 参考信息 -->