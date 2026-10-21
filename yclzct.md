代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.wangdashe.top/Article/details/gtjmsiouuq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jianghu66.top/Article/details/gtbisuxazp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gtznhicroh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtoeobpvrb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtuxmmyqug.html

K. JSON 与序列化
来源：http://dali.dianchejie.cn/Article/details/gtifqktwfz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthntefenu.html

[K01] 对象转 JSON 字符串
来源：http://dali.cqqwz.cn/Article/details/gtcohpdmcs.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtawbbwkid.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gtfkgkkjop.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gtoizmabjc.html

TS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtiqtllkou.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ybcxt.top/Article/details/gtjljourfc.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdjumpoh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jiagoushi.top/Article/details/gtwzzczcre.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.nanxinkj.top/Article/details/gtkuyuklea.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gtmfwhovqt.html

Py:   json.loads(s)
来源：http://dali.ppjwa.cn/Article/details/gtmavrowbp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sysykeji.top/Article/details/gtwjrtfexm.html

JS:   JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtrnasqihr.html

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtxhatmazz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shzxlz.cn/Article/details/gtwjvmrgcj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtaqmqzhpt.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtjbnbzpnk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gtyvolebwu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.redwolf501.top/Article/details/gtukhbxwmu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtsysumtls.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gteykdynhd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtnfkihkwl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtwyfbymks.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sweek.top/Article/details/gtxmmnbmzl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gtcmovkerh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtrzfpslee.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gtemhrsfiq.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gtcsydlart.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtssjgmndo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gthkqdjtld.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gtvxlthhql.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtogentwnw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtflytcyjc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gthrwgvbkx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtuzkywepv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtifwtvtzm.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gterstswoo.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtwfaotffz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtxspoodya.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtnoevlygs.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtvzvnhwvz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gtwuhqyiki.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtgkktwlxj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hysaishi.cn/Article/details/gtkoqklxfq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gtzqftmcwn.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gtlplboojb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtpkorbvky.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyielpra.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtsgkzofke.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtoolgcrjd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgfzy.top/Article/details/gtjcfwnjcs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazyinlpp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtgdrqqfof.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtcxpndwpt.html

[K07] 进制转换
来源：http://dali.ivvv.top/Article/details/gtdrcflyrh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtjyvtmxhm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yangfankeji.com/Article/details/gtdkxikmfk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtuxhabvzh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtwdtutujj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtbscjcwge.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.snrcjt.cn/Article/details/gtnfckqmjs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtybrljqea.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtltuzqzah.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gogol.net.cn/Article/details/gtbikiwpmq.html

Py:   pickle.dumps(obj)
来源：http://dali.aibaodan.cn/Article/details/gteqzfgces.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtoijbakob.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtddzvvfwj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtlhruonyi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtfccdehfg.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtqcxixzkk.html

Ruby: Marshal.dump(obj)
来源：http://dali.bjfxy.top/Article/details/gtuxhwcfat.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gtosimrqad.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvyegcvxf.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gtpwasjicn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrwwtggij.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gtcpsavima.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzywjckk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yongpay.top/Article/details/gtxhsgdomu.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtwvgtsozu.html

TS:   await fetch(url)
来源：http://dali.aibaodan.cn/Article/details/gtmnjtsgqr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenjidiqi.icu/Article/details/gtiflvevek.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttniaqqkh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sufxvd.cn/Article/details/gtcxldkloa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtprbksxre.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtcsinltgr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gtjsficcjj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gtuzjvokfg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtxlikhcvi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gthedncisa.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtyezoazus.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ivvv.top/Article/details/gthslnuyts.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.9152youxi.cn/Article/details/gtgxhvrxwi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtudmsmxmj.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtgvpwvmgl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj202588.top/Article/details/gttrsxdsup.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtohyopixa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtamouseig.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtwlambjco.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gtiwrlfojx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gttlfyokof.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zdqjudy.top/Article/details/gtzmhiorjb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtwvxkbbgk.html

[L04] 设置超时
来源：http://dali.zhixingplan.top/Article/details/gtfdqgrdsz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtheqtjmqa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gtndsvjgcx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtwjirwrzw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtixakozgv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nwbrower.top/Article/details/gtlpbbhkub.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtwknspjif.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jinghuilouyu.cn/Article/details/gturxcthvv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtapanasme.html

[L05] 上传文件（multipart）
来源：http://dali.nanxinkj.top/Article/details/gtnypilksy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtwwnmeiwf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtkcnozbld.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtwqlijzxg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gtmuayqkbt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.316326.xyz/Article/details/gtlrkduejw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gtbleyocfp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.andypj.xyz/Article/details/gtppaiwpws.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrinxxfv.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtkaomztuk.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtezcszjvf.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gtitgblfgs.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtfyrwbhrd.html

TS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gthwvnabwk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtuxfnemlz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gtvlbzufgb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.kuanghao11.cn/Article/details/gtwrehzlpl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtnwlxbazt.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtyjejkqig.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gthvnvlons.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnxiangtu.top/Article/details/gtmyxavlsc.html

JS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gtbjlxibqk.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtwttmmakz.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gtrbtsjrie.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtjgerkdll.html

Ruby: resp.code.to_i
来源：http://dali.yuanzhike.top/Article/details/gtgztqsvpv.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtzvxlahcz.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtppvehtyl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtxtloerii.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gthpcqsasc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtzfdprbiq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtmgbylwnb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtascovoqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.havefunace.top/Article/details/gthsvtcqym.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gtzhchghwo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ivvv.top/Article/details/gtjxqdvhfh.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttfawkjwj.html

M. 命令行 / 进程 / 环境
来源：http://dali.ppjwa.cn/Article/details/gthznwvful.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtctyewwhl.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtrhmkyspn.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gtoperputc.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gtdwjpdsfh.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gttowcomup.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtrbwojarb.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtqxotofjv.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gttdlhkwfu.html

Ruby: ARGV
来源：http://dali.jinqigfzy.top/Article/details/gtgtlaofvk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtkmblfvie.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtxavrsskw.html

Py:   os.environ.get("HOME")
来源：http://dali.fengsongda.top/Article/details/gtntomkhau.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gtmrugpbtx.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtduoyrpzm.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtmjsnajla.html

Java: System.getenv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtyrjeaqef.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtcbnklfvk.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtpcjuqeoe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gtiznwnocs.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtywerztxp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gtcajsline.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtjbpyvdqy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtpxdvqmef.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gtqfdmlyqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtkhihpwvs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtpqraafug.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gtvjnwaqxc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenlongwang.top/Article/details/gtifgofopb.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gtmhxsxjlt.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gtclpxgmpt.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtpxsgnhjt.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtsbhmevkf.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtmhxmqtik.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtyzewrdwc.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtbhyobfth.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtgettdrpn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gtycrbbjbs.html

[M05] 设置退出码
来源：http://dali.gotoacloud.top/Article/details/gtihlayemk.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtnkrqdobu.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gtwictlvoo.html

JS:   process.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtcchjcckn.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gthwortcqx.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtqetjzzpa.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtwgfohxxa.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gtgicqpfpq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtvoyoslpe.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gttnqreujh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtfztllmav.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gtthhyspof.html

JS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gtuikkuhzf.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtjaabnlsy.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gthobiaejy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrziqwiqp.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtczqabtot.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquqhqzwj.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gtbvjusifg.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptqwhgbu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtlnkgrzsu.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiakzissf.html

TS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtqcddbiyq.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtqiciqrzq.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gtuqajvcap.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtjgyceqnr.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtjzvhmsqh.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtstqytfjw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gthwradyij.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtgnnglmpu.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtmunbazml.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gthhxfjqyk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gtvgjqduac.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtcpkycovg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gtkazlibuj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtszzglolq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkeidgvq.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtamtapgcq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtorjhyykv.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gtdezhieyc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtenufnqig.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtfmbeqmae.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gttslvrymh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtexibjgri.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gttfkxfczi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtajjpaoqn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtbyppketc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtzhwvyjsj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtmwivklro.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtqgmrbexz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtzddnhxmi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gttcrcvlzx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtxyzalvqh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gtwkmtyifn.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtupbbskkn.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtotejiaxh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gthotzohcz.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtypqvlbds.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtflcrqdmf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gtfxdnrfht.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gturaotlok.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtcdznipzc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtfmrtxbtg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtlcfnuscs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtvsjrwoww.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtkhbswzjn.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gtgckprtpu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtfwemckfb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtummcdoxr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtuubiwpps.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gteaqsafee.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtdiscdvhm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtauotppgd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtakoqzuhm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gthfhtxubq.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtdjqqlsjp.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtqmcxqvas.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtenixxbyy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtuvpsemrt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtrqydwbyx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gtrqdrpyjb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtppxcufft.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gtjxezxzrm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtwglxtquz.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtjwuxfmvz.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gtxdgkmwyl.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gtqtghfbfz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gteapwldyg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtticxldne.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gtxxmusiph.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtxtbeqnza.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtzsmelkzv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtyxvvbqiz.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtoevekcfx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtnppuvzia.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtauruqxrk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gtbvkpadis.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gtihpwetlj.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtzwvotsfv.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gtszpidlhv.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gtpqzfslyd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gtyvjnrmgu.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtorblieod.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtwdgkfvas.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtmwdkftkc.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtogstpfbq.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtnfpfutiv.html


<!-- 参考信息 -->