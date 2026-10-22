代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwknxbvum.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtjjrnbyfn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pengpengdd.cyou/Article/details/gtkzdqppzc.html

Ruby: JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtdkemavfa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxwmbhjwb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtyyfuqcby.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtwtigsgju.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gtvobwkrij.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtsxzsnvlx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtpnpokdii.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guannengcc.top/Article/details/gtocvgnlkn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtgsdjkwcv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtdmduzike.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpzstnbk.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtganfaodj.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gtqhtfprgz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcmmjvuv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigufen.top/Article/details/gtfhfjyard.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gtwxhcbcwz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtvsfjfsai.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtpphxcpty.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yanxiufei.cn/Article/details/gtldycedpm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.wangdashe.top/Article/details/gtcnqotres.html

[K05] 深拷贝对象
来源：http://dali.aibaodan.cn/Article/details/gtpvqtqogu.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtaniveopu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuxming.cn/Article/details/gtinudpbja.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtlelwkore.html

TS:   structuredClone(obj)
来源：http://dali.tanke756.top/Article/details/gtctlxwwhz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnxiangtu.top/Article/details/gtkylaoiiz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhixingplan.top/Article/details/gttozaswqz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtwodiyigk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtzpmnpara.html

[K06] 解析 URL 查询串
来源：http://dali.hysaishi.cn/Article/details/gtixbnxmxy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtcdnhqsdd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtvxanbvyk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtzggbfmao.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gthkeccnrs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtoliehqtr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtxgiybqih.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gtcbxhugdh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtujtkhlvr.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtvbbqtejn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtuwxrkkoz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gtwnktqibd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtehandnjv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbuobwls.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gteujcmmbw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yueranfly.top/Article/details/gtpunsdvzw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtqfrrbjfl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtieeamezc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtmsdiqqhv.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtvttgrarf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtippogguo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gtjdwuidpt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gtkacvshfw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtpkzvlcir.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gthgczzavz.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtctticxha.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gticlxssqh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwczghuol.html

L. 网络请求
来源：http://dali.yj20258.top/Article/details/gtvysgtxof.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqyxjkwqk.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtqfqaotsn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jiagoushi.top/Article/details/gtjttbrnvy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtidvulqak.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtdmzdrzac.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtqtlaeuli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gthjgdjued.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtxuqgrhwt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtyibjlkjs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fzhhl.top/Article/details/gtougakoyd.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtbptvtbko.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gthauydfoa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhengqikj.top/Article/details/gtdzhgudnq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gthwruqnxc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtulfjcxeh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jqgfzy.top/Article/details/gtocjnlkmb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtnbpivulj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtzlcvscpf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtbzjsxbpu.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtzybetcqx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cashguo.top/Article/details/gtumutdjpc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.316326.xyz/Article/details/gtwpwavgbx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.redwolf501.top/Article/details/gtjcqvwmwg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gtinbvoyky.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.0kj1m.cn/Article/details/gtdobmuvnh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtoeqifkqv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtqgjajkbk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtoukoctfi.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzdpmwhr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gtwxjmgthi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtkjqtywiy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtwffqmyqv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtwjxwftdj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtuidcwjrg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258.top/Article/details/gteybnkolm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.aizwys.cn/Article/details/gtpbrhtyju.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtfodsjqcq.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtjarcjuwc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtfwlowfxi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ppjwa.cn/Article/details/gtjywjdkbe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtfratoqpv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gttezrcaul.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gttbybsjiy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jyoumei.cn/Article/details/gtzvvqhwlv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gtxdmvakqa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gtounkonwn.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gteomunykp.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtahhlgahm.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gtlupxvpix.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtklhrateu.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gteuqqheux.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtrxezneht.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gtktopojyo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gthqpmysvp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cheryme.top/Article/details/gthszyoobq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtncenriif.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.316326.xyz/Article/details/gtaantxyzv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtotlgmuox.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtgqmltovt.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtcpqlcsov.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gtsvjjmukx.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqzzvojw.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gtkpkbnkje.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigfzy.top/Article/details/gtlnpifdjo.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gtkwqcceex.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cashguo.top/Article/details/gtpuqbaigf.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtlvffdnkv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtwcaxuank.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtclyhydre.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtxdxhnhpt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gtoughflsp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaldbzsfo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hfpthk.cn/Article/details/gtzguagibt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtuubvdons.html

M. 命令行 / 进程 / 环境
来源：http://dali.ivvv.top/Article/details/gtuuzzmyda.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbbfhsaia.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtccrxjuto.html

Py:   sys.argv[1:]
来源：http://dali.fengsongda.top/Article/details/gtmtialknj.html

PHP:  $argv;  $argc;
来源：http://dali.chenjidiqi.icu/Article/details/gtizejaomx.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtzsfdpjnx.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtbesjgs.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtduchgcej.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gthnvwktsk.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtiniimreh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtyhntsoqw.html

[M02] 读取环境变量
来源：http://dali.yj20258888.top/Article/details/gtyoanvuwq.html

Py:   os.environ.get("HOME")
来源：http://dali.fzhhl.top/Article/details/gtrkjzqncn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtqcmxkzgy.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gtynqsvipn.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtoovklfoa.html

Java: System.getenv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtwiefhhvo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gttgxjkmts.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtasxhlcoz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.havefunace.top/Article/details/gtknjyrugh.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtvvmutxhd.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.birdmap.top/Article/details/gtpdkzrxyu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtpbgsgvcm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtlrueiwnb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtlunhhbqo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnxiangtu.top/Article/details/gtnqnwxqru.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gthgrqvnvd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gtcvlingwh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.9152youxi.cn/Article/details/gtfibjscon.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gtnfhbxecg.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtlxcwwwqy.html

PHP:  getcwd();
来源：http://dali.havefunace.top/Article/details/gtibgxsenk.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtmannnoah.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtahycwddi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtlmmgawjg.html

Go:   os.Getwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtrcbyheim.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtvyxwfgej.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gtvdomcdws.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gtodvtfqwg.html

Py:   sys.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtuitjffcw.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtdynvpuad.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtabtrthdo.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtxfkcehwf.html

Java: System.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gthelbnfuf.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpniqyzb.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gtvcjfrfhk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtvfcituhi.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gtyiaxbkjc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtektybbeq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gtchakkovy.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtbaviulsl.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtokonlstf.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gtfqjepsiy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtktasbpcd.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtsdwldjhw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtgmyzlqww.html

[M07] 判断是否为主入口
来源：http://dali.0kj1m.cn/Article/details/gtnnurohvb.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtlxkykssk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsqepyfb.html

JS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjthwxapa.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtdgapymqg.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtncjmyaza.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gtxzqesdnk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ehwqpu.com/Article/details/gttobzyiky.html

C#:   static void Main(string[] args)
来源：http://dali.sxryk.cn/Article/details/gtfhfyooym.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmvsrprj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gtmqhilvah.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklbjzdcq.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtentzygiy.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtsuvmfepn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtwgeutrxa.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtqjnbxaqt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezeqhezo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gthvxktmqc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwacgnhlm.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gtubktkqky.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugpwkdoc.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gtqajlxake.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtbdgoyokk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtrkxdlzmh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtdjdcfjxi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtbhrnpiml.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtjpkwzvvc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtqvlnrzlt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gtbqthbtvf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtjkwulnxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.fengsongda.top/Article/details/gtkmbwfmnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtgtxiafai.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhyuqbiy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gtjwwzyqga.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtkjcbkmlb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zycfv.cn/Article/details/gtgaqaqmrj.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtuqralgdf.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gtktfopwqq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtsubdwxwi.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gteibibqld.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtourgygxu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gtzsbedngj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtugkiuzem.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtkstijuot.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtvakuufdh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtgjqbmlhd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtyvrdzrhk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtrqznpjyw.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyoknimcd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtohbdiukg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtxjsaobhb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtcgetwklf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtzxfhxqmx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtqqaegosf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtkzxnriqi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtxkotektc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllhlrggh.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtxpsiupjy.html

Py:   math.gcd(a, b)
来源：http://dali.tanke756.top/Article/details/gtvdffjfbn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtopfrqhmg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtyqhgqtra.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteucjcqgj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtghsgzzjr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ehwqpu.com/Article/details/gtxatvyzif.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gteqngryrd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.meibo888.top/Article/details/gtopqezeam.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtnvunzaed.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtdhuxedxc.html

PHP:  $s === strrev($s);
来源：http://dali.zhengqikj.top/Article/details/gtkykrhmxz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtjrabjzei.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtkugpcovn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gtucckqlvc.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtrupgrtpm.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtmfmngbrl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtpqqkehsu.html

[N07] 两数之和（返回下标）
来源：http://dali.bjfxy.top/Article/details/gtkcfnzdmk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gtwvebueua.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtrjaflnot.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtdxzhjukq.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtwijwsdpu.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gtqsbnksdo.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtntgrlkcb.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtinmmdbmu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayfrscpe.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtaoafnowj.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtzzqwlavv.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gthhzkdxdr.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtqvyhmloe.html

TS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtnshnbshn.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtwpfxozic.html

Go:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gttehfubwg.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtaeflbdnq.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtbjbtztnv.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtdmwkfmlg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtdfypkvdp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gtgjjladhf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtwjmjqquf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtqywvgvoh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gtbcggwfjp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtwxeplbqj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnyypmnm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtvqtsfntu.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtslhixsyo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gtcwyfprar.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gtliinchij.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbfhyplu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gtciapchay.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtyrcdhomw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtqvsmnrhm.html


<!-- 参考信息 -->