代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gt2ublgewck.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mahwoowp.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gt2rinfefkx.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2gwtcotdu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oypzdgzq.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2ajjxhysb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2gebzkvlc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gt2ijxppbmv.html

[K02] JSON 字符串转对象
来源：http://dali.jiagoushi.top/Article/details/gt2wicqsxgy.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2vcvzkiox.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewlicwpn.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2tvdenwop.html

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gt2vstljmvk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gt2lxzzbivy.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhijiandao.cn/Article/details/gt2woxffayi.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gt2pvvhwvja.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2jhhiqmuf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gt2krictunm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj202588.top/Article/details/gt2lnmvswyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gt2nukbitqa.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2rvezulgp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2phlcjdtt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2krsozssz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gt2pluxgzkw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2wtsdctaq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gt2uhqrpcsr.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2yelnfcnp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gotoacloud.top/Article/details/gt2lijqrrxc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hammf.cn/Article/details/gt2qcemxhng.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdkahboi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2dncypjnz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gt2jfmadkli.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2hzesqpjm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gt2lhpadlru.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gt2trcgfqfn.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gt2grggrtga.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2lncylgfq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gt2piljrjri.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2htjsesku.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2ebiklmma.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gt2asmzkypm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gt2ikukjyha.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuanzx.com/Article/details/gt2uiseivoc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.meibo888.top/Article/details/gt2ilrgytmk.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gt2bjkseqkl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwjepzhn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.haohaochexian.top/Article/details/gt2andxdqqo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2yumijmhe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gt2nogiepol.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gt2gddvpixl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2xmiqbsdp.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2wvpyzann.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2wkbqyfcy.html

[K07] 进制转换
来源：http://dali.birdmap.top/Article/details/gt2vyoxcngq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.meibo888.top/Article/details/gt2ujgnnmcv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinqigfzy.top/Article/details/gt2zgttwkip.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2bwujwzxd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gt2zdqvudmn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2foaswhpa.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gt2mezgxqys.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2sosyaeec.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2iaiqofff.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gt2aaabegie.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2vletnnqy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gogol.net.cn/Article/details/gt2elqvvdzw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xziqi.cn/Article/details/gt2ccbvwqep.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2vzcbuejs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cheryme.top/Article/details/gt2vrwvzskz.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gt2qutqynnt.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2xnvqykmm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2tmggfjwe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2lsrwfsnc.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gt2ouzfnety.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2hjbooxmm.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gt2jvequdbc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvfkocsm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpbevexp.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzlgevic.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gt2nzzjeqpm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.mhx1999.top/Article/details/gt2euywvnds.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gt2udclymoa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gt2ufdrwqxb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2axguangu.html

[L02] 发送 POST JSON
来源：http://dali.cheryme.top/Article/details/gt2rmnbpfec.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gt2cbfmqmwt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txdlfeld.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgxiqfrw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2ogkhxlwv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gt2nceusihz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gt2gbgdmgto.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gt2ghgltnen.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrklqurx.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gt2otcazxpz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gt2asrufqeb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gt2audtrucd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2ankhscmp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gt2xwngizkq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ciqvxcry.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pliwsufs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gt2hhxlqtdj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gt2spmkwqmv.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gt2dfbglfhx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gt2yrmfvads.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gt2qrmvlteb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gt2cjaqkepd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2ltkdbahy.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gt2bhkdrpwc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gt2xexulwfx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gt2rteebxku.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gt2hsgkvdhr.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gt2eibsicnj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2ssafmnev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gt2ploajvqy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2qnengmsp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2wtcrkvuj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxuanxn.top/Article/details/gt2gfjtnsge.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gt2uswekxce.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gt2zhvokpwg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2bdjmrkvq.html

[L06] 解析响应为 JSON
来源：http://dali.wangdashe.top/Article/details/gt2cgkmkocj.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2quczkhrg.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gt2tvbzymhr.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2usvmmsju.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2ahdetmtr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gt2dsenfjaa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jiagoushi.top/Article/details/gt2wntvqlhy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gt2oxsgwsgy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gt2tnevxhfu.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2bkrzvcnv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.havefunace.top/Article/details/gt2zaabzllu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ybcxt.top/Article/details/gt2iwtcsedd.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqlzjbvu.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gt2mtfmaqtf.html

Java: resp.statusCode()
来源：http://dali.hysaishi.cn/Article/details/gt2vtfzuezy.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2hsohgmrl.html

Ruby: resp.code.to_i
来源：http://dali.tian-w.cn/Article/details/gt2fvjfnslh.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kpvsbcdb.html

[L08] 并发请求多个地址
来源：http://dali.sweek.top/Article/details/gt2eogweqvv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gt2hugnvxcw.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gt2sxwsgnpe.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2vaetamuo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2fatrssiu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2woonnekn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gt2emaobjwj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gt2ksaglmpq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lrbawreg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2sqvtafgy.html

M. 命令行 / 进程 / 环境
来源：http://dali.yongpay.top/Article/details/gt2myofvqak.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ihsvcrly.html

[M01] 读取命令行参数
来源：http://dali.ivvv.top/Article/details/gt2cbvsldbb.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2apdlvyzp.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gt2zrcugtpj.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2ozfgkhml.html

TS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2wywovznt.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2vkmhlmoj.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gt2rmxxzptz.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gt2kaqyduqe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2fcygczsb.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2vpzvjzdu.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2lyujscci.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gt2hfnpgzlu.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2wbacdmhk.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2xdiblsvk.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2mxrwrcgz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2yhieidmu.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2vpiapkaj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsyaoiup.html

[M03] 执行外部命令
来源：http://dali.sxryk.cn/Article/details/gt2wsvicbjy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pycfn.com/Article/details/gt2vylaatme.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zdqjudy.top/Article/details/gt2ttzoshlm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxinkj.top/Article/details/gt2dvrhgwqx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2vbitrcea.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xylfe.cn/Article/details/gt2jqbpyrjh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gt2sznpvzhw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwwstruo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2dmanjkxz.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dxhlrjkh.html

Py:   os.getcwd()
来源：http://dali.yj202588.top/Article/details/gt2fiajkffw.html

PHP:  getcwd();
来源：http://dali.hysaishi.cn/Article/details/gt2utarjgiv.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2hafawgtf.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2fwccgzbd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2kqxauggz.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gt2gnwgbgex.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2ilgxypmn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gt2nhnnkyci.html

[M05] 设置退出码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sligxeij.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2jkxnkpiu.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gt2zcocjuau.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2fngzwpqq.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2uaqisyex.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2encxigxl.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2vtzklcbh.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gt2krdkcrug.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gt2iqembaua.html

[M06] 向标准错误输出
来源：http://dali.sweek.top/Article/details/gt2qdvvqnts.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2iesmklcv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.quarkkingdee.top/Article/details/gt2vjiruvxl.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2ikhgzikx.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2dbqgfsoj.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gt2moyllrft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.c1oappe.top/Article/details/gt2igcwdwyc.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gt2bgkmauxm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gt2fiyhzrsa.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djvfrvbr.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gt2oljkrgtc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gt2kwnmuisu.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2xktdawvn.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2unpzopfx.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2rgjrsnrl.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gt2sthlhbyr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2dasjhwbc.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2jblnkpwu.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gt2wuosqpiq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2tussnyke.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2okgsvdgk.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2xpwypsdt.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2rgoqnrng.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iojvovpv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gt2jxjrkzoo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gt2celwdnjz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gt2acttlkiv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2rvxskoyo.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2tvvifvev.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2qmtzjgji.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gt2khjgdhcy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2lspajvfk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmtpkuxr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2vjzcombj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vkmyrbaq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2fmdqqmsk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgkevglk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gt2zvgvbddi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2ocvzkxfp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2pfdzaary.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gt2jintpijy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gt2wylqycyr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2lnzekbcr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2zmviabyc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2hxyfdvzn.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gt2bduzmwug.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2stikjjgs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.9152youxi.cn/Article/details/gt2gkmyopdg.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2cywhtntu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gt2zwpdpqkr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zdqjudy.top/Article/details/gt2shyrpccu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gt2zmwcptnw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2enfosvvs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eitoipeu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2fnzbnjew.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gt2utbobkhr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gt2qyaianit.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gt2ctgjmrqc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2ekturfhc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yvedp.cn/Article/details/gt2jifhhtvs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2hbnkjkst.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gt2hvwbdfud.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gt2mirmbdvl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gt2bzmyqkst.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gt2awxcqxss.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2yhpjsagj.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gt2xtxznjzz.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2hibmwbnt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2onyukplz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tylrozqp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2pvzisqrc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2sflnussf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gt2nbphssvr.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gt2ggsjrvgo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gt2fadvxgik.html

[N06] 判断回文字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2naiuudpb.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2nbxolhon.html

PHP:  $s === strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2pdqgiclr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2eudwwfcc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2bhbbzgzh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrahigsm.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gt2rajjeapr.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2usxrpozt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gt2ycoydeba.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gt2rzqoogbg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2gvnqnjhj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gt2snkpnqus.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhixingplan.top/Article/details/gt2zoanydgd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gt2xlzgrkcr.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gt2hvdyvhga.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayogeqlz.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gt2zosgduev.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gt2gdxffeju.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gt2tuzmnmlb.html

Py:   itertools.permutations(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2qczoxiot.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gt2aiteyugp.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2erhdhsns.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2qoolvmgp.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2kcojqljs.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2wgcxkxgc.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2dkkrsdai.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsnudor.html

[N09] 栈与队列
来源：http://dali.fengsongda.top/Article/details/gt2xxsddoja.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gt2dynijucy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2tfsealgq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gt2egycfsxt.html


<!-- 参考信息 -->