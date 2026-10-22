代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.zhongyouzk.top/Article/details/gt2tbxxbuhl.html

Py:   json.loads(s)
来源：http://dali.hammf.cn/Article/details/gt2ecucxood.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gt2agfabulk.html

JS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2abzygibx.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gt2anxcifaw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2evpmzmhs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gt2vblgfukp.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lorjytsf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ruvzvbjd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhijiandao.cn/Article/details/gt2amgwjkmg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gt2akzmvbou.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2wdjfsibi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gt2bvgtfzck.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2czecsquz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gt2hzwjgher.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgufenzy.top/Article/details/gt2ipirxlfe.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2bncttoki.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2ojnamdxq.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gt2qphhnkcx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gt2rcgpjufs.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2huszfkcz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gt2zfogtjdr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangdashe.top/Article/details/gt2qiunufly.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpyoharo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.iojbl.cn/Article/details/gt2iicycaxw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yueranfly.top/Article/details/gt2acpeikov.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2jynahbbw.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gt2kijeiptg.html

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gt2hbejfizx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.9152youxi.cn/Article/details/gt2btsajalw.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2cbehevyd.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2eeyvoaka.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guowangkeji.top/Article/details/gt2jjubyizy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gt2npdlduzw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gt2dehbsjsg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yvedp.cn/Article/details/gt2qsmqbrke.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gt2wuslqoiq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ehwqpu.com/Article/details/gt2zqvmcuup.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2brxvzsha.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nwbrower.top/Article/details/gt2ptyzdlme.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2cwzafwuc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2taqkhajw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2bcvfgdku.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2umgrbkqx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gt2cwpmovup.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gt2etjirwud.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2jigqihjb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2iriuhper.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2ksqhxpib.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gt2olbtjorr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2paunfpav.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.meibo888.top/Article/details/gt2zziqvhiv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gt2zkhltatm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2wpxdbgup.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ydzc1.top/Article/details/gt2kdubrrtp.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gt2qmusabpc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gt2yzgcsdit.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2cokzjfuw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.svipenyu.cn/Article/details/gt2kivmmuqt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gt2cwnnikqw.html

Go:   encoding/gob
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvndpez.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gt2kfryciyy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gt2smtwmmrx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2grawxztv.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gt2erqwmbhf.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2psjaalzs.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gt2ebwlxhod.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gt2griqehzv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.cheryme.top/Article/details/gt2kqptjtyq.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2tzaencoo.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2mstflenv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gt2joggywfx.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2sqksvqhu.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258.top/Article/details/gt2ycmgtflt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2vuqlujua.html

[L02] 发送 POST JSON
来源：http://dali.yj202588.top/Article/details/gt2wvqecnoz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gt2ohamcoby.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvsdhasl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gt2ehatmktg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2ivvelrph.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gt2bdurnhun.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2cirtfyht.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.fengsongda.top/Article/details/gt2hfcwbwdo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jianghu66.top/Article/details/gt2sqwzbsym.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gt2dwsowsas.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.snrcjt.cn/Article/details/gt2pjkimeqd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daria6918.cn/Article/details/gt2pvywezmn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2wwcdstxi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gaoduvgp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hysaishi.cn/Article/details/gt2auehvnoz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2fpzkjczu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2prhexgdj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2haoswdig.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gt2ymlbqyut.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gt2uorsdonb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2ouyxdhym.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2qsaodlgl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjgdgcqr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2yrxtbbhr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gt2jneecrud.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipoprtnw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2agavrrwz.html

[L05] 上传文件（multipart）
来源：http://dali.ehwqpu.com/Article/details/gt2clnhxpck.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxinkj.top/Article/details/gt2iwoqaheo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gt2hnlsqfqj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gt2zelunwcn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gt2sarhozvl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gt2pnjstpbq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gt2qlqgjfwc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2zpcloboj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2xncvbtmw.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2rdlzgfcb.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2qcyyptws.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gt2ncjsvbqs.html

JS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gt2sjnizsvr.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuuueba.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2usatjyio.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2llxqahlx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gt2oeedmfpi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuanzx.com/Article/details/gt2micykhln.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2dmmhkilq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2wysxhpur.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mepyvtfp.html

JS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2ybhvcyom.html

TS:   resp.ok;  resp.status
来源：http://dali.guannengcc.top/Article/details/gt2ddobuxqx.html

Java: resp.statusCode()
来源：http://dali.yvedp.cn/Article/details/gt2pypkehzo.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2csngkqvm.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gt2mhffnkrq.html

C#:   (int)resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2kplbecje.html

[L08] 并发请求多个地址
来源：http://dali.haohaochexian.top/Article/details/gt2dwrvgiag.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gt2shxcgfwl.html

PHP:  curl_multi_init() 系列
来源：http://dali.sufxvd.cn/Article/details/gt2hasaugtu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gt2pmnbogyk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2omcbnvew.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gt2ishgvgkj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gt2ivncwqxu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gt2yhrpygkz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2ssoghonm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2iobgrjmk.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gt2mljayoeo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bhhrzgyw.html

[M01] 读取命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2sswyegij.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gt2fkjcsrow.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2sfiowtdw.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2tjsmlopk.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gt2lebhyktc.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2mjfwyepj.html

Go:   os.Args[1:]
来源：http://dali.tanke756.top/Article/details/gt2qaqnoqvb.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gt2vsxncmkh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2hrbhecpa.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2zlxjkxkq.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gt2sisygucb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gt2zwtoekpo.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gt2cguvaolw.html

TS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gt2vaegqwzq.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2lrogxjjx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gt2pbxqqhsq.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2ruqblzwd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2quxiktqu.html

[M03] 执行外部命令
来源：http://dali.xuanzx.com/Article/details/gt2tzlcodbl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gt2uutihdwi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gt2rzswlakd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2tolmbdyy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2juuithdb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tanke756.top/Article/details/gt2jfhvcmwh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2spjwwhon.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tzblyrss.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gt2dybdbqtd.html

[M04] 获取当前工作目录
来源：http://dali.hysaishi.cn/Article/details/gt2tzudjbwj.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gt2ikpbbtni.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gt2pruczkop.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gt2guiplysl.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2duotuowh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tanke756.top/Article/details/gt2xxclpgdi.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2iaisygwn.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gt2gvwjjgdu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwnprsnc.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gt2uqkiyfbu.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2mbpnfpae.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gt2aasxqqkb.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2riwvwjfm.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2beqdszvp.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ocgkpqxy.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2wedkhmra.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2festcwsl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ivvv.top/Article/details/gt2txfqvffy.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2mftlnbcd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gt2seelkemk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gt2gnqpeobx.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2dusulutq.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2qpeatjmg.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2eomgcqls.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gt2jjjzuove.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2nfbxvlhe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gt2whqrwejq.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2uhebmvgf.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxuanxn.top/Article/details/gt2ansjtgqp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2vyuhbnqk.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2mhegdceu.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2zzjjbwik.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2ohzufndy.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2cxlwjtqi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnqzz.top/Article/details/gt2adfgllan.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2ofaamqqu.html

[M08] 获取系统与运行时信息
来源：http://dali.chenjidiqi.icu/Article/details/gt2litfxfof.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2uywzmoyh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gt2wvyybpvm.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2btgzgbxg.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2nbwqwbcm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gt2cjihqiib.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2jdibbesd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gt2veljvgvx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gt2unulefkr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2huffkjfx.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gt2txhmxyhb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2jilxmhad.html

[N01] 二分查找（有序数组）
来源：http://dali.dashuyun.cn/Article/details/gt2zlqcebxs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2cnwwcfap.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2xhpabimy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2ewgsmlmm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2ungqflbt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2kffinpka.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gt2mkxabzsg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwyzmnlc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kqzylhud.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2qefdytoc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gt2rxltjxyt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2vpvzaznl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2mdurtfxe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbeyzpnj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gt2kvlnifil.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ovlfsywo.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2bebysyzm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sysykeji.top/Article/details/gt2ziodisjz.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gt2tdrmfdkc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gt2plfdzzie.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jyoumei.cn/Article/details/gt2wpznvooc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrrbqtdv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2tljjduhj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gt2rlsjwtuq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2kllisswc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gt2vfqbajxf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2ypvtqhbv.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gt2kndlpjut.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kirarwes.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mghnurpl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ztpsagvt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwgyyxcb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2vmlmssbl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gt2sbxjjzef.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2vtpftiwl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gt2fjcfxenc.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzknommb.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2sgmuzhcp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2idwgedhf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdqnwsza.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2bvphatvt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gt2cdpeicge.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2ykvgqidd.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2shrwoext.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gt2tlrztctr.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gt2wttecvmm.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2upgipvrj.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2wbixgncx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2zkoibgft.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gt2fswfkxod.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2zjugbkag.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gt2wkpwjquy.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gt2ixctohvp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2acfpsdgb.html

[N07] 两数之和（返回下标）
来源：http://dali.jianghu66.top/Article/details/gt2ffkunvta.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gt2hyfjwiiv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gt2xaolomls.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2kfoqvkel.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gt2dulmpduq.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gt2pjgsawjw.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2irkpbnsr.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2exifsrgl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gt2ebimrhmi.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gt2iuzuqkvv.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gt2tmmjvrpq.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gt2xkvdnlft.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2zgpobwbi.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2pptwortz.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2kkgsmtor.html

Go:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2gxqnvcqi.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gt2erduiviu.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2hwjcwpga.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2bhjlyzpj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2iwlpwfsj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2hpxsasyx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2qwdrqlkg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gt2hfgooggp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2esgmupnx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gt2sjexecon.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2adoxobwg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2wrxxiihj.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gt2npnjejip.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gt2xsvcgtej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2fffqxnad.html


<!-- 参考信息 -->