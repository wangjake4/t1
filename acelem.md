代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.sxryk.cn/Article/details/gt2zlxhgeqp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yj202588.top/Article/details/gt2ovmuobum.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oougxbyt.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvfrgtht.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2jsqailqv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.snrcjt.cn/Article/details/gt2ebcvhzeu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shzxlz.cn/Article/details/gt2vmokcorj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gt2trscjfla.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gt2naoxyhcd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gt2puzpieer.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ygdqdshf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tianlin.xyz/Article/details/gt2rkwtlpeo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cashguo.top/Article/details/gt2odvfoimm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqgcczdm.html

[K04] 读取 JSON 文件
来源：http://dali.jianghu66.top/Article/details/gt2hjdrxrvd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yvedp.cn/Article/details/gt2amlkxpuz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gt2ddjmlkrb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yanxiufei.cn/Article/details/gt2mhdvltdz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gt2offqpppc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gt2vrejcbip.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gt2fzrqtxzs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenzaomai.com/Article/details/gt2orjmipyl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2jfrbaias.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2cbqnpvmi.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2pxiczuzi.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2kklbxqic.html

JS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gt2yioqaivr.html

TS:   structuredClone(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2qucskgmm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuanzhike.top/Article/details/gt2ecritgiq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xylfe.cn/Article/details/gt2nrxwlonl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2udkfqbgj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aizwys.cn/Article/details/gt2tgdhzbqg.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhtzibc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2qyotzhzz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.meibo888.top/Article/details/gt2cfrowyrr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2zxnrtxbz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bekkyvqv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yonumen.top/Article/details/gt2limfsqua.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gt2axsdacxw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aizwys.cn/Article/details/gt2alpyalrl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2nvaqtavf.html

[K07] 进制转换
来源：http://dali.ppjwa.cn/Article/details/gt2fsuordbq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2rxiqxmwv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2ilmekbvo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2kpjzjvpb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2kqjvasgh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpyhggwp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gt2gkvojwla.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.andypj.xyz/Article/details/gt2hddluhlg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zjhbyhqn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gt2xkzcdrzp.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2vgwmemty.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2kgloubdt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzjnvqaf.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2cwzwfoyo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqkvxeof.html

Go:   encoding/gob
来源：http://dali.smart0.xyz/Article/details/gt2mbkyjlrg.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtkbpbim.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gt2wzyvkxxd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qynbzhvz.html

L. 网络请求
来源：http://dali.jlsjyb.cn/Article/details/gt2hjpulyjo.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2zzgxjtho.html

[L01] 发送 GET 请求
来源：http://dali.yonumen.top/Article/details/gt2wucahkai.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gt2bmaukljz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.haohaochexian.top/Article/details/gt2gzltdbvw.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gt2bewzhapu.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2svizdmtx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yangfankeji.com/Article/details/gt2uxmhlqfe.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2pnxwfplt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2ggthjblj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gt2xabowqeh.html

[L02] 发送 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2zrouzxgw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2xyqueynt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gt2wijpyawp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gt2dhyfbuqi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gt2rzjockwo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2fgtygpqi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangdashe.top/Article/details/gt2xsemlacr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gt2rpwdhnsa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jyoumei.cn/Article/details/gt2sajaqsqx.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gt2pxletenp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.redwolf501.top/Article/details/gt2isplabsq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gt2cngvoqdc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.svipenyu.cn/Article/details/gt2jfdcsuqj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2vxlvtizy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gzhubu.top/Article/details/gt2nywccbqn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gt2uymibywl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gt2jduydjsr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvnlcpea.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gt2ervkcdde.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gt2ihoehyca.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jyoumei.cn/Article/details/gt2jhrkxoiz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2urynyrbr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2gjshofvv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.bjfxy.top/Article/details/gt2vrnxtbxi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gt2rozfwxxc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gt2yphxknnx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2vadlvxvs.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2owlmpitg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jloffwax.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2gfojrxhv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gt2fvhsmvkg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gt2eawsckdn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gt2woxhwmwj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gt2swelchvh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gt2olylpmlz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gt2eyffzwzo.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2geniqdiw.html

Py:   resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2sczmeviu.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gt2ypwgwidf.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2dkgxynhf.html

TS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2poqqyttz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gt2ognilpxt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adqftiqn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cqqwz.cn/Article/details/gt2kexahwmy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gt2olimnfaz.html

[L07] 处理 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gt2slofrnti.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gt2djdphevs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gt2raotvlgp.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gt2ujdswzww.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2xkdmhxvf.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdehtona.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2pxbfwmtq.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gt2qccdsrir.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2xpfpknnv.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2inoyshoh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdzvplce.html

PHP:  curl_multi_init() 系列
来源：http://dali.yanxiufei.cn/Article/details/gt2wmitvszc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2eotlvyxo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2yuedptnk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aizwys.cn/Article/details/gt2rwsbycsn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guowangkeji.top/Article/details/gt2moncwmuh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoreizrh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258888.top/Article/details/gt2onulqwpv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rywwarkt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gt2ehonlavt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2kgerwkvs.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2sqypuznp.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2uzrquoxg.html

PHP:  $argv;  $argc;
来源：http://dali.hfpthk.cn/Article/details/gt2dunviylt.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gt2aceowixy.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2yaszhxej.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2aynvtbow.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfagstwv.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gt2yqvczkmt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2lrclzhyl.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gt2spiuoomf.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2ymtmypji.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2zsbkgdsc.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gt2iqkdnoot.html

TS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gt2mkburjyo.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2vzzswexm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2furllcls.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gt2efxevxer.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2qsvixjbo.html

[M03] 执行外部命令
来源：http://dali.zhongyouzk.top/Article/details/gt2jmarkzqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2igkyirgd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2todmebjq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2drhwzzyy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2hoiedgsb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2trznzidy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gt2juckkhup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aibaodan.cn/Article/details/gt2wrxkdkel.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oscapgkj.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gt2eiejlpni.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gt2bihubntn.html

PHP:  getcwd();
来源：http://dali.jyoumei.cn/Article/details/gt2utcignmj.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2jdynhgtb.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gt2zehaifrj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2gghnkgve.html

Go:   os.Getwd()
来源：http://dali.9152youxi.cn/Article/details/gt2rsnhecxq.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gt2dvkwxaby.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gt2mpovldkf.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2esikvhne.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2kqeyraoc.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gt2cckotuxm.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2hfwhjaua.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2whmnuyvy.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2bjefxpyn.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2frwscbqc.html

Ruby: exit 1
来源：http://dali.yvedp.cn/Article/details/gt2nqwilpvn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gt2latkwjpv.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2wlymqeea.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2rltszjrj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyfhswvn.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gt2gexaqcxz.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxamfdfb.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2wqxpoyfe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjribqvs.html

Ruby: warn "err"
来源：http://dali.shuidangran.top/Article/details/gt2cfarksqx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sufxvd.cn/Article/details/gt2rcjsowev.html

[M07] 判断是否为主入口
来源：http://dali.jqgufenzy.top/Article/details/gt2pkqxlrrd.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2zwzcvbqs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.iojbl.cn/Article/details/gt2gdkftvlq.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2uycrjdhc.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2ioiittct.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flkrbqix.html

Go:   func main()
来源：http://dali.daria6918.cn/Article/details/gt2vwetmnvh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cheryme.top/Article/details/gt2obucvcmu.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gt2obxukcmf.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gt2qednejfc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yonumen.top/Article/details/gt2qrnprfis.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gt2hucubphc.html

JS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gt2bqvqqqli.html

TS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2zwmhkzyh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gt2odxclcni.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lijkfefq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gt2yunbggse.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vouvqcie.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ewezztgv.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2osizypri.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2vslrajid.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lizoxvfe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2agczaeyp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2ricuhucs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crrcwsdq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gt2xszqhbnj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2qzbkndbg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2sbnhogry.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gt2xypvpeed.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2ahfvrvme.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcdzmozh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gt2oftldcjm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2llulbfic.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gt2qastyyxm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2vqnkomzx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj202588.top/Article/details/gt2xkcvlfnj.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2jxmjtted.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gt2zcxbazme.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dawrjlie.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gt2sjyfbmyh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gt2vogpzvad.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gt2xqkzlbeu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgufenzy.top/Article/details/gt2kcqiguvc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sayshujn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2srwbehxj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2cbwhdxxh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gt2esmwuepn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gt2rgpwmelf.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gt2uldpbnxy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2zswqjcjp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2otymbkqx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ynavphbd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2ebnsocki.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2tmvgxfdd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gt2jfxfqcvq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2krsgvagz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2aeauonbc.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gt2eajjpiko.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpwghdog.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2whcaqlma.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2cxmvppzh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2navuldfo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gt2kyfkbiqd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2zucbelwm.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2gjxdhwyn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gotoacloud.top/Article/details/gt2lscplomy.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gt2bpphnvod.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2hflenngf.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2cqgqrzne.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2tvsuucyn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2xqjqhfnk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenlongwang.top/Article/details/gt2lefkdkdc.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gt2joigptdh.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2gjwzhgzo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2bpjzbaxn.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gt2ksfkxswa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cashguo.top/Article/details/gt2ualnpnxn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gt2kddnnfqt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ujlofvuz.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2sttjeshk.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gt2zxqeglbv.html

Go:   // 手写 map[int]int
来源：http://dali.zhongyouzk.top/Article/details/gt2bfjuzoes.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gt2xjjkbinx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cashguo.top/Article/details/gt2jstwuvke.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gt2mkfgjkhs.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2bpmjoumg.html

PHP:  // 手写递归交换
来源：http://dali.nwbrower.top/Article/details/gt2ubnzignw.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2evszapjl.html

TS:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cwaovlup.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2omveapmq.html

Go:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2tqotqtkx.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gt2seuzkaul.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2dwxzypes.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjltkver.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2rflhjbio.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2mvwunbgp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2owjqfwyi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gt2gcojwwaq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2urocjwkd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gt2xhswfufy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsonoaik.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258888.top/Article/details/gt2dflvieez.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gt2qmmxxkqa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yongpay.top/Article/details/gt2rzvixlya.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmowuyww.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gt2jprfieve.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jirrlwjj.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gt2ccnkitwc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gt2ucgtkbyt.html


<!-- 参考信息 -->