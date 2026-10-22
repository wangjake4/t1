代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ffytccxh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zycfv.cn/Article/details/gt2xlljgwbw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2luqrrfvy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2xejyjfdx.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2fanuhxev.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbauredd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szclhwzv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gt2wupjkmat.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpjpkyim.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gt2dcbrjjrn.html

[K04] 读取 JSON 文件
来源：http://dali.haohaochexian.top/Article/details/gt2ejykyzxk.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2llwlcqmz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2lsndkmff.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.svipenyu.cn/Article/details/gt2sobwmuzz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guannengcc.top/Article/details/gt2nucauzdq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gt2rkaqyfqc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gt2jcbawzrh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daxiang520.top/Article/details/gt2tiegytuf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ivvv.top/Article/details/gt2gstcldid.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gt2rhzggusn.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2agqesaxr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigufen.top/Article/details/gt2kajckxpq.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2vkptisun.html

TS:   structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2juamgnnp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gt2gjivxmqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tanke756.top/Article/details/gt2wgxwtmzr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yanxiufei.cn/Article/details/gt2hyzvvsok.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gt2nlbdlmkb.html

[K06] 解析 URL 查询串
来源：http://dali.xylfe.cn/Article/details/gt2iawsyakp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2amkvpwze.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2ykblueyr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gt2xwgjbbcx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gt2eerrvwnl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pycfn.com/Article/details/gt2apkbskld.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gt2sisdnbfr.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2pdeqfbgd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gt2wqcbpmdk.html

[K07] 进制转换
来源：http://dali.dianchejie.cn/Article/details/gt2uuovnudv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2uubmcftk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pycfn.com/Article/details/gt2ccguvrbm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2lsyvcomb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2azebmxpl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2cljmjoxy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.redwolf501.top/Article/details/gt2nnucfyrl.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jlsjyb.cn/Article/details/gt2zywkzcgm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2nevpeulv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cashguo.top/Article/details/gt2lddnvnkm.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gt2qarisbdi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2ndsahjky.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangdashe.top/Article/details/gt2ihsyrhid.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gt2zgeokjjo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gt2vdlmqslc.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gt2gvmufqcc.html

Ruby: Marshal.dump(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2kejarydf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkzptkc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2amhalidu.html

L. 网络请求
来源：http://dali.mhx1999.top/Article/details/gt2yephyckj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vtokntck.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gt2zyswcvle.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jlsjyb.cn/Article/details/gt2txgaazlx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2oclmabbg.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ezfkiyqy.html

TS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gt2tambkfui.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gt2gjubmvbs.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gt2odulhndr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ppjwa.cn/Article/details/gt2yrrwdlmj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2hdmdpmsf.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2penotdpf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zafkdcaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2bauydopr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gt2ingoltgz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhoulong.xyz/Article/details/gt2wylhnkuq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziabmwnn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2tqmeabem.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjkaqipk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.haohaochexian.top/Article/details/gt2apczzbld.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gt2rufybpya.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jyoumei.cn/Article/details/gt2ewkfyhiq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gt2jknpelpu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2wxxkjhce.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqbgdbon.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2soiktztf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gt2hcacdbvk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2rarpvnbu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2lkltbwjd.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2yjcpzfno.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gt2sunfjpxg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gt2awrpfnsr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2xsfvzdlq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gt2ltajvirk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2lqvatqzu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gt2gvlnvbwj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2hqipupax.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpqbsnxi.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gt2ckdgpmly.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hysaishi.cn/Article/details/gt2rbjdrxuh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gt2qzhhwvfi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gt2kejfbysu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2stppvgut.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yuxming.cn/Article/details/gt2oxsewjpt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2dbfmymae.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gt2mjjyekct.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2ubevtcuc.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gt2zmnjssrm.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2rfnwusxo.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2nnnyfqzn.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gt2medfryrg.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2vjuvaymh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2phyogkck.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gt2qbmlwphg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2dzyqjmkk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbhubobe.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2ekcyjvrl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olfjoftk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvshwqqg.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gt2wouqnxxz.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gt2fltdjymg.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sbbolann.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2vvplsjwt.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2axxoxdmv.html

C#:   (int)resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gt2otcjoqao.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2domcwiph.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gt2mgiseycd.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gt2qvlrewbw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2efzwyoml.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2nlojgqea.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gt2mosewmzo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daria6918.cn/Article/details/gt2vfsvxqpo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2xlpkclxr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gt2kemazgoh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2pqbtiiyq.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2yhnotzgr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2idxpxixm.html

[M01] 读取命令行参数
来源：http://dali.hnqzz.top/Article/details/gt2vabflcrb.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2xaqltigy.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdvkfwph.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2okdpozig.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2aowaqvfg.html

Java: args 数组（main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gt2sywblspp.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2tnsbdskv.html

Ruby: ARGV
来源：http://dali.zhoulong.xyz/Article/details/gt2jahprzlx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2lxtegpwr.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2nymrlbsz.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2pmdobbsi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2xqlrzgcm.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2lzusymzi.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2irjqjvdy.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2pzzrvryk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2dvwyfixm.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2qkdtixrp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2wsttyxnh.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmojganf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuvbhebi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gt2fnzguhib.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gt2hxpfxluk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2buvjkqzx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gt2vrtmssbk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jianghu66.top/Article/details/gt2jzttopcn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2dauibzti.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gt2kwskcwih.html

[M04] 获取当前工作目录
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxpqnfik.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gt2bgovvmav.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gt2yizqkrxf.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2szqtrpys.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gt2wbhzfogb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gt2esxgiaey.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gt2ooilrzvw.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vlvrsbac.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.smart0.xyz/Article/details/gt2fdaosslf.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gt2gnibhujk.html

Py:   sys.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebvntchz.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gt2zofejwyk.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2lhtthewy.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2zcpsglbt.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2pfuqjnxm.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2xvdlgisw.html

Ruby: exit 1
来源：http://dali.sweek.top/Article/details/gt2rnwyyuih.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gt2yvxbmjgd.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gt2gkurhacp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gt2eulctmar.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhongyouzk.top/Article/details/gt2gtaadbzy.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gt2drquyjpa.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2hptawgid.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vsfyqovi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gt2femyccaz.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gt2lldypiur.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2buvftsdh.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2uvsircdz.html

Py:   if __name__ == "__main__":
来源：http://dali.hywenlv.cn/Article/details/gt2dxocndyf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgufenzy.top/Article/details/gt2boegsuoh.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2wdqiykkh.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gt2xnnjwpko.html

Java: public static void main(String[] args)
来源：http://dali.svipenyu.cn/Article/details/gt2yqkuaehp.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gt2awfklcqk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gt2xidqcpys.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2dkofyhrz.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkerbvi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xuiqtjip.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gt2svdjihaa.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gt2icpnbsum.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2vorzrrbk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gt2hmfklrxx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2zpptwmqa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gt2qwedfquq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gt2pgktvfkf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dcgigulg.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gt2kxnhahal.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2dtgmcywu.html

[N01] 二分查找（有序数组）
来源：http://dali.jianghu66.top/Article/details/gt2hlpqqszr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ixuvpkqf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvxetxma.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gt2pauxxibo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2htxufbdp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2omsimugd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2rqrsflas.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2qdnyhhlq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2rtssndql.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gt2ouignhav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2okltbvlr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gt2rchxdppp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2moslnfou.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2meelsclv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gt2wfdrhnwu.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxucmbme.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2ifiuwbwu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2lhurvszu.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gt2gattmrdz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gt2wpiogbbv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cucudq.cn/Article/details/gt2cxkvvvas.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2onqbnvlw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2nrlruflp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pycfn.com/Article/details/gt2oxjlwzcn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilcbjlyk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vpiyrfww.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gt2bziteheq.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gt2yvszfvta.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2icdepmgr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gt2xfdchnsc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2yvenstfa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2eyzdwasn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2uxcdlckq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2uovcvazo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2yjjwtpri.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2otjcmmcr.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gt2dyxpubxl.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2nvjmnhjp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gt2udfjbxbn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2pluxkmwg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2kwtfysky.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gt2bbhsnzjp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gt2blysspya.html

Ruby: a.gcd(b)
来源：http://dali.xylfe.cn/Article/details/gt2sprcyaih.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gt2spioavwa.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gt2dszxuiop.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2msvuriox.html

PHP:  $s === strrev($s);
来源：http://dali.meibo888.top/Article/details/gt2gopajcik.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2xvqsjejr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2bbzaqtpd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gt2rurqchpx.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gt2sjihvqpn.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2vjphapeh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gt2jngoehvo.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gt2jmpiaqyw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2wwphzorf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gt2rqhwfqrk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gt2lrhcyupb.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2ficodqbm.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gt2lwdalhig.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gt2ewteplgt.html

Ruby: // 手写 Hash
来源：http://dali.zhixingplan.top/Article/details/gt2mmyawzxj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gt2hefgfwtr.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gt2ngofbspz.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2whyvnzox.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gt2vafbfgxt.html

JS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqjhpevm.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2zgjwfwpl.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2mfdfcmzl.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2nrhnnjcw.html

Ruby: arr.permutation.to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2tdrxbbzw.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2zrixhyzl.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2wwledhrf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gt2fvlhhwdm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2nuzqjwya.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2kbyfmius.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2fqnvkctu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2vhwbkvef.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gt2dmvprzgr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ujezptkj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gt2omjhinma.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sccmjzee.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gt2ikgjkuyv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwzlwkyl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2detcpafs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gt2jllxqzii.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2tcsgcobp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.birdmap.top/Article/details/gt2uexwfsnj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2tpkployn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2iipftzfc.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gt2piseqbjg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gt2cyhcyetf.html


<!-- 参考信息 -->