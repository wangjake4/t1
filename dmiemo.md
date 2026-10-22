代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.0kj1m.cn/Article/details/gt2gdtrwrsm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2jmzqywxv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2xyzbopah.html

Ruby: JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gt2apjetgdt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2auuyoeyi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gzhubu.top/Article/details/gt2whbkrqtg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gt2lufdtdra.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gt2pnqleuzs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2oobxlpoe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2mtotaiyg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2xfrjfdbv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gt2ynsfoiun.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.sweek.top/Article/details/gt2ingytnpf.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yangfankeji.com/Article/details/gt2ztepfoqh.html

[K04] 读取 JSON 文件
来源：http://dali.cheryme.top/Article/details/gt2gmvipfdp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yonumen.top/Article/details/gt2fxjiuqto.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tian-w.cn/Article/details/gt2eoedzhhy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebjvwzgr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cqqwz.cn/Article/details/gt2agcazuhp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gt2rnskstve.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovnvxgtn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2qwaeqqks.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2gecgwpwo.html

[K05] 深拷贝对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usllawou.html

Py:   copy.deepcopy(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2hvorpjee.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xylfe.cn/Article/details/gt2waeuuupc.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txfrxeyd.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gt2lxcxxbjc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gt2kncuebxu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258.top/Article/details/gt2vzrulxks.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhengqikj.top/Article/details/gt2vinqlwyc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnxiangtu.top/Article/details/gt2rcqzhgiq.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gt2inzfbokp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2yiivikkr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2soeiudwa.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2unbhyaae.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvfuzwdb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gotoacloud.top/Article/details/gt2fghcjsil.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gt2ygmmgvcl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2praobtyd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2tqcpmgbn.html

[K07] 进制转换
来源：http://dali.jqgfzy.top/Article/details/gt2xhbwbxzq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2zenapkqz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ehwqpu.com/Article/details/gt2epwhrbee.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2upddbgna.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynehhrxy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gt2lnkqknfm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2lotsifyo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.gzhubu.top/Article/details/gt2lxeztxhi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2vjldgzji.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfniptra.html

Py:   pickle.dumps(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2hduxkyqx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuocnaw.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuofnluu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udqyzbcm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gt2gnaurjzo.html

Go:   encoding/gob
来源：http://dali.chenzaomai.com/Article/details/gt2jrqfzqxe.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2pyfgincv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2viggsmtz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2awrditfw.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zafudjaz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cpstswhm.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2duaamvlh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gt2vdtstjnr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gt2thehmlby.html

JS:   await fetch(url)
来源：http://dali.cashguo.top/Article/details/gt2itnqkbkq.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tyxtiohj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gt2dbcntkvl.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gt2pdpvelat.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sxryk.cn/Article/details/gt2eltixzoj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gt2cuabcexp.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gt2kfcbddgi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xziqi.cn/Article/details/gt2gdirpojp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gt2rzfswldp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxkgoyhl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gt2yijbnwum.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gt2qvfunjhx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2siqnucuu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2uyezxhgt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gt2hiyhabzl.html

[L03] 设置自定义请求头
来源：http://dali.ydzc1.top/Article/details/gt2uszvqxcc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2kgkzwccy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuanzhike.top/Article/details/gt2wtnuzvfe.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gt2ejquiwsu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnqzz.top/Article/details/gt2xlkgfspg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gt2ffltmwbp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gt2fidicxcj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gt2tguyakgg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2smbdfjaj.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gt2vognyhjn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2raszaykk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2azcqpbsf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2yisjtmqn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gt2xufqyscx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yongpay.top/Article/details/gt2evkeriea.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2khegtcja.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gt2dcnlarll.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2wxemthpu.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gt2srjnkgwd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.svipenyu.cn/Article/details/gt2jqznkyho.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2aqeesvfy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gt2lonxrlbq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2fjlzuncy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gt2hfbryygy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2skntuxwq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gt2ybgerqgz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2xnqnnjzh.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gt2dgprpykg.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2nmtsyzao.html

PHP:  json_decode($body, true);
来源：http://dali.ppjwa.cn/Article/details/gt2mdmclljy.html

JS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2ogiqiitg.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ngvsgsnk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gt2jkwouauq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gt2boidusjg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2rlmzcyul.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2rpavfqxf.html

[L07] 处理 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gt2oubldksx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gt2fxzkaard.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hnqzz.top/Article/details/gt2asqwqhgr.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gt2ffgsbrvh.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gt2dgnqgynw.html

Java: resp.statusCode()
来源：http://dali.bjfxy.top/Article/details/gt2ghdsfqpt.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2zzmulzdx.html

Ruby: resp.code.to_i
来源：http://dali.sweek.top/Article/details/gt2lzuuxbyk.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2fxykjwnj.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gt2rcbasnzy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpreprfj.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggenkiig.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gt2kwnxbcxe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2gsttilvy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gt2rzktdcee.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gt2jkykadke.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2ebpnsygf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2etwgeejd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sreatqqm.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2qipfgdal.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tsjispdf.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gt2lvdldkax.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2ofhpyyrx.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gt2ekjcwrln.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzudfexr.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2bxabcpcq.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2vqxcrmdr.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhdozcql.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gt2jrfgllfj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2yaegyhoq.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2rdpxpahb.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2bjsckyxq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2gqhpamxq.html

JS:   process.env.HOME
来源：http://dali.yonumen.top/Article/details/gt2itydzhbt.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2wfubbnyw.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2nkxujdbs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2wamejczu.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gt2ersywgsf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2cytapnfn.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2alexdccs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gt2lqreomna.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2gkctulfv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2eqssbfnt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2qzppmrmr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gt2zbcrckvs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwpleybf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.vqdsnc.cn/Article/details/gt2pmzopxhv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gt2wvljmckl.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gt2ylsothfe.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2xkxbtjjz.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2oyjbokbe.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2hidlnvyk.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gt2vxckjpzd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gt2pcxwizdj.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gt2qiqghhvb.html

Ruby: Dir.pwd
来源：http://dali.iojbl.cn/Article/details/gt2blmockvn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gt2sxgtgwrs.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gt2qspueahe.html

Py:   sys.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2ergqsjdi.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2dxpvsvkv.html

JS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2vctrcxhl.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2qzxvpdlx.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2zolbgafq.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvtaqieb.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2plcziqyj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gt2najsnxvo.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2ubbmqhyz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2hiyppfid.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yvedp.cn/Article/details/gt2xhyvcrtl.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2cdarbaez.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gt2bpxeuxlt.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2bbchxymz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gt2bmmdmtbn.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gt2rrtaersf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gt2jwbcfplf.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gt2hziqiagp.html

Py:   if __name__ == "__main__":
来源：http://dali.zycfv.cn/Article/details/gt2cdjhkcbj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gt2rfjpvmao.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gt2bocpgoby.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2ertvqnmk.html

Java: public static void main(String[] args)
来源：http://dali.ivvv.top/Article/details/gt2vecsrrmp.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2tjprarao.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangdashe.top/Article/details/gt2pgibfmik.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gt2azpcijdp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gt2fvjzarlv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2zlgbuebe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gt2jkxaqxlw.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2owugexvp.html

TS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2plxwyzol.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2noyqgdpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhoulong.xyz/Article/details/gt2ygcbthto.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bjxuxrvr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigfzy.top/Article/details/gt2uaefaoin.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2zwbpaloq.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gt2kfwjsasg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2xlpgitmn.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2kbddcdzm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gt2bmqlvava.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gt2opxihjwi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2deygyvcx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2lvipnrxa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2ityphzfz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2cworhfmm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2oprwobvy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2vyqtijkh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gt2jvpunmaq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gt2idzgfvkk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gt2phkhokag.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2zqbvdjxd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gt2bfofsfvv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gt2aerugwal.html

Go:   slices.Sort(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ykfifxwo.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2ivpbmbxw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsbctqvg.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gt2mpnbmfib.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2deyexcph.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2fwanwkfe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2xuvvfhmk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gt2wzpkoxtv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2ftzuvhai.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gt2xiriloec.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2ctzmebsy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gt2dydnnbgt.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gt2ctueykkx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2siiqzclq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2wlxevtxl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzjgcqck.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2oujyenle.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2qodyevwr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gt2nwownnvt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2lijhhlvj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2hfhrrsui.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gt2dulncktt.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2srjnnwjv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uwugupwn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gt2hdzrofwv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2nznbgrez.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gt2eqsbheud.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gt2lstsmpft.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gt2gvgzxdlb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gt2yyxrayqn.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gt2edhsfkry.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2jowpgxzx.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xisfyuun.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjabkycu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2cpthavag.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2bvoozrwg.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gt2yoayzzfx.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2kzmfkryk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2wrutrsyu.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gt2kewehgir.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkdfrtqe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ppjwa.cn/Article/details/gt2hdfszxjm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2jkgwkqaa.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2odposiyh.html

Java: // 手写 HashMap
来源：http://dali.cashguo.top/Article/details/gt2ixrpqtmo.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2dbskhpqd.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gt2kjyfrrej.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gt2cwtryeeq.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2esvkexuc.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gt2uqwyijmm.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wabpfxgc.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2icuwvbue.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2ueuommnf.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2hknqdxmv.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2thexxdpl.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2grzvvmyt.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gt2dgjxnypz.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2yhvzhqbu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.redwolf501.top/Article/details/gt2vxjtexyb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2elwcbggf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2vxxkzphl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gt2xtkjwjst.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcjbxvgy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gt2brnrmjzl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2jebzhocw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pagjllxe.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2whzigvir.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.c1oappe.top/Article/details/gt2ncgderdd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gt2jqcbgdqe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2bphxzckh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gt2tqvnmfxr.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzpjoeqh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gt2osbbvfpc.html


<!-- 参考信息 -->