代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2nklyujdj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pwcbxcoh.html

JS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kogkwqfx.html

TS:   JSON.stringify(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2cvcgxcoh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyxffiqz.html

Go:   json.Marshal(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2pkjefcie.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gt2hjishhrs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btakhedp.html

[K02] JSON 字符串转对象
来源：http://dali.haohaochexian.top/Article/details/gt2hqeytgza.html

Py:   json.loads(s)
来源：http://dali.ydzc1.top/Article/details/gt2nsgnonva.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigufen.top/Article/details/gt2rwsktbis.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gt2oynbqqmp.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2wprmnzzd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2urqdngqt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.bjfxy.top/Article/details/gt2olcweddk.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gt2ejkdrybm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gt2mogyhjjq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhixingplan.top/Article/details/gt2gcfdqlbr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gt2ghctonyj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipmrtmna.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2vhhuvyfs.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gt2bpawcrku.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangdashe.top/Article/details/gt2erxfrdll.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gt2dyymsdig.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2brrdonav.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.birdmap.top/Article/details/gt2ceqqeogy.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gt2qzvwdkrj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gt2nzxsfssy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gt2ugdqvwrz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2lznrdvwx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gt2mheunykk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2ubhfzahb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtxaaakp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gt2ahedyhco.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjpndwbh.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gt2vzlpsnwh.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhybnrsy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gt2jeueozlm.html

JS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nkglsttn.html

TS:   structuredClone(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2efxbsebx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijupyotz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gt2xmohexad.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gaohongyu789.top/Article/details/gt2wrgikxtr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gt2qfioomsw.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gt2wixlknjn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tianlin.xyz/Article/details/gt2scvzhoaw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gt2gutormrc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gt2wrxcbnyo.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sufxvd.cn/Article/details/gt2urhkmsop.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2cutthqzt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nwbrower.top/Article/details/gt2lzssuysn.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2ijytobqv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gt2iuhxjody.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gt2yjrckcgq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2vamlcygl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjckmydt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2xzpkjvlv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2gddmgzey.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2czcqoiyr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2nsoxwvem.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gt2joyhsxex.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2qoedzing.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuanzx.com/Article/details/gt2ydzijcqk.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2shlrvhio.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gt2vlsmphqs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2vbgbdbey.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gt2zrtmhnxs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.andypj.xyz/Article/details/gt2lhdikwax.html

Go:   encoding/gob
来源：http://dali.redwolf501.top/Article/details/gt2ylxghfet.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2sibuuqml.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2cwdrqygo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tzejekjk.html

L. 网络请求
来源：http://dali.smart0.xyz/Article/details/gt2xsmrzcxh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljpjiavd.html

[L01] 发送 GET 请求
来源：http://dali.mhx1999.top/Article/details/gt2oepxucyu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cqqwz.cn/Article/details/gt2agalwgzk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gt2cijnwyye.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2uaylrjpl.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2ncnxajuc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gt2adqezuwt.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gt2fcdorhqq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gt2pouyuejr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.smart0.xyz/Article/details/gt2ukdzjfpw.html

[L02] 发送 POST JSON
来源：http://dali.ivvv.top/Article/details/gt2mscdtnmi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gt2btzqeivd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubfmbrhq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigufen.top/Article/details/gt2lhkhunkw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2wbxxocoq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gt2sphkanpx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gt2jfueembd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2gqskdvqw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.andypj.xyz/Article/details/gt2arjdipbt.html

[L03] 设置自定义请求头
来源：http://dali.jinqigfzy.top/Article/details/gt2zzddbspg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gt2ycjhbdjh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2jcnvmeiy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2gtzasyaf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2xcrlqqny.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2qirzmidr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2eqtxdagf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gt2ochybegy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gt2awzbilgi.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gt2bcymmswa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gt2sghvwvto.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gt2ihkcyitk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2vbztkfbi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gt2mkedkoam.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2yyogwfbm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2tdqpzwvi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.snrcjt.cn/Article/details/gt2wizqtgbi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gt2psccfpdu.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pttbbtrm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xylfe.cn/Article/details/gt2yvynchpd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gaohongyu789.top/Article/details/gt2swqqywqo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2zycgqvik.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2pzarjbyj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2reexcrrr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gt2mmnhjgay.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytwoibjv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2pnmrlybl.html

[L06] 解析响应为 JSON
来源：http://dali.sxryk.cn/Article/details/gt2vfpcagxo.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2tefpoflr.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dubibpgy.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gt2mcmmprqx.html

TS:   await resp.json()
来源：http://dali.xuanzx.com/Article/details/gt2qrfrpgbg.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gt2nmxoufzb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2ltxvvfha.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gt2zyomixdv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ukwtscsp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yueranfly.top/Article/details/gt2sblctopn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gt2kwbdpzjc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cdnleiting.top/Article/details/gt2bzplilbx.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2vnueeykt.html

TS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2aneyadpc.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gt2wrhkwajs.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gt2nayyijqq.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gt2vzzqvcxu.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gt2acbxqujb.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gt2xlzcwqjy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gt2zqumxvti.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gt2btcgerjo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gt2cmtkhxme.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2tshdujqr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gt2zuahdplm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osryvrjm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2jufzdhco.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gt2tyrmbpuw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2igjctyro.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gt2dyfcfyqz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2fvjodrlc.html

[M01] 读取命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gt2yiumsajm.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2ujhrlpea.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2lfikwiar.html

JS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fngjonjv.html

TS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2nbnstzyf.html

Java: args 数组（main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2abkflsvu.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gt2waljdcrf.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gt2gpddpaor.html

C#:   args 数组（Main 方法参数）
来源：http://dali.mhx1999.top/Article/details/gt2yjlnfzon.html

[M02] 读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gt2hxydfhjy.html

Py:   os.environ.get("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2chsakhxc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2zxxfzzsf.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gt2kykmliag.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqglylan.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2liebxkxc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2ogwhsnkl.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gt2ugxroqhh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2xirvfcdg.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gt2wukwhjla.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gt2vjxctbbf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjigjoif.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.meibo888.top/Article/details/gt2gxcgnnes.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2shriobdi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fzhhl.top/Article/details/gt2mzxoqusz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gt2kjngeaye.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gt2cawzhzlq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2rxlwtekp.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gt2fkajozlb.html

Py:   os.getcwd()
来源：http://dali.sweek.top/Article/details/gt2zfstkekn.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2hdlgawdb.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vqcizvab.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gt2ewozwban.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gt2kxvxjedt.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gt2zwrplqhp.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gt2hlzjjdps.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gt2xiqdldmp.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gt2nuyjrpyf.html

Py:   sys.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2xfdjqogf.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gt2ugrukswz.html

JS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uoufwpiw.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2dybelaem.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ngtdsgts.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2tcbtlxdb.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2zhhelbgn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gt2ocyyatyc.html

[M06] 向标准错误输出
来源：http://dali.zhengqikj.top/Article/details/gt2akmcuhmp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gt2lgpbjzre.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gt2hovbqdce.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2xjcwwwkn.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2blymoaxb.html

Java: System.err.println("err")
来源：http://dali.aibaodan.cn/Article/details/gt2ibrfkifa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gt2crbtnibi.html

Ruby: warn "err"
来源：http://dali.zhoulong.xyz/Article/details/gt2cxldcwqn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gt2bidzifkr.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gt2nxhbdldh.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gt2lbclhnaj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gt2tghsvves.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gt2nyobshfb.html

TS:   require.main === module
来源：http://dali.xuanzx.com/Article/details/gt2ztlyjpxg.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gt2xmoznjuo.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2xygjtoty.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gt2jpzswkrx.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhpyrtbz.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gt2nknrwvzm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tian-w.cn/Article/details/gt2qyrkhyhz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2qaypehic.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gt2eoajyzle.html

TS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2xghimuaf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gt2ntaskyoa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gt2bgerdpam.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxinkj.top/Article/details/gt2pfpaypot.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gt2kqvlouri.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2jmgqniwj.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2qwmyuaie.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2tffefnlc.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gt2shttykno.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qghqpfnl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2zssqxcuz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwxwiwxd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2supbmmgn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2kvqdnkjc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2yhvrdoyv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnxiangtu.top/Article/details/gt2zhljvoaw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2nzjjcpfr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gt2ahfyoobx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2ilzhlmui.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gt2ixzfounr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjffevnq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gt2lfcwduny.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usfjtebw.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2vhilpziq.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2rpnwxtlc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pgwnlver.html

[N03] 快速排序（分治示例）
来源：http://dali.c1oappe.top/Article/details/gt2zoxtoxly.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gt2rtjfbfgv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gt2goxeecvs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2byrqesil.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2ecxqliin.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nwbrower.top/Article/details/gt2xkjvdfgp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqppegkz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2aztymfwi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gt2zifnxgam.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gt2bsusnnnl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gt2thikzjkr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gt2mbdzxtgg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2gybswboi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2dkwuojff.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2mnmvwimr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gt2szkgorbl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2niyxbrqe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzylvzdw.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gt2npohqdks.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2ymmaixlp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2siqbskoi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gt2yxtmgnrl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgdsvkxa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfjyuede.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.9152youxi.cn/Article/details/gt2rteqkbkr.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2jcuezjmt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gt2tnfikwcs.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvtjavtu.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gt2wrjxtubh.html

PHP:  $s === strrev($s);
来源：http://dali.cashguo.top/Article/details/gt2ebbossmt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ggfjevmx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2zuroaacz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gt2bzxtkpll.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2gxemfmcz.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2bwadxuhs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2ustbfypo.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gt2rlsbpbtx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gt2hmkcjdit.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2xxycauau.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gt2glxxshmk.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbnbtvyj.html

Java: // 手写 HashMap
来源：http://dali.redwolf501.top/Article/details/gt2rgfgwmoq.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwimsxei.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gt2kkcokmom.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gt2gafzcxfn.html

[N08] 生成全排列
来源：http://dali.ehwqpu.com/Article/details/gt2axpuivxm.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2jkzmjihe.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gt2opohxxbe.html

JS:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2ssdacukc.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2mpxhalti.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2qqzpanou.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2hdgfogdx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gt2tsqvtmiw.html

C#:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2eirmkdmd.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2bsuwadby.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2sontagyr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2hooskvdr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2psomsahg.html


<!-- 参考信息 -->