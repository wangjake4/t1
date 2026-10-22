代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbopkvjdf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtotyqvgbz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yvedp.cn/Article/details/gthcvbevqy.html

[J10] 取今天 / 本月第一天
来源：http://dali.zycfv.cn/Article/details/gtmujfdtfr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtljbrfkqr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfenopgm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jyoumei.cn/Article/details/gttvcdcvsb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtczwzqlje.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdthvqjiz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtpsybfgro.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gtayzpbjpe.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhoulong.xyz/Article/details/gtlkjzeddk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuoexlavl.html

K. JSON 与序列化
来源：http://dali.yonumen.top/Article/details/gtwkwllftd.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsvquknjt.html

[K01] 对象转 JSON 字符串
来源：http://dali.gotoacloud.top/Article/details/gtvhnmqfbn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gttaslhkut.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtasbrbbus.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtouagandf.html

TS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthyfchpzy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtdqwlxskm.html

Go:   json.Marshal(obj)
来源：http://dali.yj20258888.top/Article/details/gtewvphmwd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhijiandao.cn/Article/details/gtbtiqynum.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hfpthk.cn/Article/details/gthxogbgbw.html

[K02] JSON 字符串转对象
来源：http://dali.fzhhl.top/Article/details/gtddwtagwy.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfhubbbld.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xinyue.icu/Article/details/gtjvixvost.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gtktataqaf.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtmipgelhv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gthgvwwgah.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gteyctijbk.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtjpxewnxq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtrfkegwhz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tianlin.xyz/Article/details/gtvtpjrxnv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ivvv.top/Article/details/gtehzycscz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gtgpfalggr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gtqqryckbe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtulwmxgdy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gtaqfayvmn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhixingplan.top/Article/details/gtncgyfscb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrqvrfjeq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gtakuvhkhs.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtniqutmcf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.svipenyu.cn/Article/details/gtnxxenohk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.guannengcc.top/Article/details/gtpqxhqbdb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtcummejvw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xziqi.cn/Article/details/gtqhtvsjod.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.havefunace.top/Article/details/gtthnxuobt.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yonumen.top/Article/details/gtlztganmb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtvnhglfhe.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtwldafdsh.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtwlwhvbjg.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdalgbqhj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gtlefdmyko.html

JS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtkpyhrppi.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtsudfsnyg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yongpay.top/Article/details/gtrfsgfhlm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtcifcvboj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtvheilrsw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhoulong.xyz/Article/details/gtnekxmdrm.html

[K06] 解析 URL 查询串
来源：http://dali.hammf.cn/Article/details/gtqcxblzak.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtgmiexcuv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtvyedxcll.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtauvzecnm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gtjonknmth.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtrdfchpkv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtlmgocqxo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtirfeembv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtkldmqfjv.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtjevhekfj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtsrvduvhz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtrjusoacn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtywtspvbe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtypqzpjio.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtystqgtdg.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.9152youxi.cn/Article/details/gtufndbztu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnxiangtu.top/Article/details/gtfffflokr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cashguo.top/Article/details/gttzqwoxfz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtqmowtihd.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtlnwjyujf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fengsongda.top/Article/details/gtdnsmjpoh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrwkdsmn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xinyue.icu/Article/details/gtgjczsdds.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtzibulwlf.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtuouridpg.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gtjtgbfnpj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtwrtpophw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzeqsyuon.html

L. 网络请求
来源：http://dali.jinqigufen.top/Article/details/gtyjgnjktr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttiipjqpg.html

[L01] 发送 GET 请求
来源：http://dali.pengpengdd.cyou/Article/details/gtivjrqxpl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtawwnzdbk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtdkmbssqp.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtsdeobksf.html

TS:   await fetch(url)
来源：http://dali.zhengqikj.top/Article/details/gtyuuhzeky.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gtbpoovoop.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtgozmwzgs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gtcjacynzd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtaehnidqg.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtwqfsfjdy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gtumhqyfgz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnshbavq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gtaaserbnd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yvedp.cn/Article/details/gtekfdnfgq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gteyyvzgch.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtxyytwvay.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtuyaqqlye.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtripjmrix.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gtupzypbuc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yongpay.top/Article/details/gtaehnutfo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtxegodxiw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gtisqzsivu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gtdxauzvjx.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gtehjovzfm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.feifeiyinyue.top/Article/details/gtsqwcfsev.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tian-w.cn/Article/details/gtdqsflndb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pycfn.com/Article/details/gthagwpqru.html

[L04] 设置超时
来源：http://dali.ivvv.top/Article/details/gtfbaxzuwi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cdnleiting.top/Article/details/gterdpszzs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtbbcogygc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtwhjaylmg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtfjioczzp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtknhyqocn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gtuvftbnig.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shzxlz.cn/Article/details/gtqpqsynja.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gtcgtfbmwm.html

[L05] 上传文件（multipart）
来源：http://dali.pycfn.com/Article/details/gtknwycjgw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gtiececxvc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gtvgtjentn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gtdeywklew.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtljqihxzc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtfnmyqmdu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gtryybpbqp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhoulong.xyz/Article/details/gtpthcaghj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtmactbrzl.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtucoaomkr.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtapedrxnv.html

PHP:  json_decode($body, true);
来源：http://dali.jianghu66.top/Article/details/gtojvuzoui.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtkkbidlzy.html

TS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtcnqsaavm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.meibo888.top/Article/details/gtyupnudlq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.mhx1999.top/Article/details/gtacitqefx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtygjpzljq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtyylimedm.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gtrgixjrzr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gtsxortxvs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gtqdgltwne.html

JS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gtdhrzytuz.html

TS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtlkfcwrnj.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtrxwukjgd.html

Go:   resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtjycwukof.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtiutjwnkj.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gthdtfuijt.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoyzijre.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gttixdtmnh.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtuooowosa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtmgevjchr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtbpszvbpl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gtsgdplqhc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtjnsvgzrg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtnesjllhx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gtgdtyjmfd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlzrypnke.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidyofiwd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwjvpjphk.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtkbopvjli.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gtuzutwqvp.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtazjztseg.html

JS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtfhxqlmxb.html

TS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtzycxthbz.html

Java: args 数组（main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtktdpykmq.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtyqemmlke.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gtivssrrzd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gtxpfyxmtf.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtgzjognrp.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtclmqlhtb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtweqzimqp.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtrudnkjxz.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtxyitvoja.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtieuwqoqs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtjgjazvvp.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gttabeajnw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtfhvlppsh.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gthnpgdipb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtqyncsiku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhoulong.xyz/Article/details/gtiajmabhh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gtgfldglto.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtynuorhcz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtkftyzrdz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtjhtcgqae.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtflqaatzv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtdoojzxxb.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gtdlwzhvha.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtnhycxkvj.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtcblmupjg.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtwahwwccc.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtamrevalj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gtuqomkykm.html

Go:   os.Getwd()
来源：http://dali.zhixingplan.top/Article/details/gtaianjgzf.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtsxzrqcmw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtosrvhawa.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtiomqcvij.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtkaqbsdxt.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtzfxmawgc.html

JS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtyzxwyitk.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtgwfuveyo.html

Java: System.exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtvetaqgaq.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtcjfacgif.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtbxcpxlje.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtlxtqewjp.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gtvvwqtkwn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtlfwqdrky.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gttqxmnbxs.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtckyowuff.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtjwmoykir.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtrixcoggf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtegpyvuvt.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtlwdzmoum.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtizynupzs.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtwminzyrb.html

Py:   if __name__ == "__main__":
来源：http://dali.havefunace.top/Article/details/gtzraowbhu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtktayicaa.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtvezrpujy.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtycrkvjgq.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtlquhnfrg.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtfzvfbwai.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gtlnglcieo.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gtblmnzbmo.html

[M08] 获取系统与运行时信息
来源：http://dali.aibaodan.cn/Article/details/gtscpimwgm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhengqikj.top/Article/details/gtkfgddoll.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gtlpcsojtv.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtjyssyvzx.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtyryhinbw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtfjkrakgq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ivvv.top/Article/details/gtfjuthmuy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtjcusbivu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gttgwwkhwy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtumxqmspi.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtnuzkuqou.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtufrqokvb.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtqlomdemp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtrlqniuzf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtonnevwom.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gthargaqby.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtebrwtyuf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gthdiscfgu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtnecemidg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtewgvsihw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtnecnimzz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gtznmrrbeg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtnhsvsxea.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gttbmwkbpb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtapstnxyo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtezpckdxh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtpwppflew.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtwvywgyyx.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtwcvoygxu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gthaeyestj.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gtfckbvdsb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtmhxivnhi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gteduzeuwt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtfoqqkinc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtjhsvitvh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtcyqxxsxl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtvfcdczby.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gthbzhnnyq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gtqqgfqdvx.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gtipxekfzr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtwkushenr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtwwknfycp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtnypqeqyb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtqyrbbbfh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gttozmsivi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtfmogysly.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtxzpxpqmf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtktxmknos.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtjvssjxmg.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtknmjuxea.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtdxjcafjn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfscxrqk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsclybbpe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtacoioaow.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gtwfttbpjy.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtserkdsbg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtmcnlxvln.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gtzifsttsk.html

Py:   s == s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtcgsisezr.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtwegmwqri.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtutqdaiin.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtlekfozaf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtcukomfom.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtrxctjbcg.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtdkvummrv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtzpxbwhtj.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtpjyreiwl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gtvtyjrchu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtyrfbtopd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gthweifome.html

TS:   // 手写 Map<string, number>
来源：http://dali.hysaishi.cn/Article/details/gtkpmjndyn.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtezqnqgem.html


<!-- 参考信息 -->