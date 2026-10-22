代发 wailian999

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ywliodsr.html

K. JSON 与序列化
来源：http://dali.hywenlv.cn/Article/details/gt2mrxcleso.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2fmydpfsl.html

[K01] 对象转 JSON 字符串
来源：http://dali.fengsongda.top/Article/details/gt2kfbnsmed.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxjqjkcc.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2barcxzwj.html

JS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2vskbhgbs.html

TS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2gkrkiyeq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfbcfnsh.html

Go:   json.Marshal(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2nqqrgyab.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gt2ywxahbxd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2bcvqjnxj.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gt2hqoterlj.html

Py:   json.loads(s)
来源：http://dali.cheryme.top/Article/details/gt2snpllzwe.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2muxrikea.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gt2iwhrylvc.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2mtqxhymr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gt2fkzsarwo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gt2jkcyhvbb.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2jzzgzelq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2mpbiarwj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hysaishi.cn/Article/details/gt2sryvighj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2hyeglhhq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2scttsnlf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cdnleiting.top/Article/details/gt2irjvjzeh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2awvoedsy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2aiaqlqzt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sxryk.cn/Article/details/gt2kwntnedv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gt2qpqxkxra.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gt2sehlqfcz.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2wshfcqbf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.316326.xyz/Article/details/gt2phfdsqcn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2dbdxszkn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2jretkncw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2weffpmjs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkidybhw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2gngltwpm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2rdzyzksm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258888.top/Article/details/gt2xwnnumma.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gt2brahmjxr.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntirbfoh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gt2xnngutgy.html

JS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkmxjqfj.html

TS:   structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2sguntijz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhijiandao.cn/Article/details/gt2emisbpvf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gt2tsktfcue.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fitczfgb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gt2nprkbktw.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gt2mboyzykr.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2qwsqfsiy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqthjcgx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2nitxtnwk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ykbdhktf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2lqdxuqip.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gt2feapdtqe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2pajlrmwd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gt2vtmciice.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gt2qaptfruc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaymsfe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2eakgqnaf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2rgscvoys.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2xtmijajq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2sfqonrbk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gt2pdieuuwa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gt2cexwqcye.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2zqfhwosn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gt2setxilwy.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2iatwkscg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2turcotsn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2rnmxdbzw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2cuwnppys.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gt2nlewxrta.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2czbwfgju.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gt2vepnzdos.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2zwkuktbc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2dvyzzqwa.html

L. 网络请求
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqavyygu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2kezxnszu.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gt2plfeqkqz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2vrmrkpkj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhiwuduotai.top/Article/details/gt2evtkibjd.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2mzrpioon.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gt2gajtzwtv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gt2ttlwnjha.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrfmuvqg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2qgqzblnu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gt2ghbhqpce.html

[L02] 发送 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gt2pegcospw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jianghu66.top/Article/details/gt2xfxtwzat.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gt2qgghlowe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhrxwqjm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aizwys.cn/Article/details/gt2xtjqbrqp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.aizwys.cn/Article/details/gt2quyprrlm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzqfolnf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gt2rntlnwmr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fzhhl.top/Article/details/gt2qhnshomi.html

[L03] 设置自定义请求头
来源：http://dali.shzxlz.cn/Article/details/gt2ujzvxzll.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nwbrower.top/Article/details/gt2uedgsrxl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xxhinqgc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2jxmtsahy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gt2qhzaelia.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2wywxhwwq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2kbmfodox.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gt2lancrrey.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2wckgtwuh.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gt2blutbjsr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2oinkmvqb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gt2yjpgzdcc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuilvna.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbztjfbw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gt2zbhxbobm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gt2tkjihycv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2hvzcqiir.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egdpbkux.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gt2erglskqj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gt2fnmhngpm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gt2gwpmcpmo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2eofkwcjt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2tbhrcekc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gt2ygqzijnn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2jwmvrbpd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2rlnqloaz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2xedxzixq.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gt2csowgrir.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gt2zbqyrclv.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2fmxmpxip.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gt2oaeiztip.html

TS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iipbpkne.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2iesdjslt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gt2nlubwbzl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gt2vviqrqam.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2sofcdyxo.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gt2vgjtoczf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gt2labkqvac.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmiqwfcg.html

JS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2tlbsfaih.html

TS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eaudujik.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gt2frsdssek.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2nwaoptrb.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gt2dolirfsf.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2oazxsggf.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2dlomgqjg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gt2uiutlbqa.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqzmxbvq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gt2ounqsawy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2hlforuud.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2fntjycdg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2nkzzghux.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2eenqlffs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2cglccpqi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2bxvfaabp.html

M. 命令行 / 进程 / 环境
来源：http://dali.jianghu66.top/Article/details/gt2qakdwgck.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ekpclzuz.html

[M01] 读取命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwawrghy.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2sloibyss.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gt2xhhgjbka.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2ysomnonf.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2wjmnpjfu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2zccscegl.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gt2uywhomzw.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gt2aqxgvxcf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.redwolf501.top/Article/details/gt2uwqipjen.html

[M02] 读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gt2vbmbijlg.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2bmgptmvm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2hbltooyj.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2mfxgejzf.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2ioqumpiy.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2qwaaeyph.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gt2sxmvkixv.html

Ruby: ENV["HOME"]
来源：http://dali.yj20258.top/Article/details/gt2obdbeeco.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2qwgtgymb.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zktqrffe.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gt2pktayqwp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gt2ytxwdlue.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2iewgflcr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gt2hqwnuory.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gt2anhaqrkl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cdnleiting.top/Article/details/gt2byjpwaht.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gt2mibnrrii.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2wkfkzohb.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2kjcojekf.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gt2eysptlzw.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jolzzfnu.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gt2yzeanzkj.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2dtzeehhm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daxiang520.top/Article/details/gt2txefmzxi.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2mdvhlkcc.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gt2aacxnjrw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2xjsutotk.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gt2qbuomheq.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2hfeqfbta.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gt2friszhfe.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2nrfdasqy.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2rcdhvtya.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2sjveosnu.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gt2isyitqae.html

Ruby: exit 1
来源：http://dali.jqgufenzy.top/Article/details/gt2oxacwnpq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2unitqfuv.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuccznzf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gt2lwhqbqsu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2wlurcwlb.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqznlfma.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2lydptdun.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2dxlmjnwq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2nrksmbbh.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gt2ubagluxj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2luwkglwb.html

[M07] 判断是否为主入口
来源：http://dali.yongpay.top/Article/details/gt2zhwzsjcc.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gt2baocnhhp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenjidiqi.icu/Article/details/gt2slkmpnmz.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2wvzauouj.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oundxtwc.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2wfaznztk.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gt2oupnfveq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2ymykkazr.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2lsfvehcb.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gt2dgovehdp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yanxiufei.cn/Article/details/gt2apdogjrq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gt2hcujefdw.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2otporaag.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2sexsjfig.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2kkfdxohn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2dysxhuwf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gt2kjjwkgxe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gt2puytqkxc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2gnbmjsem.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gt2mtyaciin.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ggwxjquz.html

[N01] 二分查找（有序数组）
来源：http://dali.yonumen.top/Article/details/gt2qoqmlhlr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqmziqel.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlgiphut.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2frfhykvg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2uoxtnujf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2gfafolgc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2szwlhbak.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cucudq.cn/Article/details/gt2pzlocasd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2swswuppp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2yrpeucjj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2ixbrbjwp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gt2oyuvmpih.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gt2mhrohphc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oymegrfd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2jleznkwz.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2xlfeprcu.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2bdincwym.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2imrczsoy.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2avrkqqhu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2pxdgpznz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gt2pdcnlgbz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2juzvsfjs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2ngtbcqbl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.snrcjt.cn/Article/details/gt2nceijnms.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gt2cahjdkpn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gt2evmzxvll.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gt2tyowlacp.html

[N04] 斐波那契数列
来源：http://dali.gotoacloud.top/Article/details/gt2ltcqmxuq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkrexpux.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2sgjcuwet.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2geqlhqgf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2mnsbdcqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2tbmhvept.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lykqjjrt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2znrfleei.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2efocjpcc.html

[N05] 最大公约数
来源：http://dali.aizwys.cn/Article/details/gt2lytxelzo.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2xptriwue.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2yybnyivi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmzylels.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2ydpxonky.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gt2tusmjwyi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gt2glwxhiko.html

Ruby: a.gcd(b)
来源：http://dali.cdnleiting.top/Article/details/gt2udrzgnzk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2pnwmzflb.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gt2jbernvul.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2bxzbtovh.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2hfeykgwb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkasbqar.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wajefbrj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2tncknqfn.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gt2ogfaxclk.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2zocpxnaq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2glrabair.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gt2vhhtlgyx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hnxiangtu.top/Article/details/gt2nlsuhxpn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttouvfzf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gt2kteybsoa.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gt2ovdltxeb.html

Java: // 手写 HashMap
来源：http://dali.jyoumei.cn/Article/details/gt2ildyhges.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gt2yrzouuhs.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gt2gqphwpim.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gt2uxahilrs.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2vclpxoul.html

Py:   itertools.permutations(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2nxdthtvg.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2phmtgmjs.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2wuvsejcm.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2zhycgjue.html

Java: // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2slpxhgex.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2ibgylvpt.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gt2gyubzuln.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2aasjvdax.html


<!-- 参考信息 -->