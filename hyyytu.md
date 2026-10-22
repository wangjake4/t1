代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgslovxf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2rzeejpzt.html

JS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dfqfesbu.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gt2jwlfmceo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.9152youxi.cn/Article/details/gt2nldzkhis.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2lirkkqgg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.aizwys.cn/Article/details/gt2oqzjclok.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cheryme.top/Article/details/gt2seyrckmo.html

[K02] JSON 字符串转对象
来源：http://dali.yongpay.top/Article/details/gt2ghbfozhj.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gt2iqwukeyh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhixingplan.top/Article/details/gt2ntdbyvsk.html

JS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2zhzpdfad.html

TS:   JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2nfgjefsq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.redwolf501.top/Article/details/gt2qtttlujr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gt2bqaujjmu.html

Ruby: JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nibcglvx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gt2jfoowrgp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2xwsbhpmn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvbrcnhp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nanxinkj.top/Article/details/gt2vchjgyln.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2iijahijn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2dfjzkgqn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.smart0.xyz/Article/details/gt2rplpjqrd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gotoacloud.top/Article/details/gt2yuhxegcv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yebobekb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gt2qodlzksq.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gt2ysnejpcj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2pkhbjrhc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gt2zlaukfaf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gt2khugdczt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gt2khrnkjmv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gt2tmimkwzd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gt2aaurzpkn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsmfvuc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gt2mgzmszba.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gt2eprwxgvw.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gt2drtjqbcj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gt2lvthynvt.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aupfsdhq.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2btkptsgl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mddhldss.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gt2pigeryvb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gt2fcylumuh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gt2eayxyuow.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gt2dzqvwmzk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangdashe.top/Article/details/gt2igtgemrd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hysaishi.cn/Article/details/gt2jlssksfe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gt2nyddqxdy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gt2wnlvlazv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gt2tsqeifif.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gt2oyozklgq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2yghsiuar.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwkcvjxe.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gt2cwtgdtvy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2rcqngvar.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gt2obnuqzxm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gt2ffechgxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpgrmmpz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2tdvqjfxp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gt2tqxyaibb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gt2klwpttdk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2atcfbuxu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gt2aultaxxr.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2jwukayxu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2bwissrnt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2ivcfqiyo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gt2ceugfawq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2ikrsvwow.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2ovbqklkv.html

Ruby: Marshal.dump(obj)
来源：http://dali.gzhubu.top/Article/details/gt2jyrlmmdy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2lffovqze.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2vqotrjor.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gt2mciubevt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mepqeuer.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gt2ftxtqzed.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nwbrower.top/Article/details/gt2vgykngly.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gt2taardjky.html

JS:   await fetch(url)
来源：http://dali.xziqi.cn/Article/details/gt2ztedmpeh.html

TS:   await fetch(url)
来源：http://dali.guowangkeji.top/Article/details/gt2vsokagrd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2tavzvqnb.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gt2qhiaeojl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gt2zaevhbbr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfhrzzxy.html

[L02] 发送 POST JSON
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnufgbfs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2symrhymr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gt2ouzyelhz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2hpwgsylv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uoomuflj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.daxiang520.top/Article/details/gt2wkecovwv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gt2tzojqlsk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zdqjudy.top/Article/details/gt2jyuwjjsr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gt2ukdsxkrd.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gt2nxmyuogi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gt2wjvkosgf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2kqkpcrkm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2hxswndck.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2ungjoirk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yongpay.top/Article/details/gt2wmxnlaxp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2zpsbcbna.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gt2grjoohvb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qucbfnyg.html

[L04] 设置超时
来源：http://dali.yongpay.top/Article/details/gt2dmbxeooz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbmixqpk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gt2wchxymby.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hammf.cn/Article/details/gt2fgbszbda.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrngcued.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dashuyun.cn/Article/details/gt2mqdyvkfx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhoulong.xyz/Article/details/gt2ujqwxvwn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gt2psixcabo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gt2nqlsiwjb.html

[L05] 上传文件（multipart）
来源：http://dali.tanke756.top/Article/details/gt2klyxkzwo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqyfglfb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2nmmctaju.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2hoeqwhdx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2weroqozh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gt2hkizrceb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gt2lhyxwfef.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2oryjrfoy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2gpllytgy.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gt2fxdqkahz.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2rapnuniu.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2kdeejwva.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2raviguzg.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gt2hnonayip.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2xlpkjrpw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gt2igohfhol.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2tfeinwim.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shuidangran.top/Article/details/gt2jmkmlhzy.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2yxubqbbx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2twmulcbp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gt2mpoyoklq.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2yazxrpqm.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2mueambey.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gt2vcwwsqcw.html

Go:   resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2yputiixw.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2loszihdp.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2racswyqd.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gt2jslsfdjo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gt2ndytuklc.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gt2ynbzmzly.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2bswcnzrl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2lrbknwod.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gt2rpoemnyl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2yxdihsyo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2fgteqlvb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gt2jxyddatv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2dbbgrvaj.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gt2fqvgljmy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dtpyznxl.html

[M01] 读取命令行参数
来源：http://dali.xuanzx.com/Article/details/gt2uroxteqh.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gt2ryzxoodh.html

PHP:  $argv;  $argc;
来源：http://dali.redwolf501.top/Article/details/gt2adwmszxx.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2yibneowc.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2dkkrqfwf.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2pdwlndyz.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2nysvbenx.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gt2ydcsfuht.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obmiplau.html

[M02] 读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2irernfcs.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2yqivzgue.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gt2ccttybub.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2chpeplxr.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2lpnrbziz.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2uujxjdej.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.birdmap.top/Article/details/gt2fkwpvbyd.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2qexrohhl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2xllffyki.html

[M03] 执行外部命令
来源：http://dali.yuanzhike.top/Article/details/gt2ehqwojzo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjrshemj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gt2qijvrezh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gt2mhcfjclh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2kewbincn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gt2vlprwvvy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gzhubu.top/Article/details/gt2zohibidn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.andypj.xyz/Article/details/gt2odqkhwzx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ivvv.top/Article/details/gt2yzfwlvpy.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptdjvlza.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2jonvxxuv.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gt2pjbmnvhw.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzfzozve.html

TS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2enkvgkjh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxlrkuna.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2psrbwdho.html

Ruby: Dir.pwd
来源：http://dali.chenzaomai.com/Article/details/gt2pivjrxxr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gt2lrntoxhc.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2ejljxveh.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2lxarnzbu.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2yxufjuzk.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ldetxreg.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfyoupwe.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2hhjpapys.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ykdfxsac.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gt2pmtcxsll.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpgljymv.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gt2eskmymzz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2blsfowgi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxuanxn.top/Article/details/gt2kpurqgnb.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gt2bbxbmduo.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2qqnwtbgv.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esgdparv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gt2uscfzsze.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kszrwvsh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gt2xfmxsnii.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2jkthrwve.html

Py:   if __name__ == "__main__":
来源：http://dali.xinyue.icu/Article/details/gt2vdjewdez.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2haatwsmj.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2htegikst.html

TS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2htdzpjln.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gt2nnhizzjx.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gt2bhpnolmi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gt2wrumsihc.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gt2cqtjocta.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gt2aingtvtk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2pmwubvjc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2xfrbftbt.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2ldmlwjsp.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gt2mzjirxmy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.snrcjt.cn/Article/details/gt2arwjbbtq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gt2bhvqhcqq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gt2mwjrbmpz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gt2dvtgqgqm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2rplbohcc.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gt2djxiipkr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2husubnho.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2sqjuaqat.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2hxaiwyrr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2wdcnntke.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2kokhkrzd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrogkky.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2dfuyldoy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2epjcnzkd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2epjrxnlc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2bdfednjz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shzxlz.cn/Article/details/gt2ajvoqzfb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gt2rgkixgmx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gt2izuksffx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2jflfxipr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gt2nrcrjlie.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gt2tiypxvkb.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2qlubzgqg.html

Ruby: arr.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xixwfdtl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.bjfxy.top/Article/details/gt2lbiexoit.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2pjzwtqyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2tysotrqh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.316326.xyz/Article/details/gt2hxjzfono.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2gpfemaxn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gt2fcmihayl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gt2dxlvbhmg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gt2avvrupud.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gt2vvaqkkux.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gt2aamyhmwn.html

[N04] 斐波那契数列
来源：http://dali.yanxiufei.cn/Article/details/gt2cfipttcj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2lgvonmtx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2amsihidh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkfbghn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2zbcsgvra.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gt2cgggkscf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxuanxn.top/Article/details/gt2mcdodcek.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2cosqticj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2zuibvfpu.html

[N05] 最大公约数
来源：http://dali.ybcxt.top/Article/details/gt2qtyofvbe.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xywouzle.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gt2zfxkpakn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2nwowcmwk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qzxnulpi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2gxhwohts.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zenqabbp.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2zwshcxew.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2arzjnzlp.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2vnrixtrw.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gt2okvkdrjd.html

PHP:  $s === strrev($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2ojzgbeal.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2cjaztvbh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2zwdtemro.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gt2ugxqkqpb.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gt2bpfjaols.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2ryynfzwb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2njcmompd.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gt2ylchzlmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.vqdsnc.cn/Article/details/gt2adecwrvn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gzhubu.top/Article/details/gt2nyrkvqfm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gt2ocfhiruh.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gt2rksbqcyg.html

Java: // 手写 HashMap
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2echktayg.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gt2dxtyzush.html

Ruby: // 手写 Hash
来源：http://dali.sweek.top/Article/details/gt2vutmoonx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gt2vtifasuf.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gt2exwulbym.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gt2dcjmsmkk.html

PHP:  // 手写递归交换
来源：http://dali.cashguo.top/Article/details/gt2fbsqxuol.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2jzwqzooy.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2mdqpdbqs.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2niwhohix.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2lhjcguzt.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gt2aohtdfnd.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2jifbjolg.html

[N09] 栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2zoxwahjr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gt2vogcuqnm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2ynrpvgwy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2keuxvums.html


<!-- 参考信息 -->