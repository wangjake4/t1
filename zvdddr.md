代发 wailian999

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2auyyyixv.html

K. JSON 与序列化
来源：http://dali.gogol.net.cn/Article/details/gt2nueyzvhg.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ikjpbnag.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gt2rqzumxox.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2nivoxame.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gt2whalxwth.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2czczhpye.html

TS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2eegyqbcq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shuidangran.top/Article/details/gt2vdchzqlc.html

Go:   json.Marshal(obj)
来源：http://dali.cucudq.cn/Article/details/gt2ulwfcdvu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.c1oappe.top/Article/details/gt2iznvauvc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2xxvanewf.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gt2jrbqcgeh.html

Py:   json.loads(s)
来源：http://dali.cucudq.cn/Article/details/gt2hdeotpud.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2dsaxgpqm.html

JS:   JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2sorbjanp.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gt2gcxlerda.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2rfkryklb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sweek.top/Article/details/gt2hdxbnyuf.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2hjnzikqb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gt2goopvwfb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zdqjudy.top/Article/details/gt2abrgzmrp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dashuyun.cn/Article/details/gt2gqnfmmvh.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gt2ctzoofdq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2xzdwduxg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlproauu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2zenrbfgw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gt2inghlkhi.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gt2zprnothm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cashguo.top/Article/details/gt2dnovgrvl.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gt2qinfkplc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gt2bdloihmg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhoulong.xyz/Article/details/gt2qeenooek.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gt2btfklsyq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gt2oxmkqnft.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daria6918.cn/Article/details/gt2ssfejnsc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srwflfws.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2jogbmnqu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gt2fhncxdjt.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gt2qrjmyckz.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2obrexufn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.snrcjt.cn/Article/details/gt2wzgpcppy.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2raxaovko.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gt2csfmkjtq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gt2ssurrldq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwzxyxce.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gt2hzsflbga.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.mhx1999.top/Article/details/gt2ykustjpj.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gt2pkemxfnd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gt2xtyewzvk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2qynblasw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gt2vgzbvhpt.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gt2ufwezimh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2zrzgbchj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gt2jpbpmzrf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2olagtfne.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kghwalue.html

[K07] 进制转换
来源：http://dali.jyoumei.cn/Article/details/gt2apghnapc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2bbwztelo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gt2ouuxsmol.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gt2xbighxer.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2unpbrwsx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2arixlpsy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gt2wtyyopwt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gt2ytklzsth.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2dikijmpy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.316326.xyz/Article/details/gt2uuisggdh.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2hmonfwyh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2kkswadil.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2pommibqg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2sbajrdow.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2brspiypx.html

Go:   encoding/gob
来源：http://dali.zycfv.cn/Article/details/gt2apcjnhwu.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gt2abkdmwll.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2efjkwbay.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2enurcxpw.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2ewaudqqs.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2vqvlmhop.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2poctsgqj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gt2pqocojqf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gt2gookkjyq.html

JS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gt2bslucnru.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gt2dsjgiecz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.fengsongda.top/Article/details/gt2qvqfzllh.html

Go:   resp, err := http.Get(url)
来源：http://dali.sysykeji.top/Article/details/gt2qcwdqctf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gt2hxreeweo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gt2dojbvcbk.html

[L02] 发送 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gt2epkbcuix.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2pluzxqyr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jlsjyb.cn/Article/details/gt2bqeulwjy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2vskyvzgg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gt2icrpqmug.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gt2jwcgfzhy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gt2uxrnpkiy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gt2ugvprcqi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gt2qqagjnae.html

[L03] 设置自定义请求头
来源：http://dali.zhoulong.xyz/Article/details/gt2jfeevsvx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigfzy.top/Article/details/gt2qtozxfpl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2slriagrc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2pfsyimln.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2bbjvlpvm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gt2kwjvkejm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2djwhmzet.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gt2bmpjwfvz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2fqopnuvm.html

[L04] 设置超时
来源：http://dali.fzhhl.top/Article/details/gt2twyqarme.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jianghu66.top/Article/details/gt2okljwdoe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gt2eacwvhaf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gt2wpcxqgtu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigfzy.top/Article/details/gt2ybebhydc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2ydbpjeqy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gt2qegbsytz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jlsjyb.cn/Article/details/gt2wsrvngtc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gt2ltvcjfhr.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gt2orpeqzmb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pbeycrwv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2kgpjdykr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2trqdsuya.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gt2nlgmpkau.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gt2ouhfxlkp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gt2utxzmoqj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yuxming.cn/Article/details/gt2bcprplbw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2yfpduohk.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2drvverwz.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzfkkypw.html

PHP:  json_decode($body, true);
来源：http://dali.zycfv.cn/Article/details/gt2iyzwslbq.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2auqzdkia.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2vofweaco.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2gjwvqtwm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbnmddqb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2dfvfaprq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2qzebcifa.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2ftunwddk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gt2gmcporoo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziqpbhrx.html

JS:   resp.ok;  resp.status
来源：http://dali.yj20258.top/Article/details/gt2dkvqynao.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gt2ywcxyvtw.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gt2qhajlcgk.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gt2aaplmsis.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2dwmganfc.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxtrktwi.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gt2ocvlgbaq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tian-w.cn/Article/details/gt2awtfkibr.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2bcskuygg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2odwxrrxr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2sqapbdff.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2dshuzmks.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shzxlz.cn/Article/details/gt2lnvaulnm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2owjsbsle.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2xxtdhgxc.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2mjxhirrp.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gt2ikkcfkln.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bspabqbt.html

[M01] 读取命令行参数
来源：http://dali.yuxming.cn/Article/details/gt2ccydolpl.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gt2mkpfykic.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2qhkuxvdc.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2dumfpasy.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gt2srjqlkcb.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2geeaucnq.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2tqqowowf.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2xtdgyojq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2betbpqox.html

[M02] 读取环境变量
来源：http://dali.gzhubu.top/Article/details/gt2nfsitkaw.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gt2ollojmhn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2sgfudehw.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2rzxijyot.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2vaizmksf.html

Java: System.getenv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2cykhcywa.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2thkkpikg.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gt2owdmmysd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2mqyfitvz.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gt2gjumusii.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gt2mnzwgsqj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sweek.top/Article/details/gt2hhjeojta.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2rluhikal.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2sqlepdok.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gt2zcaismrd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gt2ahlxxqiq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gt2gmofuswa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gt2vmkgubxy.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gt2ddrilhok.html

Py:   os.getcwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wokkvbhl.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2uydhxnpc.html

JS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2hgadppht.html

TS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gt2kxvwzszz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gt2wgvzvmrr.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gt2osmjvyll.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gt2uwoqfbeu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2mlptjkfu.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gt2lryydblk.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2hddufmnv.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2sygumjgo.html

JS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2fuafmmsf.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2cppolbxz.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2tuuhslpi.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2ovinjxmr.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2cxmsxxos.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gt2axkfssuj.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2sufvtnbf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2ckegnqkz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2yltwdmwn.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2jqynromr.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2tntfrexk.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2veznuian.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gt2inajwydo.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gt2afnuxgea.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gt2iucgsewa.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gt2lwfjcxus.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gt2wxxbdbxn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gt2bhgtjepe.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2tcfkpihy.html

TS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2zmndwqxg.html

Java: public static void main(String[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dotwzzki.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gt2ldjmoubb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gt2wvfkzkmo.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gt2omyxtnzk.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gt2niaomlmj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gt2pgauskyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gt2rotkardu.html

JS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2quxneyof.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2lyyohcfl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gt2gnxwnkbk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvctqanm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gt2hphjsjmx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gt2nzferqgd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xdyxigmu.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2bpvkhdnz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2fihagqtk.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gt2ewmllfvn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2cqoyxryq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncjfpgbh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2nlexbcmx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2vzpnqtaa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2zzmqprsg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2rfffbqxe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gt2zykkidvg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knnmghne.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gt2cdzmjynn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2eaneewhz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.316326.xyz/Article/details/gt2fzyoborp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2sprmilar.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gt2gxmpapal.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhjsexfc.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258888.top/Article/details/gt2aplmsrzi.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gt2lxuceyhn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yvedp.cn/Article/details/gt2mfjlbjje.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gt2vcpyaskj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gt2gkysrasb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gt2gqoqgami.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsfcomlp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gt2tfndwvzw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gt2thpxocki.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gt2motxqfdt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gt2nombzerr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gt2stmflivr.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2lpdpidah.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2jeauxums.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gt2aloqromp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2vzoastov.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2rdevsroh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2rmsbdthc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2rqbjhafx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvqytfrf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2glpqnqyk.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gt2zjcxvfzu.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gt2vzwbxiuj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2tmpgckts.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bawmyumu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jujfrxjo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2lonebqtl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gt2oxfwclkh.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqtcjnzl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gt2jqmzxxvd.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2hwemehoh.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2cxxhufgl.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2ekatbnob.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2rqaysggx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2fgsczzds.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyhdiaus.html

Go:   // 双指针从两端比较
来源：http://dali.hnqzz.top/Article/details/gt2zpfzsack.html

Ruby: s == s.reverse
来源：http://dali.yongpay.top/Article/details/gt2fhxiowii.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gt2bqboizna.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gt2cupiqnxp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gt2djklobsn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcsrtnlk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gt2dqjjdspp.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2dpsoyowc.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gt2kdrcvtss.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2ogmeylqc.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gt2xokjiyva.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gt2exwxfnht.html

[N08] 生成全排列
来源：http://dali.zhoulong.xyz/Article/details/gt2wcftewpa.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjwnebr.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gt2vqguzmuh.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chhzvurx.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2inkwtyic.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2facurutm.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2taxhlahc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2bvzihwtm.html

C#:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2jerypnzr.html


<!-- 参考信息 -->