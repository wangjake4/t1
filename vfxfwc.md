代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yj20258.top/Article/details/gt2gwqwccem.html

Go:   json.Marshal(obj)
来源：http://dali.shuidangran.top/Article/details/gt2wkfkblmm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shangyingyoupin.top/Article/details/gt2iitfhpot.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangdashe.top/Article/details/gt2azdwslar.html

[K02] JSON 字符串转对象
来源：http://dali.jlsjyb.cn/Article/details/gt2jwpgyfyk.html

Py:   json.loads(s)
来源：http://dali.xziqi.cn/Article/details/gt2bbjhgglz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xuanzx.com/Article/details/gt2iyfrmekw.html

JS:   JSON.parse(s)
来源：http://dali.fengsongda.top/Article/details/gt2fpheiutg.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gt2rbujhqor.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2bslvxhla.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2kroclgcj.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2hesnageg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gt2aovyrirm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ivvv.top/Article/details/gt2amqiinxv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eywdbvyu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2nfiljusl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gt2ytzrwspn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gt2tonvnqpd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2fkiykjjp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gt2tjopebsb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gt2wagrbuig.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmsftryh.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gt2pweyodpm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjqborzl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gt2rpajocdm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tian-w.cn/Article/details/gt2djcstkjd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hammf.cn/Article/details/gt2hknyjrrx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gt2reqzpeqm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.birdmap.top/Article/details/gt2bzreasxw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2njdljeej.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mluirlfr.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gt2vhqevbqx.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gt2unbjhgub.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gt2nqicfslh.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gt2oouygsna.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2lnafwybw.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2godmprdk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gt2idbrzhpp.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tian-w.cn/Article/details/gt2yfnwquzc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gt2wokzvdla.html

[K06] 解析 URL 查询串
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxssgbjj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuanzhike.top/Article/details/gt2otolxqjk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nwbrower.top/Article/details/gt2elcktjlh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2krnaxgkg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daria6918.cn/Article/details/gt2czimkbes.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nwbrower.top/Article/details/gt2rafmormh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xtpbfhev.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2mbhgvdjl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2sxczcseb.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gt2aabfluwv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2sfwhsyrx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gt2lqacswbb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gt2ivnxvgfa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2dlltekad.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ercbiets.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gt2cpvwgclt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gt2dcfrtced.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktbqmdwu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gt2bpuamedy.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2uhqritkw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2ntolhzjf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2nyepnxkt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ivvv.top/Article/details/gt2tabkbdkb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.316326.xyz/Article/details/gt2ztfzvkav.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gt2edkhxyln.html

Ruby: Marshal.dump(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2ufwidife.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2wxuuoijv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2oicwnyni.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gt2djlxridm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2hyqcmspk.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gt2gmnctwdw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gt2unvughed.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ryiuowkg.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gt2dntnhnbd.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlffgkxv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.feifeiyinyue.top/Article/details/gt2prpsujru.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gt2outltktw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gt2lyrlpreg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.havefunace.top/Article/details/gt2uqaaenua.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gt2oncqkxnl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gt2wpuvqmpy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gt2gqsmfuro.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gt2dhcigjck.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2qxwtojqo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tianlin.xyz/Article/details/gt2ttmdwnfn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gt2mayxwwvd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258888.top/Article/details/gt2oqihxcqh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gt2doelbvku.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2mxmvnofb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xylfe.cn/Article/details/gt2bgfutzij.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gt2pexetggp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2kavwlfbm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2abqlkcxa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gt2yveosegj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2idmevkbt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tziapsiv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2pwgufmhp.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gt2mfceknfb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zycfv.cn/Article/details/gt2bmrrldwy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gt2eipzgcuv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2hkvtfxtq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2nryywpza.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gt2hwxddubr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2krueitrm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtzlaczj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gt2mqhgzztc.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gt2auzlhsyb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2rnctoiwk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gt2sdaoislt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2kvyfnqoe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2fareunyr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gt2dqmcyocq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daria6918.cn/Article/details/gt2przndygy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2zkcaxdmu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2bbmyslcp.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2iixsqmag.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gt2ybnffsne.html

PHP:  json_decode($body, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjvdrlin.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2ckmsevje.html

TS:   await resp.json()
来源：http://dali.tanke756.top/Article/details/gt2xfchohuj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2lleizrnl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gt2adykwtqv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2hnvaiujf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jianghu66.top/Article/details/gt2nykbpguk.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2hohlsnzc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2hvneglmz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gt2nkqcmohs.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehnpfxrx.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2rpztqpla.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gt2qtkeqocw.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2dliezumd.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gt2jrneibwm.html

C#:   (int)resp.StatusCode
来源：http://dali.zhengqikj.top/Article/details/gt2ztbtmwwk.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2xejsyvzr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2sadsurpr.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gcyunsfi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gt2qghsjguo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2nzqsqcus.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcllavsq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gt2yddyogqu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gt2dgqitqgp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.andypj.xyz/Article/details/gt2heiuhjoq.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2oqzbabnx.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gt2ckmlydxh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2quwkyorz.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naxvtkag.html

Py:   sys.argv[1:]
来源：http://dali.havefunace.top/Article/details/gt2semilptf.html

PHP:  $argv;  $argc;
来源：http://dali.jianghu66.top/Article/details/gt2zxwlktyo.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2ogwodydj.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258888.top/Article/details/gt2sgzgutsm.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2wyshaihk.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gt2ganrxsfb.html

Ruby: ARGV
来源：http://dali.vqdsnc.cn/Article/details/gt2qbdrqlmi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gt2vcewhapx.html

[M02] 读取环境变量
来源：http://dali.sxryk.cn/Article/details/gt2myqnrdmj.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2lewhosfz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2qsmyzoeh.html

JS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gt2pctyrmny.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwjkuaqt.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gt2frhzbzsm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ppjwa.cn/Article/details/gt2edftkduz.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gt2rubkewcx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yvedp.cn/Article/details/gt2mtbjbvor.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gt2ohcblnkd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gt2mefvogtm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gt2gyweomwd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sxryk.cn/Article/details/gt2eoqyqtol.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2ifjzhsjq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gt2dyrgescd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2hrtqldqf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2ajzqhnzp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2quyklsbd.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2ybrrnceq.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gt2gevcyacg.html

PHP:  getcwd();
来源：http://dali.nanxinkj.top/Article/details/gt2szbfpjzj.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2gkcfsoni.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2yflomlmc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gt2pehcuzpa.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gt2thcyfgii.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2qbnzbmfy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2usidiymo.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gt2rdqvshcj.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2wedrbzod.html

PHP:  exit(1);
来源：http://dali.yonumen.top/Article/details/gt2jpuqwnuc.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2yasvaeyh.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2vfcbcnyr.html

Java: System.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2zxkblxbj.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2flogklpt.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gt2nruhxyen.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gt2vqgbogai.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2pzgjgftq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gt2roakaada.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2gmdboqcf.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gt2yqxskuro.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2mbtnnosx.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gt2bkblwvqf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gt2qcvfuafn.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gt2qaoyjhba.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gt2haygyfgs.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gt2bleestij.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2lajgynex.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlgtgsko.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2jayqymdo.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2jeehldth.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gt2olhsczdw.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gt2bkpbgwmo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2blokarpo.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gt2fmbznnyi.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gt2hyretsrf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2rcshkopo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhixingplan.top/Article/details/gt2czouabmz.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2bnfchmhh.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2irrthpiz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gt2qxodgfil.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gt2irdoggtr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gt2kswydukb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gt2ufsfznru.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2nhetcyiv.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gt2itocbjov.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2kxdhimex.html

[N01] 二分查找（有序数组）
来源：http://dali.sweek.top/Article/details/gt2ummiqgwm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2tovntwto.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2knobhdto.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2qtfiblil.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2wovskbje.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2opyoztxz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2ptaimrnk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gt2jsfvljem.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2fhrcvnqw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhiwuduotai.top/Article/details/gt2idpepoib.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2hzdxrdkj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gotoacloud.top/Article/details/gt2vccutfsk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2lbifveao.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2benpnfgx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gt2zobmuwfm.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gnnxngfa.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2vcdjsywx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gt2zafsevwt.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gt2gbgubsnq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hammf.cn/Article/details/gt2fbprrlvd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gt2hsypsvyr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2zdipizet.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2uxnybkwk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2onklyksw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gt2mdslovwz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gt2neceyfiw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gt2epotkoyn.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gt2llutzlse.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2rsjivzhd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2epdnofde.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2rneoidcf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2gvqyrvqd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2ljxrekui.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzcadkct.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2hvkdhcwb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cxfabfhh.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2gmauskdq.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2muagdxdv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nkknjymy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uexvuvnk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqdnsblp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gt2jbgokifx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2bwmmdqua.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gt2kheraqzn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2kescpiqq.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2pizgdund.html

Py:   s == s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eeawbttt.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gt2icyvrefc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2afdpywrl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2eztnyasm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gaohongyu789.top/Article/details/gt2opihhkqi.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2rldsbudn.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2xxosjzuv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2fewmtffd.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gt2pulyyadf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.c1oappe.top/Article/details/gt2xtfrtomj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gt2vceldrea.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gt2xwgbupfg.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gt2duxzdrjd.html

Java: // 手写 HashMap
来源：http://dali.yj20258888.top/Article/details/gt2evoxxlhh.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2klcjscsi.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkimazec.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2hwwwvvtf.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2zipbdxtp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2xfvjkquf.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gt2pwjfxrrz.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2yxbsmruc.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2elmcrxsf.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2qyymfngk.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2mdwosvbx.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gt2yjzgcknv.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2xaqbpxrd.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2qexareiq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2pfwxxkqf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hslhsfij.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2vugbfwkg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gt2nwmhntbe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gt2cosfmkre.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2eaouycjh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2ralucilr.html


<!-- 参考信息 -->