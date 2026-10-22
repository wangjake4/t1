代发 wailian999

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2cclzmfzg.html

K. JSON 与序列化
来源：http://dali.sufxvd.cn/Article/details/gt2lxjlisqc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2cixicdsy.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2oepqhcjt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2uwhmnvow.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gzhubu.top/Article/details/gt2ocfffpvc.html

JS:   JSON.stringify(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2brhdfpfa.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2sjjmiurc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.vqdsnc.cn/Article/details/gt2iimnchzb.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2vnlmhncp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2llaxfiyq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.iojbl.cn/Article/details/gt2xzzepnqc.html

[K02] JSON 字符串转对象
来源：http://dali.jinqigufen.top/Article/details/gt2uomqzced.html

Py:   json.loads(s)
来源：http://dali.yvedp.cn/Article/details/gt2jyehehwv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gt2hqqemzxn.html

JS:   JSON.parse(s)
来源：http://dali.haohaochexian.top/Article/details/gt2qolwnsic.html

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2khihvbpz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2wvjjgndw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gt2pbyszwwx.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2uaspwmge.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xziqi.cn/Article/details/gt2kniqquko.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.guannengcc.top/Article/details/gt2batdpbso.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gt2zecgwjvq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gt2kxpfjicm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2tpyfxoht.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2cgawnyhb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gt2uihsagth.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gt2vkyhlleb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gt2tsnjkaic.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2kjnpzgip.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gt2bkbighdn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gt2mtjeukfc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhongyouzk.top/Article/details/gt2igigstnz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2mnotkrtj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2nqsrurbf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdxwxqcb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2glrxpukw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2pojcfben.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ejaexday.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gt2wknrwwoz.html

Py:   copy.deepcopy(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2iomjhzfz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2bznyubiu.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2wkikvylz.html

TS:   structuredClone(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2qihjhltn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.0kj1m.cn/Article/details/gt2sbswsokc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gt2pqsdmmhx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gt2rqhufufo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gsqelakt.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2gjbqixgx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ejxitamv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2ehxmnowd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2pkzoxwol.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gt2rcbyyfgv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gt2pzmsxyad.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2zqujthnl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gt2ftoptmss.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2xoohgwry.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gt2mdxejjqu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2mvldxmhv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gt2ntgintwj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijnvisbq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2ndivoyxn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2dkmpkbxd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.havefunace.top/Article/details/gt2hvxbhvih.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjeiaygv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2jzgpkfkh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daxiang520.top/Article/details/gt2zyhrlpbc.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gt2eljxetum.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.0kj1m.cn/Article/details/gt2tuvxqqwl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2qcowvgii.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2dqwdeibm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gt2vgkzczfn.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2rsvjclhc.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2dyqvsnee.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gt2nduuukmq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2fmwudoap.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gt2qruhfrtw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqqzolzw.html

[L01] 发送 GET 请求
来源：http://dali.shuidangran.top/Article/details/gt2vocybmwe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltxodsox.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2dqvlaftt.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2kiedfumi.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2vovnpmis.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gt2feupjuif.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gt2zlhbqile.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzfxablr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2amltlqyy.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njnavuue.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2gvftlevg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gt2tmukkjjc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gt2lzcudfaw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2slumfhxz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxuectnp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gt2vaobibzk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gt2mntwopoc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.dashuyun.cn/Article/details/gt2atgifmqu.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gt2vryuopoj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2ducaxeki.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cheryme.top/Article/details/gt2nyyxkugh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gt2mryqkfgj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gt2hfcwyegh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenlongwang.top/Article/details/gt2aluctxoz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gt2lsbjnvjj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2prtleihw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cejjyvng.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gt2mcdlxonc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2byvknabm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gt2zuxkmnbg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmhcstsn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenzaomai.com/Article/details/gt2ibijcgpa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2memqlcyr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gt2bwykkabx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gt2uhmamtdf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gt2hfsvzajb.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gt2zqywxcgi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwiohdgy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2niluknej.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gt2nhqqclnn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2njesrqza.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2iwwnfrkv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2ofdgbtbu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2hksrpjda.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlbmemew.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gt2ifkuybud.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2yykhsbua.html

PHP:  json_decode($body, true);
来源：http://dali.0kj1m.cn/Article/details/gt2eqgxlmaw.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2hixvguya.html

TS:   await resp.json()
来源：http://dali.yj20258.top/Article/details/gt2dfmkeauw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvphylwv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jqgufenzy.top/Article/details/gt2vcfzurrk.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2qpsxhovr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2irwwesby.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2tkrxurln.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.iojbl.cn/Article/details/gt2ltvgogbm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2efmsldvb.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2wbocyimk.html

TS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2oymuqrov.html

Java: resp.statusCode()
来源：http://dali.svipenyu.cn/Article/details/gt2hxypiloi.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gt2grejowze.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gt2kdmdkanl.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjfekbwh.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gt2gqzelebz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gt2uzfpkgce.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenjidiqi.icu/Article/details/gt2drdebttp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2idcyuvyo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2coaepvyi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2cyrwfkuc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2bueejxip.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2jqaumgng.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2ewkdqtzf.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2dwcrfeaq.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2xlqzyqmo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dlfvehrr.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2zutsqkys.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gt2hqaexnqo.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2znjiuuil.html

JS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrbabpwo.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccwkptzs.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2vkvbguyb.html

Go:   os.Args[1:]
来源：http://dali.hywenlv.cn/Article/details/gt2giiivgel.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gt2ifdizkpc.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gt2tzlxyvcp.html

[M02] 读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gt2yoofjzll.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2aozhvnpr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gxociyyw.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2slhlaaxa.html

TS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2kcnaekps.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2yxqofzqj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2kpujabbv.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gt2hyhzmolp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2tzlglmak.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gt2nrfenyke.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2fdyqtozv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tanke756.top/Article/details/gt2cmalxoke.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgpdcqxy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gt2skbalsme.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2kvnxpslx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhblqfqr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2okvnulhu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gt2bswbpuzu.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2apwjhhle.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gt2yynoeqeg.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2wbfxoexf.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyftvcdc.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2tdclaepc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gt2jmwboqpt.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2zlwenztp.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2drzsslzh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yfpbwddh.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2xnvsbxfu.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vfuspqcu.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2tunzyvvq.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2kbzchkmz.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2kkpjtmqw.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ubloznts.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gt2rxyjjykx.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gt2lkimvkuc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ltuetgfy.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2lxmnayfi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2tpmabxch.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhkdrhck.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2yissmbkz.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2neevaejk.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gt2puqfsbcx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gt2lajzdzis.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gt2szocjqxs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whcvjiqh.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2jnrzspsm.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ioyyohuu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gt2pyomqdpr.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqcebciw.html

TS:   require.main === module
来源：http://dali.pycfn.com/Article/details/gt2raylhxaq.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2omkpjjdw.html

Go:   func main()
来源：http://dali.chenlongwang.top/Article/details/gt2pqhsxewc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gt2ycmshggk.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gt2lbcfhfbk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2daiacjjl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2ckeyrhpz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2ygefajaq.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gt2gwhflkkr.html

TS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gt2rsvuvxpw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gt2xareppar.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.9152youxi.cn/Article/details/gt2hoewhger.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gt2eglhjiwp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwozrhzk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2tdfhcjwo.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvdftdti.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrwntczb.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2wxhqandi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2ingzitsy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2uaiyoxty.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2ekkummjq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2nyyqnpwc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdiucmbc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2udxrmtgg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cdnleiting.top/Article/details/gt2qqkdshxd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2msrznvwt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbkewuca.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2qahqrdda.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdzyhzye.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2bdngnkhb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2tetxcxrc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tmnltttq.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2zgkfdpcj.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gt2goapeuyi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gt2pwktxnsa.html

[N03] 快速排序（分治示例）
来源：http://dali.guowangkeji.top/Article/details/gt2klhgypai.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2tgxeopzi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.meibo888.top/Article/details/gt2mumqbmlp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2zhosmbkf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gt2dnodynfv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gt2gsefbdxq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2srdyoswc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2dawmdasi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gt2obehotry.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2jqwgzteg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2griavmnf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2zuevdjgw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2juzzhzli.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbuhbnnm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2yqllqnyn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gt2wmplgvbg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbtzngrj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2lpcwotmh.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2qttbggrx.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2qaupkhwu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2smctbwat.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2bzxuvoed.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2ihuydpqm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj20258888.top/Article/details/gt2lbrcyser.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2eixfymbi.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gt2colbziyo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gt2zfliqywy.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gt2phwqxqqx.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2croznimi.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2csowvhcv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gt2zvrqrvpz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2pefbtomq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnhebfuk.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gt2nzoeiapi.html

Ruby: s == s.reverse
来源：http://dali.sweek.top/Article/details/gt2zhuwjhrm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2bibtaqxi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2iokntrlf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zdqjudy.top/Article/details/gt2zfhzfify.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2pxtktyaa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbsursxw.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gt2ocqpiisn.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmfykaxu.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gt2qkcjuvxo.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gt2fpmapozp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhyvtcat.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gt2dcwocscr.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2quegcbxy.html

PHP:  // 手写递归交换
来源：http://dali.zdqjudy.top/Article/details/gt2hornects.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2vmgrkobn.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2ikaeeial.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2llothqil.html

Go:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2nnheqlbx.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gt2dmumxtzg.html

C#:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwpgspfv.html


<!-- 参考信息 -->