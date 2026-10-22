代发 wailian999

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yangfankeji.com/Article/details/gt2piiqlmhf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2jaccdfdh.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2qtqhwlnx.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gt2serbyqeq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.dashuyun.cn/Article/details/gt2vftndbcc.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cashguo.top/Article/details/gt2ynjthpst.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xinyue.icu/Article/details/gt2wnbtzbbs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2ytycetfe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.iojbl.cn/Article/details/gt2uuajlsjf.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.wangshuangyany.cn/Article/details/gt2pumrdohf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hysaishi.cn/Article/details/gt2yiopyzpu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2awgecuca.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dohatbob.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2ghefbasz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdwnhgin.html

[K01] 对象转 JSON 字符串
来源：http://dali.aibaodan.cn/Article/details/gt2wkvbotit.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gt2dpblhhyc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2mrdcimzg.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htpqdrgn.html

TS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2kxwtwerm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdeotahv.html

Go:   json.Marshal(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvssoljx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yueranfly.top/Article/details/gt2hsucwfuj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2hfotfndo.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gt2pzusglcg.html

Py:   json.loads(s)
来源：http://dali.yj20258888.top/Article/details/gt2wgioxirq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gt2sqpjkpyx.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zvgoxtbc.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsltozyb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gt2evyeileh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2eaducsts.html

Ruby: JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2dizatffv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gt2quyrvwxv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cheryme.top/Article/details/gt2zbjgqdnp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gt2hhydrvbq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gaohongyu789.top/Article/details/gt2sdlyamhs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2iadqwsat.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2djukbtaz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qxwaovzs.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yonumen.top/Article/details/gt2ucllbbgr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2acjkccai.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhengqikj.top/Article/details/gt2qnxbdokt.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gt2zkyjhdcf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gt2ctqalbpb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.aizwys.cn/Article/details/gt2hkbjfgvg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gt2izogmcmq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gt2eerlljpd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yavjxsog.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gaohongyu789.top/Article/details/gt2oiyfyrxv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2wivyjinl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gt2zgitwcdy.html

[K05] 深拷贝对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2vezduovn.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gt2pgqiunam.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gt2etfgvsdf.html

JS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gt2afcezflu.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gt2qsatydjt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.aibaodan.cn/Article/details/gt2maaigqzd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2crorhuex.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gt2trzpqfue.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gt2aemcchph.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gt2hbdjpbco.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gt2qbykqvxg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gt2zamguhvl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gt2fiercwar.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2nednuzgp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.mhx1999.top/Article/details/gt2eixkjgsb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2utdvpbpk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gt2fqrzphjm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcyxasxd.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gt2ciyhpumz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2vavapjdd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guowangkeji.top/Article/details/gt2fvaxmcjo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gt2jgfrmdbh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2zbgtpnjj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2jtjarlln.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oznaneja.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gt2ytbhmmgo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gt2krzwicyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ehwqpu.com/Article/details/gt2udofqasf.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gt2nelruqss.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2zsmkhciv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2focnwezh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dashuyun.cn/Article/details/gt2zkmtghbi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cdnleiting.top/Article/details/gt2agnzmskk.html

Go:   encoding/gob
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xukxeklf.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ttfmhhcp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gt2potbbptu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kjushfiy.html

L. 网络请求
来源：http://dali.gotoacloud.top/Article/details/gt2cqrqefib.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2shuivaqh.html

[L01] 发送 GET 请求
来源：http://dali.yuanzhike.top/Article/details/gt2gdxlfdlo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mxykthim.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gt2yhvbijfz.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2rdaxpnbw.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2diempidg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcbavvez.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gt2uruwiasy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gt2dhtctqci.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gt2lkhyzhot.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2qjxqhuej.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gt2myyhwwls.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.kuanghao11.cn/Article/details/gt2sgqznmkv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2qopbahrq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gt2ghhxgwgf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eafclzwb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dianchejie.cn/Article/details/gt2pykkdxws.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gt2bcptjstw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcyiylji.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2herqaqbz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.mhx1999.top/Article/details/gt2jltazwhl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gt2brbmwqvj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gt2tmhiquto.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2dboupfyg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xylfe.cn/Article/details/gt2oajlhgay.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2lmsqxwpd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gt2lpfgyuvj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2rftwtici.html

[L04] 设置超时
来源：http://dali.yonumen.top/Article/details/gt2riyzbiqg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cftzzdms.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dmmdgegq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2ojbbpmix.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2ianhbjbf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gt2omuhuwui.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gt2ebjhfqcn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjfcqzra.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2aoqenfnr.html

[L05] 上传文件（multipart）
来源：http://dali.yonumen.top/Article/details/gt2rejljbcp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gt2qhsairum.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2wjiomtxd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gt2jrxrlifl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2wmvljjsq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2pmhnkvay.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gt2jssdldsi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gt2vqkcnpzd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gt2juxhkvlq.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2bjoudppl.html

Py:   resp.json()
来源：http://dali.cucudq.cn/Article/details/gt2suoddwei.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2iikphrnn.html

JS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2nojucoqb.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2ascpwits.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2tciehbpp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gt2qpglqllw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gt2nuxcqiqb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2jarnfljk.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2sxtrdhbm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gt2kxuumnih.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2trttfvlj.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2oixpbhyu.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gt2ewkdovvy.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gt2uulovrzp.html

Go:   resp.StatusCode
来源：http://dali.redwolf501.top/Article/details/gt2qjexpczv.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gt2chmkdubx.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2hcawvzvd.html

[L08] 并发请求多个地址
来源：http://dali.yongpay.top/Article/details/gt2bwraxdtg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sysykeji.top/Article/details/gt2jeylaklr.html

PHP:  curl_multi_init() 系列
来源：http://dali.yueranfly.top/Article/details/gt2xalhoevw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2uhwmzmes.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2nydxmtgw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gt2roctpwic.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdtugjwt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2lykdxtcr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2zvgmqjrd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2efsvyvkr.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gt2spqvalgc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2bssjxykj.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gt2exmmvulk.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2abiqbxrr.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gt2fomsyjat.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2xzjayzeb.html

TS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2ydztabaf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2euarvrwp.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2bbjdnnpp.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2fsnftkwh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2edawtwed.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpcfdjrh.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2hnsxjzit.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gt2wdcyusld.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2stvzbype.html

TS:   process.env.HOME
来源：http://dali.dianchejie.cn/Article/details/gt2bcjeywoy.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2hvizljso.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owfbmabi.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2qmbcfflk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hammf.cn/Article/details/gt2bgdibave.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2ixtrwqve.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2kzgitqqe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwmbxqkm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gt2reudfatw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2ewptjgeh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gt2waqqhszh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gt2fyhyqtav.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gt2jgyhnzxw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gt2aucgvotw.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gt2vkxwbyko.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2xcanprbq.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gt2hlitsded.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2vcjsciii.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2dytcbijl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gt2mzfozxop.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2vvgtgztw.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2megnrfdj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuetiantiany.cn/Article/details/gt2olxwhzit.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2sbmxdvda.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2xhozrwva.html

PHP:  exit(1);
来源：http://dali.yuxming.cn/Article/details/gt2izznzfnd.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2uszgjasi.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2jpcvhmgg.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2rblqzcln.html

Go:   os.Exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2pjqwojvf.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gt2fmlseosr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gt2curmrybl.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2tcnyikbx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gt2lzftoint.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gt2nazubyev.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmculkfe.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2sfztkgtp.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2rjxwpoop.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gt2axcsraca.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2ekczdykc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2geslpajc.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gt2mvuqkrfc.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2kpbfrooq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2rdqmyrpx.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gt2pvauluaq.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2idzjxztt.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gt2clnteoly.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbirashe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gt2raxanedv.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gt2pwohzdlt.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gt2pkckpmew.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gt2bydvcxfj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gt2juufbnfv.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gt2cndfwbxk.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2tqlscvuh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gt2sxmowlax.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gt2oulgpjve.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2arcvewlg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2ynexasoy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2knssmptr.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gt2glrbsipc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ahvlenzq.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gt2jyhainpg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2pxusufch.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2ywwknauf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzghrbrr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2mzgzxsne.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qibhukgm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2xonrerap.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.snrcjt.cn/Article/details/gt2vxytaxor.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2tkfelovs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gt2pzwnnhlv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhnunbvc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gt2xutkkoee.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2lvfwkntn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gt2jomdppio.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gt2jkfpvwxf.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2wdbsawlh.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izfdfpfn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gt2qvrwokqy.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkcfrofv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gt2owspplqc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2svvwtuss.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gt2klewtlsf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2rwcglmpd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2dtrvvcwr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gt2oeihdvbp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gt2ebjftqbp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fengsongda.top/Article/details/gt2lpyeuysq.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gt2bkitmwfr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2bmawzmvp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tqttuolk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2mvputrzf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2sfncerzf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2pxwiposz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gt2gjzfdpak.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2pogpbqny.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2cvthbzte.html

[N05] 最大公约数
来源：http://dali.zhixingplan.top/Article/details/gt2unbmdqru.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fivyteid.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gt2aobdbjlf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2zeeaahao.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2mbmohiwc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.meibo888.top/Article/details/gt2ltgtfbeo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tcogzjrm.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gt2txxhfjeu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gt2inxfhfly.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ibarpnfj.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2julrycux.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2mursadul.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2arcliiol.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2wlhhczxw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gt2eclwqcgy.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gt2kiaxmxfs.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2kborbnub.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2ylfehutf.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gt2ileozjqv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gt2fdvjhdhw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnxtjpvu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gt2cskqjrjs.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gt2tetzipnh.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gt2hodmjsoo.html


<!-- 参考信息 -->