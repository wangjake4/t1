代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2zavnammx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbztyppl.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gt2coqcdvkr.html

TS:   JSON.stringify(obj)
来源：http://dali.xylfe.cn/Article/details/gt2fybkohpb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hfpthk.cn/Article/details/gt2yoyzbkxs.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msyiozlr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gt2gmmpjjij.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjzzkgms.html

[K02] JSON 字符串转对象
来源：http://dali.nanxuanxn.top/Article/details/gt2zcvnzrxg.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gt2ebnyngis.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2onxztuux.html

JS:   JSON.parse(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uoielfed.html

TS:   JSON.parse(s)
来源：http://dali.yvedp.cn/Article/details/gt2vbqgqppj.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2njkxxftx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gt2ehmfuafa.html

Ruby: JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2byyamyqx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aibaodan.cn/Article/details/gt2voavpcxd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.kuanghao11.cn/Article/details/gt2wedzelka.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gt2znlrmvnn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gt2vbfhmlqg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sweek.top/Article/details/gt2cugmbczr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2ujiwthto.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2knfcsnov.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gt2ceefqddo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gt2vurinpkk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuanzx.com/Article/details/gt2ovmfjrpy.html

[K04] 读取 JSON 文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2pphpoccj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.haohaochexian.top/Article/details/gt2dfgsorpe.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.svipenyu.cn/Article/details/gt2wejbnfwv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gt2qhjdxbhw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2fwzdyvry.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gt2mzqufhdk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cashguo.top/Article/details/gt2npntnzvq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybrmorvo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2nssbiuqw.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2ifgeqzmu.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrdwnboc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2exsypemk.html

JS:   structuredClone(obj)
来源：http://dali.yueranfly.top/Article/details/gt2kqjzeyrw.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2cbladshy.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigfzy.top/Article/details/gt2smkyxnlr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gt2qngfhwfp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.havefunace.top/Article/details/gt2gdxptohs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gt2ykbscwsr.html

[K06] 解析 URL 查询串
来源：http://dali.yj20258888.top/Article/details/gt2fmrlxxzi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ghxixxol.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gt2aluvhhma.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gt2xjmhvbob.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhengqikj.top/Article/details/gt2bnyjmpid.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shuidangran.top/Article/details/gt2ddjvacnq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2rwyiatfy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vgsvbxly.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2uhmoisds.html

[K07] 进制转换
来源：http://dali.smart0.xyz/Article/details/gt2ngpyxdep.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gt2mcwtkkzd.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2fcbenqui.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cxgscpku.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2iusokeeg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2itlbpmwe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gt2addztzrd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gt2ybfoodjj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gt2eqmuiyda.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gt2zabniyyw.html

Py:   pickle.dumps(obj)
来源：http://dali.xziqi.cn/Article/details/gt2alzqjdsn.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gt2zgnfvwdj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cdnleiting.top/Article/details/gt2ofkdhoms.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzqxqli.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2wgkcnnni.html

Go:   encoding/gob
来源：http://dali.sxryk.cn/Article/details/gt2ibrobiws.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258888.top/Article/details/gt2pquttzjh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2defxyqal.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2mxyzpgbb.html

L. 网络请求
来源：http://dali.jianghu66.top/Article/details/gt2wsaxdnxi.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2wnztasuh.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjjvqzus.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2tiuxugcf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gt2mapbflpm.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2hbxiiziz.html

TS:   await fetch(url)
来源：http://dali.gzhubu.top/Article/details/gt2dpttwvor.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gt2ycnopeyi.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gt2efemsprn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenlongwang.top/Article/details/gt2nrrlkihc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tanke756.top/Article/details/gt2lsjxbnzd.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2jgbgtlzm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gt2gvtqvkcq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2elrburax.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gt2lxohfxit.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2citefagt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gt2lztumzmy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbcmhzyo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gt2ryxvgrzn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gt2uidciuzl.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2khnfmyxk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gt2giclimqo.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gfhqzode.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2pyuajjjy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2temkbcwm.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pycfn.com/Article/details/gt2lefwrazi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2wzefiudn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzavkzon.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2bnbkukrl.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gt2axofekyt.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigufen.top/Article/details/gt2oeficvsv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gt2lgmdmope.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emihksnf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2gchqrpbs.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2zopqnvgh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gt2wknslgbm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yueranfly.top/Article/details/gt2khlfgzzm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tianlin.xyz/Article/details/gt2bbxelmtm.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gt2muhhubxa.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gotoacloud.top/Article/details/gt2hvmpocey.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2nxwkiydo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gt2sutzqssp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gt2kvchnkqw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tanke756.top/Article/details/gt2bewmgdka.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2jliihhqu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gt2xyncptnm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2kturcrlh.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258888.top/Article/details/gt2bewbkimo.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjxlmji.html

PHP:  json_decode($body, true);
来源：http://dali.tian-w.cn/Article/details/gt2inhrbepf.html

JS:   await resp.json()
来源：http://dali.ybcxt.top/Article/details/gt2iiytdxlm.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2cqugyvux.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2nykfwyys.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuptprbx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gt2najlndmw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fzyoojok.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gt2brbbzfki.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yanxiufei.cn/Article/details/gt2eqszgqwo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2snlytbul.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gt2hwljdzos.html

TS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2orrfolwf.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eiwqbqjw.html

Go:   resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2ceuvgztj.html

Ruby: resp.code.to_i
来源：http://dali.yanxiufei.cn/Article/details/gt2lxazlrip.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2nbllchxt.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gt2mtjfrstq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2zvyddzjo.html

PHP:  curl_multi_init() 系列
来源：http://dali.ehwqpu.com/Article/details/gt2ljhlxmsx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2fiiwekli.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxtcvuja.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmqqvgbn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cflwqtow.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2cgtpeuyf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2dmbhtgzc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2oaonuaai.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2gyfehmuf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2vsahsjjx.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpvopfar.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2zpydpecn.html

PHP:  $argv;  $argc;
来源：http://dali.wangdashe.top/Article/details/gt2yqdrhfvl.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eykjasik.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2ngmmdycr.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2wcgeegjk.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gt2triyjxgc.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2woytpvem.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2tdjlbaul.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2jcqiorio.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2atoyspzi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2xwirrins.html

JS:   process.env.HOME
来源：http://dali.pycfn.com/Article/details/gt2abcgtkwp.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gt2imcfyxpq.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2vtkakupx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2ygrvgyow.html

Ruby: ENV["HOME"]
来源：http://dali.hnqzz.top/Article/details/gt2oakwsabt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yonumen.top/Article/details/gt2piixchcr.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2cqbpcydr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gt2lldizryq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gt2htzmuqki.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2ceulmqlu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2spyilwdb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2isbucvao.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gt2uvcvxcie.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpwvutjb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.chenzaomai.com/Article/details/gt2muepoklq.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gt2rrvqrccx.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2tytddcos.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqbojiza.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2vnncucoz.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2vfkvdfgf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gt2ghdgtpax.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gt2gtizbgem.html

Ruby: Dir.pwd
来源：http://dali.xziqi.cn/Article/details/gt2tpbikmeg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gt2czmhapiu.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tlymyxgk.html

Py:   sys.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2tsswxdti.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gt2pmceahzi.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2oesepvsh.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2yfqkvccn.html

Java: System.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2fyfxuhzj.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2usjpssio.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwwblvkh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gt2ficgajbk.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gt2tglsbbsu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2lrzbeexc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gt2rihbhznu.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2xfyhocxp.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2nkiurneq.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2blnsomar.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gt2cappbkch.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2irwcjpcu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gt2xdyjzrli.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gt2qutlkfjf.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gt2cdykczqh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2tpeqyglu.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2anlblbup.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2iwinkvgy.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2yepmqaei.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2ndunruvv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gt2cwaoiqod.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2mwawraql.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gt2pwhkkjts.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dashuyun.cn/Article/details/gt2ztjselsl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gt2ekdlahmq.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2rrqpgwor.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2tmgolybu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gt2taxzxeta.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gt2yidrgfea.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2oneapbmg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2jctdrgap.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2kjltqbub.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gt2hwospvqf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qhsfeqax.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gt2ffzkmqqx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2vrbscqcj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2iqcssrsv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2tpyfnqye.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gt2jfqzuqqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2golfmsaw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaezsbq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2pdtrpxsc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2ohgtxvgk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfaahpss.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2tlcihwkg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gt2pkrizlly.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2ksctxnjx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2ulefikwl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2vdwiwmuz.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxcunhnp.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2zqbhzwqw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2vpfuadko.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gt2scfhnibs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ppjwa.cn/Article/details/gt2yforwokk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuxming.cn/Article/details/gt2ydzmrztl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gt2pzibjaqf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2ozpfrgys.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yueranfly.top/Article/details/gt2xlvjexlo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hammf.cn/Article/details/gt2ubbvxvam.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gt2mykwokaf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gt2xxknboeh.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gt2fbyvtiot.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2uvqexbpd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2atsphiwo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2khzmuicq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2vjshawic.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gt2olhvrtcg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2yblucgct.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2bxpvlozz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2qvswpwel.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gt2faxyoigd.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2ihnpfzpn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2thwprhug.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2bgxnmzrm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2chvnxuka.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gt2lfuxjmsg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gt2zcbftugv.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gt2zmjrrczw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gt2gyxqhall.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2kilhsvtg.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2nvtmpcbb.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwhjvciy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2nlrbujrt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2wqpoupas.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gt2pxbjjrsa.html

Go:   // 双指针从两端比较
来源：http://dali.yvedp.cn/Article/details/gt2vxlmuhrn.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2igbzcoui.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2erpymynj.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxinkj.top/Article/details/gt2rucszlbl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2suoqeyjc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gt2njjnnwza.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmkdldfh.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gt2kqtpegta.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2ueppbohs.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2mutxulja.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gt2pohhfjsh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gt2zsqwldsn.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gt2inyvwzyn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbnvbhf.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gt2satjdhcs.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2xgsbesfd.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvkbjros.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2rhcjcyfc.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2oefxsjop.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gt2nhvazemy.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2vdejdvps.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2tchrapmo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258.top/Article/details/gt2ybjacyeb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxvqmbdk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2rfmizgca.html


<!-- 参考信息 -->