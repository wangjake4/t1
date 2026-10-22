代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtbyltarve.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtprqtibes.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtfqebbtgv.html

TS:   JSON.stringify(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtkbuurxfn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gtmsquleik.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtgsilulal.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.guowangkeji.top/Article/details/gtkbuweydq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkajappnq.html

[K02] JSON 字符串转对象
来源：http://dali.xuanzx.com/Article/details/gthajzulcq.html

Py:   json.loads(s)
来源：http://dali.aibaodan.cn/Article/details/gtggmbbhil.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtkgllqkwh.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtigtdwyrs.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtnqlekqdy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.smart0.xyz/Article/details/gtbvzxozhl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtspazyksv.html

Ruby: JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtjkyfoggp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gtknhkkovy.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.havefunace.top/Article/details/gtjpfifesx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtcnujlnwt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtphltypdc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtwxsonijt.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtczkzikch.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuxming.cn/Article/details/gtfcbwliho.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtfhmyajse.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.bjfxy.top/Article/details/gtvrpztoxq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtiiqdzwia.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtharxqyqt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnfhpyer.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtdsquzgks.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtqcnafnbf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gtvusrhvhf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhdsxzez.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hfpthk.cn/Article/details/gtkeeayjmd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtfdkmbnfc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gttragpqzy.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtgzkqwdsh.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnctrdptd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtrxbmxpoc.html

JS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtajhambhs.html

TS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtuggubrwc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtfhomkwgd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ivvv.top/Article/details/gtdrqqfpca.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jiagoushi.top/Article/details/gtrnbejevv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xinyue.icu/Article/details/gtrbgqfxxt.html

[K06] 解析 URL 查询串
来源：http://dali.gotoacloud.top/Article/details/gtktenapwq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxpahfrw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gttkrvrxji.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuanzhike.top/Article/details/gthkmyklqy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtbjykwjst.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gtdykzpzeg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gtdaftypvr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtuckzkgxe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtxdmmyzzn.html

[K07] 进制转换
来源：http://dali.vqdsnc.cn/Article/details/gttwucsxpo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gthnyhkabx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.iojbl.cn/Article/details/gtsovtbpho.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtfqbbnmph.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtwkoxkwjm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtbiveqvzs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jiagoushi.top/Article/details/gttkmjjuua.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gthjorttxl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtxqlwruay.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tanke756.top/Article/details/gtunyrimma.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtvhehheeu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yueranfly.top/Article/details/gtfjmuswvb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtyuldzjxo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtbqbokdxt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gtjtxziyuv.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtpqwimfpo.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenlongwang.top/Article/details/gtzefstkbk.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gtykyfvwds.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrwxvuljg.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtxkiadguf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gttauclhdk.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gtttehlzhr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gtywtlofot.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtlvblmxcw.html

JS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofmogrkx.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcelikfl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtuqucwubv.html

Go:   resp, err := http.Get(url)
来源：http://dali.shzxlz.cn/Article/details/gtigfgxfnc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gtczsooqpa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gtrlkzdkeh.html

[L02] 发送 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtswidwpzm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtofnjzdac.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gtbwdpnjef.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtwdzjnwpz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtjekwudqi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtrfnodege.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gtfgxfsqqv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtbvtsfned.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.pycfn.com/Article/details/gtieeicfng.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtdhjieljg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqixyblms.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdkdlcir.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtphrxkrkh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gterzliieb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gtokueensn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gttglzqskj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtmyoxffpl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtykanllrc.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqlnqcbq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtsequldxo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmxxqori.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtcwwtipah.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxinkj.top/Article/details/gtxgyzjupv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258888.top/Article/details/gticwbuhkk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuanzhike.top/Article/details/gtgawjqknx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hfpthk.cn/Article/details/gtvtzwmgjo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtcamhfhyz.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gtahenbwge.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtzonblzmr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlqybxeo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.fzhhl.top/Article/details/gtlznteiff.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtvlsltwaa.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtcgpfimwe.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtmleqiior.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shzxlz.cn/Article/details/gtsssrkhse.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtztpepzzf.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gtjzxwueqw.html

Py:   resp.json()
来源：http://dali.jianghu66.top/Article/details/gtcmpuhndw.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuzgdsso.html

JS:   await resp.json()
来源：http://dali.hywenlv.cn/Article/details/gttwuleebu.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtatqdrgqm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtyvhphyan.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nwbrower.top/Article/details/gtzajhzllf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gtvmtgecgm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtuxpawwvz.html

[L07] 处理 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtktdehpfo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuanzx.com/Article/details/gtkkqatkzr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gtwkhnkpva.html

JS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtdqqjxirv.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtrnxwmxyx.html

Java: resp.statusCode()
来源：http://dali.shuidangran.top/Article/details/gtcuxgtsgi.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtqxldrkjv.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtotjecfef.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtcbeuffdx.html

[L08] 并发请求多个地址
来源：http://dali.shangyingyoupin.top/Article/details/gtzakaglyd.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtpkwubipn.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtegnugaka.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtezsqcivj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gotoacloud.top/Article/details/gtppcrxwpm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.guowangkeji.top/Article/details/gtvnnosiso.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtmogktogs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtojxtpksb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gtguxrnrza.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtksbdkovx.html

M. 命令行 / 进程 / 环境
来源：http://dali.dashuyun.cn/Article/details/gtrtomydcj.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkjlrlzrm.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gtoqcihegy.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyatqhcxy.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtjinfuqcq.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtgpcjnnht.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gthdgrhtmt.html

Java: args 数组（main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoooxzlnt.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gthlkalzbj.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtbfkiyuej.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqnmhlng.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtvywavvhq.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtshobhogs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtsxusxruv.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtxublfovi.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtmzrteeqw.html

Java: System.getenv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtkzcofneo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.iojbl.cn/Article/details/gteleoxtfl.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtozpulstr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtrmocxavi.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gtdjshecbr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gtozogukzk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtesdzrafp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gtwzdcqdgb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtdwmmklmt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtehwsmdjk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nwbrower.top/Article/details/gtoyixhpwx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtbkifubgm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gtgtmctade.html

[M04] 获取当前工作目录
来源：http://dali.aizwys.cn/Article/details/gtihjztxva.html

Py:   os.getcwd()
来源：http://dali.yonumen.top/Article/details/gtcrjprgap.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtplhyzqfy.html

JS:   process.cwd()
来源：http://dali.nanxuanxn.top/Article/details/gtiniohfab.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtfdeicwze.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gtyglcmcwj.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtbygskbpl.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtoupwjklv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtqqxfgett.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gtghzzpaec.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtvnthbeyw.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtnssshefr.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtksamrdzu.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gttrntlztb.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtvfmljjyt.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtuttllddb.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gthhwxlbnk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gthaaggide.html

[M06] 向标准错误输出
来源：http://dali.chenjidiqi.icu/Article/details/gtwehfcmdx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtylxlueki.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkwhohhl.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtmcjkndcv.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsquinlic.html

Java: System.err.println("err")
来源：http://dali.shuidangran.top/Article/details/gtqwvnpvul.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtdhqsfbnu.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gtrmvigqor.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtigjuoepk.html

[M07] 判断是否为主入口
来源：http://dali.smart0.xyz/Article/details/gtoxukfqua.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtelkupsug.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gtwyniddkb.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtdjjxgohd.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtuckunsgh.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtrfhishec.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtafeczlrr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtsxqhliij.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gttbaabomb.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gttrlcsbzf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtchesufnr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtbsxswxxl.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtujxtsnoy.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtdorxazoc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtoxjnnntm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtuudmumbq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtzikgnibw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtxgcrezmq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtgppfuios.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gtpimlvipn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtalubkvxl.html

[N01] 二分查找（有序数组）
来源：http://dali.vqdsnc.cn/Article/details/gtbjdlkrkq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtjfkfkinc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtbwctttej.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneodjmyl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtmgqmsguh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258.top/Article/details/gtrpwcwygj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtytymemxg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gteyndcrjw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtybpzjtip.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtqlgvrmmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gtdldhurdl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shzxlz.cn/Article/details/gtimgyvxud.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsizcaxr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtlcljhtjh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtyuivwath.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtccezdapm.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtcsikcmsi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gtzpvcyeie.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gtqgrowbwe.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtfcsiollz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtjbsqqfcv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtnaunpobk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gtfzwwugwb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtaucesnur.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtvovgshwu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtbnrqzukz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtlkqfmjgc.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gttdsobyzq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtwgjzfgwp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtkkfknxpq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtevrsfbus.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtbbcpromt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtccuacpnu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhvhqeye.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtbzoxjyhm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtznshbrdq.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gtqjsswvuv.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gttsxqfcnj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtamhuqbgu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gttayggkzr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtozsfpwmw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.mhx1999.top/Article/details/gtzkbhpcjo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtepwbball.html

Ruby: a.gcd(b)
来源：http://dali.mhx1999.top/Article/details/gtojjjcvgb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtrwafdfht.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrarjrzbi.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtexichtoy.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gthdbaptvs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtyxyaqjnm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtijkmumor.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtkafpazej.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gttjcsjznb.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtrkgtlurh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gttonsoftb.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtrzvswdnr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtijifnffa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtxicazkdm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtyasbirvv.html

TS:   // 手写 Map<string, number>
来源：http://dali.shuidangran.top/Article/details/gtjzxrykvh.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gttxjwmcgz.html

Go:   // 手写 map[int]int
来源：http://dali.guannengcc.top/Article/details/gtkbyloxje.html

Ruby: // 手写 Hash
来源：http://dali.yuanzhike.top/Article/details/gtuglshcjv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtadlbmmjo.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtneszemlc.html

Py:   itertools.permutations(arr)
来源：http://dali.aizwys.cn/Article/details/gtudnhlvlk.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtwpulvbkd.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtzipsbreg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtxyuppcji.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtlyepesbb.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtaldebqjs.html

Ruby: arr.permutation.to_a
来源：http://dali.guannengcc.top/Article/details/gtlrczqzru.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtogsadndv.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtlfhnipwz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtosxsgojb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtrhvjrlky.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtnaebsozg.html


<!-- 参考信息 -->