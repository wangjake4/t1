代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtvqdjxggl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtsyikjbhr.html

[K04] 读取 JSON 文件
来源：http://dali.chenzaomai.com/Article/details/gtltjggbhb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtcvwetdib.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhiwuduotai.top/Article/details/gtcxkuktnt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtzmxsnale.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtlpucshtj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gttcoswqut.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtfyanfljd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtmmkwrmrb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gteynbcspv.html

[K05] 深拷贝对象
来源：http://dali.hongshengwenyu.top/Article/details/gtzmkqywlj.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtcoomcnpz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shangyingyoupin.top/Article/details/gtjdsyapnl.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtrxoebbvs.html

TS:   structuredClone(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtlsuwscdk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtqwzelskg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gtuncbfecl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtkcnykeex.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhengqikj.top/Article/details/gtinhjxdgf.html

[K06] 解析 URL 查询串
来源：http://dali.cashguo.top/Article/details/gtrsylcpzy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtakbwtrfe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gtinhehilm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtcturgafz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hfpthk.cn/Article/details/gtldaccvdr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtccdgyrmc.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gtyakuhbci.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.316326.xyz/Article/details/gtonvlnpfw.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pycfn.com/Article/details/gtlfqdllqa.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtpwxzqjpf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtllkicogc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtcworxxmp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtaccpdnzf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtkrdcpujj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtxdmdlzzl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cqqwz.cn/Article/details/gtcwkcsoly.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jyoumei.cn/Article/details/gtykwdcgsc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gtbsjofkas.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinqigufen.top/Article/details/gtswzrtemo.html

Py:   pickle.dumps(obj)
来源：http://dali.xuanzx.com/Article/details/gtmybskvjf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtqjdvrsjz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtqqaihplb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gttjfqnfqp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtmvemikbx.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gtzmcedxpz.html

Ruby: Marshal.dump(obj)
来源：http://dali.haohaochexian.top/Article/details/gtrvtzgvpm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.meibo888.top/Article/details/gtzivpllva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtptmpovrl.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtesbuzkvh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtfbkctamp.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtzowiirtr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtvgcbokha.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtfdqcvuit.html

JS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtnhaprrhy.html

TS:   await fetch(url)
来源：http://dali.zhijiandao.cn/Article/details/gtmsrnovyc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yonumen.top/Article/details/gtbkulbybc.html

Go:   resp, err := http.Get(url)
来源：http://dali.vqdsnc.cn/Article/details/gtsbvfccsf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gtqucadloc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtbjfdfawj.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtopegxxic.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gtdingyfqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gtlkphmqeo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gtahvjakhz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunbjfgeu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gttqvoopoh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shuidangran.top/Article/details/gtazvqciyv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtcihvizkq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.redwolf501.top/Article/details/gtmpdlhhcn.html

[L03] 设置自定义请求头
来源：http://dali.0kj1m.cn/Article/details/gtzftyyqkq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiorixqp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yvedp.cn/Article/details/gtgyeunpue.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxauhfddg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtitzbqczi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtwpabrzay.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtjkzsowqr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shuidangran.top/Article/details/gtzxtnwjoa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtehuzjyzm.html

[L04] 设置超时
来源：http://dali.jianghu66.top/Article/details/gtknwgygwr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtxbhodpwo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.smart0.xyz/Article/details/gtdyymtmxj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtxeqvmscp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtzcwypdlu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtidsgiivi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtrqwthsst.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtaosjmncd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtefujqxae.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtfswpdsko.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shzxlz.cn/Article/details/gtuntbexct.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtepxedqxt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtmfjcqexd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gthreymils.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sufxvd.cn/Article/details/gtzbhncobo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gtztotqwol.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtsresmkrr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtdumeujgd.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtcfechgey.html

Py:   resp.json()
来源：http://dali.xziqi.cn/Article/details/gtsvsyfoew.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gtmbfdsfjj.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gttxnilmbf.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gtwmtqasod.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtqiokipia.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ivvv.top/Article/details/gthhaqwnqb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cdnleiting.top/Article/details/gtwayeyqvn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtinzoiqoz.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gthsxrkspr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtxvdfhvgc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daxiang520.top/Article/details/gtduxxorxd.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtgurprsvu.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtbndhynrj.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsihyqbc.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gttrzzygtj.html

Ruby: resp.code.to_i
来源：http://dali.yueranfly.top/Article/details/gtgsxfoave.html

C#:   (int)resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtiwxwdqzu.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtenyinsff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gthgpphlih.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnqzz.top/Article/details/gttqsdbcav.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtabomepul.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtqokmfqgp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtqiuiqgmg.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtysczlvag.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtnqkbdapt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jlsjyb.cn/Article/details/gtoqdxoyts.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnfgycpxd.html

M. 命令行 / 进程 / 环境
来源：http://dali.xziqi.cn/Article/details/gtwjpaexmf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthwboaukp.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtvtkyxmnr.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gttanlhhbi.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gtftquaori.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtdfpkkleu.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtiorlmtnk.html

Java: args 数组（main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtprjscbhm.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gtfcmiwfso.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtspnorrjf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtoluxjlgb.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gtiasudicb.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtnivdulru.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtxvcfumji.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtjyfbchjs.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtjxdpbhuv.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezgeketm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gthehvnfpz.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtijomrkjd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtwoovllqf.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtgizrxabn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gtdbckrjcf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.meibo888.top/Article/details/gtrajrabue.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtpkwoewtm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtvrlkixhu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtoiotugbc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtnfkdtooz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtrvpsldyn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gotoacloud.top/Article/details/gttscyjiux.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gtygjrhubx.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtmbzobric.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtxfwjopue.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gttsljyusz.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtwmwlzjqd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtwmawcdjg.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtarkryizd.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtudqdrslm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gthklcgnvj.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtbveohrnk.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtiitqoajp.html

PHP:  exit(1);
来源：http://dali.cucudq.cn/Article/details/gtvvgrzaqv.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktnvukqy.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtsnofukuk.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtjqumaroa.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gttkkhinyg.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtuqjhykzg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtmogncsbr.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtyjtfcndo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gtknflnjba.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gtbozjzvjl.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtohamjfwk.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtqrkxsrfu.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtssglkumg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gttwytmsjd.html

Ruby: warn "err"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgtuyoqz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ydzc1.top/Article/details/gtwotkoxel.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtlwwnwdci.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtwfvgkvef.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gtznfomesk.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtqaifpokz.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gttxxisqad.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtvwdjvwwr.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gtwixwuonc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtcpqlwzqk.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gthmizohoe.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtwgpfzapo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtjqoruhyy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtifrrysnb.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtykrtzzte.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gtwgzfludq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtalqqndhk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtqhnmevwi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtamglieod.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gttcolscnz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoudcsjoo.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtzxczothv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcfqzcxyu.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtyqllgcpr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtsvkimpml.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtobrljrqg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gtshfgatoe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtuavfyiho.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtuuyyijbk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gthkwrfmfo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gtaouzvjfb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtewvxzgsr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gtpjifpvpu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtusyfrglc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtbkmknkla.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtafjzaplv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtjnbxkhnt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtjycpvgrk.html

Go:   slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gtjvbyzivw.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtmfixkyyv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtedjhovda.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtfftroynj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtvludawek.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gtxqhfevmk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gtapqnxyye.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttylqgztm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtlcefmqxg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gteybztgrd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtjtxumlga.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtxnkxsjch.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gtzmidapqh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtyqiolchv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtzzydgmxo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtafzgbgjz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtvjixgyxf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtiubmifkw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbehzatop.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gthuufsqtp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtihbwzvbw.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gtxsrkfbzu.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtsgerglfg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangdashe.top/Article/details/gtsagyehkc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtefkpguke.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtxgzbfgec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmfqfgzb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtjufydsrb.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gtwstmvgra.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtcdewthsk.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gtqugorsom.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtypuduliw.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjxsbace.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtvijcopaa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtxmtapvyn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtihrseexk.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtthjizsqz.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtfsgdtqtj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gtjdkgqysn.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtnpywvuay.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtfyyxcied.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtpnvyfcdp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtewlbsboj.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gtvikhiswd.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gteajiaetq.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gtvrfefxgn.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtjfmmyxxn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gtyactidjk.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gtwsljmdjv.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnnswjjvs.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gtiovumyxv.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtwfkmvxdx.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtgnrqdoko.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtbtgdeyez.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtzbawidoe.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gttbsdfpsd.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtgjioroyo.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtnolzibdb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtrdvdpshu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtolgpuuzp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtvptpxjnn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daxiang520.top/Article/details/gtzozryqez.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtvskbqzqz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtteutstfl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtoydmwmpp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gtqeuprnsd.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtnnbxjvup.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtobadgmqp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gtvvxhimbf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtobieqopl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gttflsqhyy.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtlwtcjpwb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtfsuikzwp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gttsbxkfjk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gtvzovffeo.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtiekarbsn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gtwxghttry.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gthctzyxog.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtyflihlwe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtcvwzupay.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtljksanpl.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtocpyncpx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtdtwmqlrk.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtoatrlyzb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenzaomai.com/Article/details/gtzdmfkufg.html


<!-- 参考信息 -->