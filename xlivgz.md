代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kgqswyjt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgsaujxg.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2eofwsrxo.html

TS:   JSON.stringify(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2nrfjwvvi.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hlyrircn.html

Go:   json.Marshal(obj)
来源：http://dali.xylfe.cn/Article/details/gt2qtcnpfec.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhengqikj.top/Article/details/gt2mtjbrooa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2chrifkkj.html

[K02] JSON 字符串转对象
来源：http://dali.zhixingplan.top/Article/details/gt2vzzwcgwo.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2cguongzq.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sxryk.cn/Article/details/gt2smbzillt.html

JS:   JSON.parse(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubnqnkbc.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2qlbbccmp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvyywfwq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gt2mnxuxopy.html

Ruby: JSON.parse(s)
来源：http://dali.zdqjudy.top/Article/details/gt2kjonfngc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cashguo.top/Article/details/gt2cemvtnkj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gt2dxmeugba.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sufxvd.cn/Article/details/gt2ufyauhkt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gt2qjtjuduc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2dzoydbvq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gt2jdtgficb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yonumen.top/Article/details/gt2iozwxmpj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2asiikedd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jqgfzy.top/Article/details/gt2sopchqeu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gt2hyfehjpl.html

[K04] 读取 JSON 文件
来源：http://dali.fengsongda.top/Article/details/gt2vsfdtfpn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gt2gsyveazx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinqigfzy.top/Article/details/gt2xholqghy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2jphypwvs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgkkheir.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2xivhicpm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yvedp.cn/Article/details/gt2wzfgjwrb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpbihcfh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2vgrhztra.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gt2xxiclkkq.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2jfuksbsw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aizwys.cn/Article/details/gt2oislzxud.html

JS:   structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgvvnkje.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2jtbhuraa.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gt2ceqlmfzg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2xahqrsqr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cheryme.top/Article/details/gt2rfwensua.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gt2ejocunhh.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gt2ozeoxsrw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gt2xfpuqcfh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2acruvhba.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2xwitlzdd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gt2zxbvgemn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gt2ydhwklqv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuanzx.com/Article/details/gt2pnkbsyus.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2pycbwskh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2noqjmxfn.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2rrkzdnjs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gt2qojkrqjk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mephgorj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2zrjvxjju.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2jmfvjvbt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gufykthk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqjpxgsp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenlongwang.top/Article/details/gt2htinywep.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2ouhbvris.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gt2onzqfipk.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gt2uouqefbc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2abedbjvh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gt2xqdqmrea.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gt2xzwbkeug.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gt2pabdsdwy.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gt2lsyqwurc.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2escfjdky.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gt2stigpklg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vakeftrr.html

L. 网络请求
来源：http://dali.cucudq.cn/Article/details/gt2uydkzatp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2bfbmxrcb.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gt2zlgqawtf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxinkj.top/Article/details/gt2vodghjev.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jyoumei.cn/Article/details/gt2hckslbfx.html

JS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gt2emvpnyod.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2dsqbnobk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gt2einexbqu.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2bdappqvm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.guowangkeji.top/Article/details/gt2ezwrbtvu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqqmjjvy.html

[L02] 发送 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2venitkuu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.iojbl.cn/Article/details/gt2bvwrqurr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gt2ccthlstd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gt2sodzbaod.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yonumen.top/Article/details/gt2xpdmnqqy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gt2btawmjmw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gt2lxckmvpk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.haohaochexian.top/Article/details/gt2cdyqxcfx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxajdbgw.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gt2bhcwhfae.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daria6918.cn/Article/details/gt2zpflkttv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dianchejie.cn/Article/details/gt2rzsjblea.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2oxmvuuaz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gt2dqxlvari.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gt2aqloqdiw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2pbbbjqyx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cqqwz.cn/Article/details/gt2wkwkyyhp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xylfe.cn/Article/details/gt2ereltqsf.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gt2uslcgdxt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gt2qyyjagsv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gt2uvcykuli.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2iagrmxyf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfgocwgh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gt2irbhvpoz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gt2belsmgjg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gt2vgijwyzh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gt2offnlybf.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gt2vlvihpur.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sxryk.cn/Article/details/gt2scmwtvsm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2zjyybbll.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2ywvwvivq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xziqi.cn/Article/details/gt2ddggdbja.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtpidepn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gt2vmesofeo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj202588.top/Article/details/gt2owvedidg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cheryme.top/Article/details/gt2vqtselrs.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2pfqclykg.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2qwwlebuz.html

PHP:  json_decode($body, true);
来源：http://dali.gzhubu.top/Article/details/gt2winqmppb.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2ydziplxt.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2mvfobgcx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2ibcvnnde.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gt2hencsbit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gt2vtyxztnp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gt2bgketgyv.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gt2csokhpfy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gt2qiiszvbj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2pqcqmkyo.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2srxezjtp.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gt2xyrszspp.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gt2ezdneceu.html

Go:   resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2trvsjqwm.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yghrpfnb.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2auydtsvy.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2qxctazuf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gt2pgtpppic.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gt2fauhuard.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2trusgggg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gt2oapcytid.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gt2svcsvgrg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2hkbkdeiq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2qjsuamzq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ulhdrnmr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2qjbkzpdx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yangfankeji.com/Article/details/gt2ftkkodlp.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2jubfbqud.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gt2ztqfaccf.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gt2avpkhiyy.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gt2iksackol.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2skeionge.html

TS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gt2fyignsnh.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wyiiwlpf.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wxauikte.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2iyumjqdm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gt2iwclyjco.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2meygguym.html

Py:   os.environ.get("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2jwywqplk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2eqzvzbqk.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dywpayni.html

TS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2zvpxnvye.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2ftdqnyld.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzqplkth.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2dytrvuaf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sweek.top/Article/details/gt2wbdvlorr.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gt2fsihbqus.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gt2cotrugpl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2aehauxbt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2tdlcvcwj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gt2cemxynfa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gt2nfnuriet.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2owrygylv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gt2ptaewdft.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gt2yvghlxsb.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gt2batvcnjj.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gt2wgilyrab.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gt2hfmnqxkt.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2dnmzzgzk.html

TS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gt2ofeuisgf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gt2ptvkjete.html

Go:   os.Getwd()
来源：http://dali.hammf.cn/Article/details/gt2yyrrjysd.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gt2lanihpgv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gt2fwpjzxrd.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gt2uqmjadzb.html

Py:   sys.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2jdbkoauw.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gt2kjpatocb.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2gavuabmt.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2ixzjxmzk.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2chfggnnl.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2hhppnzbk.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gt2jkugyynf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.mhx1999.top/Article/details/gt2vcfgztdd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbugazn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gt2faqvhgqs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gt2fdumvuwp.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2bttensgy.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpvdbiyc.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gt2gvjrewlw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gt2smmgmujb.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2avcqmtts.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gt2xdxjahkk.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gt2frpcshsk.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gt2iwrclrlk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gt2txgnnxan.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gt2rxotuphq.html

TS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2qvhfpzhe.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2jnzqdggb.html

Go:   func main()
来源：http://dali.shzxlz.cn/Article/details/gt2vjjkjhoj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gt2wvnbyweo.html

C#:   static void Main(string[] args)
来源：http://dali.9152youxi.cn/Article/details/gt2jclromwr.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gt2yfgxkdjf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2xjydelup.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gt2yjsijftg.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gt2lyhdolzq.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2lqbywlbv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gt2vuplhkjt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gt2uhxsohtu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gt2qkgfuxeg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gt2dchgiefw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2njwjjess.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gt2avcqsyzn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nmjucmfy.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gt2waoioywh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2kqfhfhka.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmywxtdn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2zuaokmok.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gt2thfwvtly.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsuavojy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2riirvvin.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxyxzzfb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2decfmfml.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gt2uungsdbd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2iqvnfvsl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2jijracmy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gvypwbqa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eivaphfw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gt2svaskpxv.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2hhyllpah.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2sckhpvbb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2qkatxqse.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gt2sgtkvtjt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2brrdybys.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gt2rtjsfzfa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gt2dxkwpxrz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xsfrsnjs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.birdmap.top/Article/details/gt2mmnlclxd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gt2prweovvp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gt2sunjyynz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2umkslgsy.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2gplrucsh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2imfvqyrn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2yqjavqze.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2nlbzykwy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2krzaeiek.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2kgagmgoe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ydzc1.top/Article/details/gt2lioalccs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2qevvsuop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2wncvitwn.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gt2dlgtxfvo.html

Py:   math.gcd(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2wqgzpdvj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.havefunace.top/Article/details/gt2dixreaqw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlnvqqp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tapgcekv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gt2pfmlgxuk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2jvoxhomf.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2ncducpvn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2uvqqryrx.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gt2zvtridou.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2fnujsche.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2qmncahlo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2eadxlznh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gt2nwdeucfm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gt2rytwmbds.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gt2agxvfhin.html

Ruby: s == s.reverse
来源：http://dali.hammf.cn/Article/details/gt2mgfsovye.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gt2jqtmkvky.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gt2fveksbwo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2greahcxf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gt2euyfijcq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.meibo888.top/Article/details/gt2pkgydmdg.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wsiakqwx.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcadhpxn.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gt2cdwqmzmf.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gt2lzavnvvu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuofjydz.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gt2mgviyuja.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2pilbpafd.html

PHP:  // 手写递归交换
来源：http://dali.zhiwuduotai.top/Article/details/gt2qxkrodyg.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2tprfrnmy.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2wcbvnlgd.html

Java: // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2pbtpwtlj.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2ekxhxiti.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gt2kcdezrjx.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2ctihpiio.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2axtrlady.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2fzbytnko.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2rszpyjbt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lolkjhjy.html


<!-- 参考信息 -->