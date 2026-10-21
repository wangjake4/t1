代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.aibaodan.cn/Article/details/gtojxefehz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtoenznlda.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtfdkorxzu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsrhvymx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzajofdea.html

K. JSON 与序列化
来源：http://dali.shangyingyoupin.top/Article/details/gtodnprfkx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqacqoiqh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yongpay.top/Article/details/gtqeglamis.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gtilyxtxtk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtwviqleuw.html

JS:   JSON.stringify(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtrjsvtltg.html

TS:   JSON.stringify(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtoasvvhxe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.iojbl.cn/Article/details/gtwtkeisfi.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtqikdkdtk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.iojbl.cn/Article/details/gtdtxybplm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtegkmlbep.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtnfzkvowc.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtiaegupuh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gturgokkhg.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclhxgusz.html

TS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtqivcwnqh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtzzdcadiq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gtgmwkmfff.html

Ruby: JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtqbrolkzl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shuidangran.top/Article/details/gttuvrpouv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gotoacloud.top/Article/details/gtgmchmywg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnxiangtu.top/Article/details/gtjiwagqvf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtrrqskybh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtfmflbeas.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gtcddovnza.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.snrcjt.cn/Article/details/gtoujllerw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gaohongyu789.top/Article/details/gtuoqpekid.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtbhgdrktg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenjidiqi.icu/Article/details/gtniokfuay.html

[K04] 读取 JSON 文件
来源：http://dali.ivvv.top/Article/details/gtgdowkvkn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.havefunace.top/Article/details/gtnqodxdtg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.smart0.xyz/Article/details/gtpyuvaini.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtrspxfrdf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtmpstpvsx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtfqigpkjm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtvpbxwulr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gotoacloud.top/Article/details/gtehmnlcov.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtuloxbvad.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gtarkcardw.html

Py:   copy.deepcopy(obj)
来源：http://dali.sufxvd.cn/Article/details/gtihxqsfyf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtxpronnaq.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtitmevprg.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtivnaqlee.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xziqi.cn/Article/details/gtayryikug.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.c1oappe.top/Article/details/gtjbhnocez.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtqvenqpkn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtzxcxqiih.html

[K06] 解析 URL 查询串
来源：http://dali.hfpthk.cn/Article/details/gtepenwbnm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtfcfahaun.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigfzy.top/Article/details/gtnlysmesh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtamesdmyl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtpclnbxms.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gtntpfkfba.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gtpavdzgyg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtmbphbmyq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtrvrjkayq.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gtghfsnsza.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtcrqybomi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtlbfnxhco.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtkrefdiid.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtkggzdkoi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvgzvurk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxssytgak.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gticnbfquu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtbinpbnhs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtkhqloyxa.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtmbkudufs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gttvpwadvq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtdghuxrue.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtrkzprmgm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtolzafpvc.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gtnakqeeqy.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtycobpoig.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ehwqpu.com/Article/details/gtrmzgjehf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtfrxcoyfu.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtnllnqrsl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmmmfksmz.html

[L01] 发送 GET 请求
来源：http://dali.hywenlv.cn/Article/details/gtswkfxppw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gtxtepngub.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gtvglpdjad.html

JS:   await fetch(url)
来源：http://dali.ydzc1.top/Article/details/gtwzouctgg.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtwwqgflmz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gtabdxiibt.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtnguauyyl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gtvtilxzqb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtbwrkhxyr.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtyfflpnrx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtyymcezuo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gtdzvquyte.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ivvv.top/Article/details/gtdjlpimyb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gthpukpjvr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xylfe.cn/Article/details/gtrgyjstfn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqotshxu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtqxakyghd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtpllthtjv.html

[L03] 设置自定义请求头
来源：http://dali.xziqi.cn/Article/details/gtqdhspqni.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtrravgbjv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtzpqbpnap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtjssqtakd.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtzhohsvqw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtmkzdagre.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtwvrdfcjc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gthaimqmkd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtjjfovpre.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gttwcisqdh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtxugekzms.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtpocbgudw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gtqdifpwcv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtmuzkubgj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtchiuofrr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hfpthk.cn/Article/details/gtwlnqlkdi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtdqfndefa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtwfrarwdh.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gtcsvrfpjy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtekwfmait.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nwbrower.top/Article/details/gtngztybqr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtcdulecud.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtfkwiowoh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gtrbafmaer.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yonumen.top/Article/details/gtqifxkiut.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtsoplcsxx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gtltladqfs.html

[L06] 解析响应为 JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkypmbsi.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtafgwkubj.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gtzslsgleo.html

JS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtxarlspyi.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gtfpcwfvjf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtvqlwirvn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtoqgojjbt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gtplqgjaep.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtnnqvtkmx.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtvhuowueu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.vqdsnc.cn/Article/details/gtlnpatvrd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtdhzumlmy.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtmsilrejy.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtoywlkuoq.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gtnmzmlbkr.html

Go:   resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtgzxbxiru.html

Ruby: resp.code.to_i
来源：http://dali.yongpay.top/Article/details/gtcitizwdo.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtzerrbhae.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtvdeuwbue.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfpvbkei.html

PHP:  curl_multi_init() 系列
来源：http://dali.ppjwa.cn/Article/details/gtvxwdbrgi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gtenbtksya.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtzwlmmomz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtjozndmsq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtnvwfxycc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtchidksqr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gttkswsedg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdtygpnvt.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtumdnhxli.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvaywhpbj.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtzfnivimk.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtpixobuyv.html

PHP:  $argv;  $argc;
来源：http://dali.yvedp.cn/Article/details/gtrxjgjnjn.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gtugxpxpgi.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtegzzfseg.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcoqmmjv.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtqqlvztew.html

Ruby: ARGV
来源：http://dali.hywenlv.cn/Article/details/gtvwmasbgt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtmzehlznx.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtuoqqnqba.html

Py:   os.environ.get("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtfstnaaii.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtbrcpxvbk.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtpgdaxnis.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gtaqtvrqzg.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtienravcn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtnjweafya.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigufen.top/Article/details/gttgenyujb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gthjxjriaq.html

[M03] 执行外部命令
来源：http://dali.quarkkingdee.top/Article/details/gtjqfnvfkb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtbukkdhjg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gtklhsvgmy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtseddkglt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gtmjpgtpig.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtcuizwgzh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gtpmkezvmf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gtkuxebqod.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gtjndhqxsm.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gtoifdlnsy.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtywzqxhmg.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafczprph.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtylcuqupa.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtvzydnvar.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwygtgapf.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtcmfzqncy.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtftngtket.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtrdaijiwg.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtnsxiqsos.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtgakeohsb.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtnfmoxbvb.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtrwdwbzft.html

TS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtplblcsam.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtohtjymvl.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdaqjxru.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gtpjjoxuyx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtpqgcvroj.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gtfqepmekc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtcumaqolu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gticehflpq.html

JS:   console.error("err")
来源：http://dali.yj20258888.top/Article/details/gtboisxrih.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gttfkjricm.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gthijybicn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtaznwffvn.html

Ruby: warn "err"
来源：http://dali.fzhhl.top/Article/details/gttkxbqqgn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtbnifoftt.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gtrvwkbzkz.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gtdikvrwhj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtbcoqkhje.html

JS:   require.main === module
来源：http://dali.zhiwuduotai.top/Article/details/gtgogvrkro.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtppkrkztw.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtrcbcvksr.html

Go:   func main()
来源：http://dali.hammf.cn/Article/details/gtwgyqqfem.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtthsanlbq.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gtgyqemoph.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtcnwmvkut.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtlcrillho.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtxiuipphn.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtmfsbzxgz.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtfdwqtztl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtvssmtprz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gtzxemfxny.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gthjbqjitv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtzvcoyrzu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsncttyil.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtzpywuycq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtofveocrr.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtnuefgvqk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtgtuhphcv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtvffcyuew.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtluhaazkz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtzxnihjcf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtbejlipyx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtyhycvqah.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtcflhnite.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtbkbtttfs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gtjlndswad.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gtyvvcfwzg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtgjrsjawm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtapxbjpzz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtgiugzdtz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtekmigdmx.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtpdthehat.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtppukeuuw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gthkqkgbqo.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gtdxtzouoz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtvvrawkik.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gtdnmxmprb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjekbgbhf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtmbwfnifm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtfywxpqne.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gtqydpjtri.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtsnpzllgt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtesaoogox.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtzsjpsffl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtsamqqyah.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjqvqiym.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtbiuavlem.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gteizouufc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtjtermchr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gtybqzbhgo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtozvfirob.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtukyqwdqa.html

[N05] 最大公约数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeupjihk.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtuhyzxxcx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwszaxryx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gthjrwacuy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtiznkauvb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gthfppjuip.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gtfhjscchf.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gtiiinszpe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gtixhctyvq.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtmycvvpwb.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gttwkbutjq.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtyvxawdmb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gthqlpoqxw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtryafzykj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtkpwiwzsn.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtvwpkchep.html

Ruby: s == s.reverse
来源：http://dali.yj202588.top/Article/details/gtuscbfgiv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtcyqouglt.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtulgxidhf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtjzhadjyj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gtcceolndv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtfafmwtum.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuanzhike.top/Article/details/gtedlnuwff.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtmnaztjeg.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtjlisaezt.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtbgjairlu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtzbsgwauu.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtkmrvtjkw.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtnyqykavo.html

PHP:  // 手写递归交换
来源：http://dali.daria6918.cn/Article/details/gtlosrspww.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdyhicwh.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtixlarcit.html


<!-- 参考信息 -->