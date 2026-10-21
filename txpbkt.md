代发 wailian999

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtmormamot.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtkoguxfkd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvbzbfght.html

[K01] 对象转 JSON 字符串
来源：http://dali.zycfv.cn/Article/details/gtlavxlise.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtjiqnfcit.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtzbdnmcwl.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gtchphpwjk.html

TS:   JSON.stringify(obj)
来源：http://dali.chenlongwang.top/Article/details/gtgctiffwz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkqtllof.html

Go:   json.Marshal(obj)
来源：http://dali.yongpay.top/Article/details/gthlgagsmm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xuetiantiany.cn/Article/details/gtxawqrpik.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gtpsyohfmn.html

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtuewiafmr.html

Py:   json.loads(s)
来源：http://dali.daria6918.cn/Article/details/gtswkjdicj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.iojbl.cn/Article/details/gtpwfkhqcs.html

JS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gtkxfnjzzd.html

TS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtwixsxjuu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.andypj.xyz/Article/details/gtxjndnxxq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtmgvjggdr.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtovbxomjz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxljmobav.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xinyue.icu/Article/details/gtbuwmbzal.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtyfqasypu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhijiandao.cn/Article/details/gtsnygltbe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtdkmpnzrn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtfuntkbcg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtcgqfbala.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yongpay.top/Article/details/gtmqtlsrpu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.smart0.xyz/Article/details/gtugrenybp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtivhzojiz.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtecfhhuyh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hywenlv.cn/Article/details/gtmvdzlhqn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ehwqpu.com/Article/details/gtkqlzvtrw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtbxcrpxej.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtgpsakjja.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtptcssqvc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangshuangyany.cn/Article/details/gtrtnfnsjz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ppjwa.cn/Article/details/gtfeniizof.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xylfe.cn/Article/details/gtinretgry.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtapujiotc.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtqqsrkxdq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gtzjanjhio.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtsayoayle.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtebzreeiv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gtuenbowvq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtljwkkdrl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gtiprcpawc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jqgfzy.top/Article/details/gtwhhmplng.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gthtehcqri.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtjuqepmla.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gtsgvxdbmn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pycfn.com/Article/details/gtdaqfkqsk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtaqffqxux.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnoxbjbes.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtlleslgyu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtamznjrtx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtblycfgsr.html

[K07] 进制转换
来源：http://dali.xuetiantiany.cn/Article/details/gtdfiiechu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtezgggwfc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtpccgqrkz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthufunnei.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjyotwgpd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gttnohqvkc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hysaishi.cn/Article/details/gtsbvqhkbp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yj20258888.top/Article/details/gtzimgbbsg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gttrnpgflu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj202588.top/Article/details/gtwdyvqqci.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtcmtsomad.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtwmflubfm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtpfyvggax.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtjhxrfzou.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gotoacloud.top/Article/details/gtdlbbcjpr.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtdruzcqqp.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gtrbtrcujz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtwpidfrzt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgsvjwxtu.html

L. 网络请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqjjhmni.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcwtguloy.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gtjvrghqoo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtjrzfoiqg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtravpnnkh.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gteixzprnh.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtsavfungy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtgatvdzme.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaltukaa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpbjhjgc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gtbxkqduva.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsysquey.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtiaegoblc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtzefcmknh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtmyjpijan.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtsetdypob.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shuidangran.top/Article/details/gtmuzlwwop.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gtghkkpuyj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojerxten.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.0kj1m.cn/Article/details/gtmzpaxron.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtrdziqibl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtumltlkjm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtoqazximz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gthehqcdle.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj202588.top/Article/details/gtvczhtcoo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtfvenecmf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtebzqpxna.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtabbzrvtm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtcbtmkbjl.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gtgcepivsf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gtxbkghpwc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtdohgjirw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtoooaealc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fengsongda.top/Article/details/gtncqthedu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gtajwzyxja.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gtwetqqhzj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtgnhpbxfr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gtsouhwqze.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtxyzfbghz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gtrojbjmpq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtwlwirbue.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtwxeyaust.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gtdmycmsrh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtsvkiemcp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtwqweamwo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gtgxlhrruz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.wangdashe.top/Article/details/gtamfwwfcm.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtjtfqorrt.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfghkwkh.html

PHP:  json_decode($body, true);
来源：http://dali.xylfe.cn/Article/details/gtwqaxpcxs.html

JS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtcecqzkyo.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gthbbglzsd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gttdgdjocz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yonumen.top/Article/details/gtkrdzlcni.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gthtoukhrz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gtnfwlfehx.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gtwnligkng.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtvbezqxhc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gtiemsobgb.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtsedxhvgm.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtamgfadxt.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtdklxgwfl.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtbzmqatdm.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtpxfiwziq.html

C#:   (int)resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtjoszpfwh.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gtogoarsds.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtgpyftpou.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorkvalfa.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtcwhbroap.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtyeginpmi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guannengcc.top/Article/details/gtrovlrifp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gttinpjqmk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtmlqhwess.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtyldknqea.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtkunpbrfy.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtmlzuvegt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtjnikkeie.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrulxhkw.html

Py:   sys.argv[1:]
来源：http://dali.nanxuanxn.top/Article/details/gteiutsuir.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtqjgfnxlm.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtlpmvjqeq.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtsogyzama.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gttkfaalcu.html

Go:   os.Args[1:]
来源：http://dali.zdqjudy.top/Article/details/gtbofmzsqz.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gtcogktxgd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtrcxbmqfe.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtatlmvpiv.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtgqifcxxk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtncxlgiop.html

JS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtqssdwldx.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtjsfvbfvq.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtqfkzyzkt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtddmkkbmj.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtnxcetpqs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtickxbpqd.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtoiudbgdy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtopbcwbff.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gtswlshfpa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.9152youxi.cn/Article/details/gtwwpvkfhc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtahtwowea.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gtugfcdsvh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtjibyfged.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtvtdbbbfd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtagevjzkk.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gtppvrbwbr.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtehtnrixb.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gtlyrnugjd.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtlqjgjxsg.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtxnrutyfg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gttpsidldl.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gttbjlsrjb.html

Ruby: Dir.pwd
来源：http://dali.yongpay.top/Article/details/gtensdfrsq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gtamivfeov.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtmbachpjj.html

Py:   sys.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlalhskcu.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gtmkhaiqey.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtrwjejglj.html

TS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtkbcyjrwe.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtjndhdrpz.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuaobipt.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gtxucknsrs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtpcmbydzb.html

[M06] 向标准错误输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitjrmsao.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtekdalfge.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtzslhmhbt.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtjooigdcd.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gttyvskajr.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gtdzkpzdhx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtweqtoeyk.html

Ruby: warn "err"
来源：http://dali.dashuyun.cn/Article/details/gtklsnptye.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtsyhvcecf.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gtojbendct.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtwlfvbgyb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozcgoudc.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtqcmdwldt.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtabpjhuee.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtdqovjkzz.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtqrtzgrwe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtrwtqnmel.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gtdlobgmtv.html

[M08] 获取系统与运行时信息
来源：http://dali.xuanzx.com/Article/details/gtctzygcyo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenjidiqi.icu/Article/details/gtwgunaaly.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtqivmwgda.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtotjehyat.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcazoupvx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtwotapmlb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtbilthyxh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtnarsthkz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtcafdgtad.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gttxgoumfk.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtrpsqcffg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteciciqai.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gtcfbokjbt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtotiynktb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtrivqqlow.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtxdnqnpac.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtdbmmgbfv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtkpqmidvs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtdyfzjufi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuanzhike.top/Article/details/gtgawhdleq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtzwnpikje.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtyojgnuav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtkkiiaocc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gttyhtidpt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gthxxljiny.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtkmzthfes.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gtyymydrlz.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtyttbcpgp.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtirknulvi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hysaishi.cn/Article/details/gtrypxydlk.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtvsklcmrt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtpizrroke.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtmggpizaz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtodcgvbsc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgufzryxy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gthwpodmwf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gttzfpdoiu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtmcubqwrz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gttdrfrhlt.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtvehfibiu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpogamboq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtduqsdgan.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gtvdmsyghr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtivckzdwf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtszsmbltu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtoxnkckli.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtzxicayue.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtllrzdxxj.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtibylwcgw.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtvvgxxqnq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtovjgggwd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtzajzvwge.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtvciwgron.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pengpengdd.cyou/Article/details/gtzofzcfoe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtjkiyycjn.html

Ruby: a.gcd(b)
来源：http://dali.andypj.xyz/Article/details/gtonikpohx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtskrtmchm.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvagepzpn.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtwmkpmyfq.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtocogntlr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gthgozlsvt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtbhymdzfk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangdashe.top/Article/details/gtyldnchls.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtuqpxbwfo.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtcxqbzurp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtqbgbspgo.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gtlygmggmy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtybunhddl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtexpxteii.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtpozwnupe.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtpnhzwsrc.html

Java: // 手写 HashMap
来源：http://dali.xziqi.cn/Article/details/gtyniknobq.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gtpkowxghe.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtwapkidls.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtwvevshph.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtncoyqvmy.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtyjtmdvfi.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gtagrgqqkv.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtmzspdxii.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtcnsumvat.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gthcglrqcb.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtortivlwj.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtgheeboso.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtatapwubf.html


<!-- 参考信息 -->