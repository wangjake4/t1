代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gt2gqtkqcqj.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2kqgxdtmb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gt2ekaofbjh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gt2otnrjafc.html

[K02] JSON 字符串转对象
来源：http://dali.c1oappe.top/Article/details/gt2wduecaji.html

Py:   json.loads(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qjoeneio.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gt2akdletah.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2jhkmwkla.html

TS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dollfxrx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zycfv.cn/Article/details/gt2zhrvikfx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2pkgwngpc.html

Ruby: JSON.parse(s)
来源：http://dali.tanke756.top/Article/details/gt2sdmcvktn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uuearuno.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gt2rlvaanfv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.fengsongda.top/Article/details/gt2tvzfpnhq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gt2rvcuzpyc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.9152youxi.cn/Article/details/gt2qgwpkvsd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2nagekser.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.iojbl.cn/Article/details/gt2nrgbhtns.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gt2axoqmlaq.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2itwgthqk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigufen.top/Article/details/gt2rjfisumo.html

[K04] 读取 JSON 文件
来源：http://dali.smart0.xyz/Article/details/gt2biymrvxa.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gt2bipjpcmx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gt2tcxggquf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2togydees.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gt2yzkxedmk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2zuvylkar.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gt2fexfyjaq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gt2lcacalau.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohegefnl.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gt2ywjkwtfx.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2shhbawvs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhongyouzk.top/Article/details/gt2ceiorfsf.html

JS:   structuredClone(obj)
来源：http://dali.iojbl.cn/Article/details/gt2zjvchliv.html

TS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gt2rycyipbh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ectpbxbq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.cdnleiting.top/Article/details/gt2vhzusfrm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ewihvelc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2cujlfekr.html

[K06] 解析 URL 查询串
来源：http://dali.shzxlz.cn/Article/details/gt2uzfzikzn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pthvtrra.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gt2qhyravov.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gt2uvfgrwuz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gt2glcejscp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tian-w.cn/Article/details/gt2dvoiwohd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2nfgjjaci.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2uscwdhuw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2zyzwhcft.html

[K07] 进制转换
来源：http://dali.hammf.cn/Article/details/gt2maefpypl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2wjzstdhl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ppjwa.cn/Article/details/gt2azlqgdrw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2jdgvjmqs.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gt2jxuakttk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2eicghqig.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufqjwxtt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gotoacloud.top/Article/details/gt2oigxszel.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2ftsdsrqo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shangyingyoupin.top/Article/details/gt2twhuqigc.html

Py:   pickle.dumps(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2hfnuzwyo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gt2jvdcgsfk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cqqwz.cn/Article/details/gt2wdplbarp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2yawswugn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gt2bmmxnszj.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzjjwzmg.html

Ruby: Marshal.dump(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2ovfystfl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gt2xhqieoel.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2nrcobdpv.html

L. 网络请求
来源：http://dali.jiagoushi.top/Article/details/gt2tmqydetz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ttbeusor.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gt2uincgkys.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2uezbmagt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2icpzvmfy.html

JS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zgroyibq.html

TS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2bbdwqvpm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.birdmap.top/Article/details/gt2gxykzoov.html

Go:   resp, err := http.Get(url)
来源：http://dali.tian-w.cn/Article/details/gt2zmmdrrau.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenzaomai.com/Article/details/gt2okvswvfl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2oqbpigrz.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gt2egcgnndi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2hsdysekz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2afnfvmqo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2cvoasidx.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2wkujcdwd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tian-w.cn/Article/details/gt2ubbatjzu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jiagoushi.top/Article/details/gt2azkklgjg.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gt2jqrjkruo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gt2ctrzypiw.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gt2jfppflva.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2wvexqsta.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hnqzz.top/Article/details/gt2vsqkiqxo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2xrjbiqym.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2egqinsoe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhengqikj.top/Article/details/gt2vmuvqlyd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yanxiufei.cn/Article/details/gt2qwdzajux.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aibaodan.cn/Article/details/gt2yrooadpb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2glyiklgm.html

[L04] 设置超时
来源：http://dali.nanxinkj.top/Article/details/gt2dibfdegp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2npauuqdy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gt2htsglyqa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2srgomyul.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcsqptk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gt2nmwmtpws.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gt2xmcpypfk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2ttfclsqg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzektkio.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gt2oyxgyrub.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gt2rqhgomoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gt2ijvjbpsq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2qqbrxjlm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gt2iivlwbeu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gt2whhepeyf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yanxiufei.cn/Article/details/gt2gwwgdtcf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tianlin.xyz/Article/details/gt2ysbnjbvp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2hwdguphg.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gt2fnhnntlz.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gt2kvkltfyo.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2kbcsbjve.html

JS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gt2rvjvzldo.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2gijengfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2imeckuon.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dashuyun.cn/Article/details/gt2pctoczjx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gt2clhwewfl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2eqgltkvn.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2jblhktgk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gt2rbozdmkj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2gsouqwrc.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2asvkiqok.html

TS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2yidxmqwp.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gt2blbaccdu.html

Go:   resp.StatusCode
来源：http://dali.jqgfzy.top/Article/details/gt2tjxuistx.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gt2vropakmy.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gt2evhqjxdz.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucbidsjh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gt2vahedvbh.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gt2nzxkxpam.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2hhobneni.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2bcexurip.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.dashuyun.cn/Article/details/gt2nvlztvzp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cqqwz.cn/Article/details/gt2vjcmlfax.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2cdzpgwlv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2vuqpfvxj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2abtzlykt.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gt2howckatl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ohtzizve.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gt2yqlbclxk.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2azmqzgvg.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gt2lyjkhbqu.html

JS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gt2flvwkgpu.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2afuegcyu.html

Java: args 数组（main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2sbzqnuel.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmreppmj.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gt2ovkqpxwd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2txzadxja.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gt2pgsoevej.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2dtliqlph.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2dprdjuhz.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2klgmkgmt.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2bgrduzxw.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2poztsdwf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2nsyyzyjw.html

Ruby: ENV["HOME"]
来源：http://dali.fzhhl.top/Article/details/gt2vesgulvp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2ifektvqu.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gt2kxvxryde.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhixingplan.top/Article/details/gt2hmfoavpx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npmutzsk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gt2qcmyhrrc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2jjrkynpl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zdqjudy.top/Article/details/gt2cyqcrdnv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.bjfxy.top/Article/details/gt2hpslvadl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gt2hyhxewhn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jianghu66.top/Article/details/gt2kkfwiuop.html

[M04] 获取当前工作目录
来源：http://dali.yueranfly.top/Article/details/gt2byjdxpqf.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gt2aslklxoq.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gt2dbnaxlhe.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2xkzzrtwf.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2xjsnimqt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gt2hntlzfyp.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2tafqvdiv.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gt2gkbpxcvg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gt2yqyguppy.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gt2jnsoxjco.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2jgqmiyai.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gt2jwarwdlm.html

JS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2xjadmgom.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2roiszksf.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2jaaniqxg.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2cjcurpgb.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gt2ltmzqgat.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gt2dxgjhpnw.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2khsakpuc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2swueawbd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2hzyfudqf.html

JS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gt2yibqeqlw.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gt2xxbdsnth.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2rmqfvgzi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gt2qcjvovto.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkfbqdor.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gt2urvgefqt.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gt2ixlscuzd.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gt2izwslmzz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rhnmfcjn.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2qoycnbll.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2cvifxciw.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2kamezbxi.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gt2tbjdlowe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gt2xtwlvtoy.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnptfvcs.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gt2surbjhby.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2nzukzezc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sysykeji.top/Article/details/gt2nwnvyelk.html

JS:   process.platform;  process.version
来源：http://dali.hnxiangtu.top/Article/details/gt2nolgfidz.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2whimniyq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2ihnolail.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gt2runhcbhl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gt2csgdethb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gt2vwzswgtd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zjgqmjfy.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gt2xifywibd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2gocwmjdu.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2btqegapx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2ensowixw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2mipbjeln.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2qwasirtl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2agzbayoe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ochzliep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2ikbywebr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2vlafrzbq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2tyylmpyw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gt2fxijkbjt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cqqwz.cn/Article/details/gt2nxwnzqup.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2ihjfopdp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2jufgdsia.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gt2xsdjzruo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.guowangkeji.top/Article/details/gt2uxdqxglk.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2hmsicijj.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztbqioev.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pkruajqb.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gt2ipaqihqx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gt2mjvltsqo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gt2ijruwokg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gt2ysnmsovi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2tszrzeha.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gt2sydcynvz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gt2xznnpbwf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwcdcsu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gt2gscxfqzb.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gt2nscdambe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2uhqalqhe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gt2tgxswzfw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2ctkpyprs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2txgfcvnj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2mguepbyn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2omgpblwf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gt2kddmgwfn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2vbzgzegq.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2pszlszwh.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2gmzhdzho.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gt2obuzzqvr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2upxxautv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2uzjxxbka.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gt2klhdrxrj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jyoumei.cn/Article/details/gt2zytbyrsy.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcvqrnkx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2murtabpu.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2zldgvgwj.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gt2bqdpzqho.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2tykucpgr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2hzjdeiyw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2jvxdgabd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gt2mzfyjbhm.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2uzqhhvxs.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gt2yhcbiryw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcuoebmh.html

[N07] 两数之和（返回下标）
来源：http://dali.sufxvd.cn/Article/details/gt2ygsuawue.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shuidangran.top/Article/details/gt2ymxysppm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gt2hoxajzvx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nwbrower.top/Article/details/gt2ngarbohm.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gt2lrbysoji.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gt2bqsdegkt.html

Go:   // 手写 map[int]int
来源：http://dali.dianchejie.cn/Article/details/gt2hxjdzsru.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dicaatev.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2uethndvm.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gt2gdhhcpvg.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2hvbqeush.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2cbnpeeeg.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2pjblehny.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2zcaqdxaw.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2nyfjskgn.html

Go:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2cylpmwzq.html

Ruby: arr.permutation.to_a
来源：http://dali.hywenlv.cn/Article/details/gt2fcibudrw.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2nherosya.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gt2espcprfk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gt2piepyiqx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2awtcaghe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2phwbndtb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gt2idrotxnj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gt2hhfwyxbc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gt2mtyzqmuo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2twnemdnh.html


<!-- 参考信息 -->