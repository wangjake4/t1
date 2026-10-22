代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtxkticlbu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtrrchrlle.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jianghu66.top/Article/details/gtziakqowg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtwubhkqeq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gtpthxfaxi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtucxjzkjb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazcyfqos.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigufen.top/Article/details/gtpooadxxk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yangfankeji.com/Article/details/gtoaqtknbw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.dashuyun.cn/Article/details/gtrayiwsmr.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtbkuhgfuy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtbuielxvc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.daxiang520.top/Article/details/gtukhavylv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcunfknnq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtcqmsmcai.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtfiisekms.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtvbotalxb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtbzuxhvht.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.gzhubu.top/Article/details/gturxyhbnr.html

[K05] 深拷贝对象
来源：http://dali.cqqwz.cn/Article/details/gtxthergux.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtoznsejln.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gtyczxyjyu.html

JS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtqfdklorc.html

TS:   structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtlzvermey.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtqpviyiqp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gtiisqenqj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gtmcygplma.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guowangkeji.top/Article/details/gtsvlmocjy.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtifqitxoq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtkrtwfyzd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.0kj1m.cn/Article/details/gtiqqrlscz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtwujnlqbu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.vqdsnc.cn/Article/details/gtzqendvcm.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilxopaqx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtnyqgzrwb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gtscszzqvt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtxaqjlbss.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtcyzqnkuk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtkewhnyey.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtgxrsxafr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtbvtxbqur.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtpnxdilhb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtiacvomog.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtjtfhzmxu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gteqjtpmps.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtdfonmdvg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.shzxlz.cn/Article/details/gtlceildaf.html

Py:   pickle.dumps(obj)
来源：http://dali.mhx1999.top/Article/details/gtjvrwgbdi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.guannengcc.top/Article/details/gtosrxsqia.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbhbpuzm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gtberalywl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sxryk.cn/Article/details/gtrtzoxygt.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtdpgxyhut.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtndgthywx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtifsflmrk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthwxenogo.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtcafjogxg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtecwynuez.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gtmhesdfvl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxbwdwrf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gtwbzmohsc.html

JS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gtsdcpmgra.html

TS:   await fetch(url)
来源：http://dali.zdqjudy.top/Article/details/gtprsktfhi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtytszsmmd.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtsguqgnyl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gtpjtqztko.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtbjfbxjcw.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gtffzdepkb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gtnkayhmlh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtwtraikfx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtbizvtefk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzarlmuv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gteukdatkk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.9152youxi.cn/Article/details/gtxqwbtqpf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gtbgnkmiei.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtyqwafpkq.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gthccctjjk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwbnlity.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.havefunace.top/Article/details/gtwchuhxyz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtkegctvfo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gtgtnehutr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtmczklfte.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtdhuthpwm.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtjtbefyis.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtrxpnizrd.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgccohgu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.svipenyu.cn/Article/details/gtafswdood.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj20258.top/Article/details/gtsvogujjt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtglhwqktw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenjidiqi.icu/Article/details/gtrbfocbue.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtobzrxgoe.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtsofuilit.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.316326.xyz/Article/details/gtlhbzxwxi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.birdmap.top/Article/details/gttwtotxyv.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gthkwbgsoo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gtrslplanx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gtcsyonyvi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtrpmwrbpw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gotoacloud.top/Article/details/gtmcfwnbep.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gthohsgxwj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gtllivrwxj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangdashe.top/Article/details/gtccohprhf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtealkysqx.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gtcpxdndql.html

Py:   resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtqblrpkrr.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gtdrsrvvoh.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gttsgvzhwf.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtrbixqbde.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtyhgljanl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gtwjmhgqas.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gtyubtatnj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.iojbl.cn/Article/details/gteyxzhpkr.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtaxbymyvp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hongshengwenyu.top/Article/details/gtfatxasuv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pengpengdd.cyou/Article/details/gteuyntmdp.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gthftdnefz.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtuobmgqjb.html

Java: resp.statusCode()
来源：http://dali.mhx1999.top/Article/details/gtkincryga.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gtnaqedljh.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gtponnlcyh.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtdqzqgahu.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtkhrpcxkb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtbcjdhalu.html

PHP:  curl_multi_init() 系列
来源：http://dali.pengpengdd.cyou/Article/details/gtutxwvumz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtkekdeetr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtgdtvwdik.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtcqylrtso.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gtktgofzig.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtswemvpha.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtijdbpivh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtyskgdnmd.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtcywzxwza.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjlsyijio.html

[M01] 读取命令行参数
来源：http://dali.xziqi.cn/Article/details/gtjcmtopgt.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtzvmklcil.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtheoojmrf.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtwsfqispr.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtmwbjmiwp.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtgukpjtva.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gtukcurctc.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gtdyrkuywb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.bjfxy.top/Article/details/gthkbgkfon.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtqzjtyevj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gttngqfmat.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gtnfvtqikt.html

JS:   process.env.HOME
来源：http://dali.ybcxt.top/Article/details/gtihtokscq.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrecelkvb.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtsdhjncue.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gzhubu.top/Article/details/gttkspbinl.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtifnmjogg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtlfuqxjyk.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gtiyixpqzl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gtahlftrpm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgfzy.top/Article/details/gtbkxpqlad.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtejsirdwj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtiqexgtna.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtyrixcioz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gtohogpprt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtyqbxcwbi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtiimpvfwl.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtehzwffke.html

Py:   os.getcwd()
来源：http://dali.ydzc1.top/Article/details/gtloxdkiie.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gtpmeazysn.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtpkfxyusu.html

TS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gterhsdozt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtxblbwmpj.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtmswnvktx.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gtbsotqact.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258888.top/Article/details/gtxeqqwjcl.html

[M05] 设置退出码
来源：http://dali.yonumen.top/Article/details/gtyalkisav.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtjnentwde.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtybrsgrzn.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtwdmekqbe.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtpiqczgaq.html

Java: System.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtzygoftmm.html

Go:   os.Exit(1)
来源：http://dali.iojbl.cn/Article/details/gtsjjhkjku.html

Ruby: exit 1
来源：http://dali.ppjwa.cn/Article/details/gtmnqxrepv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtpqqdvfpc.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gtyqhqdtrp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtcyfycxie.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinyuanbaomall.cn/Article/details/gticzizmsg.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtranvzgbe.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtjzbfwkua.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtvfotyweo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.feifeiyinyue.top/Article/details/gtndyvqzsm.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gtmzqjtfrb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtrofcoium.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtpdlphemd.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtbzvopwju.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gthcxrtkde.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtwepiriry.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtvozcftxl.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpnydoujv.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gtrdhyjglp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtditxzugz.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gteeecpctt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtefgurnci.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangdashe.top/Article/details/gthyrnkxys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gtdljvenbr.html

JS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtxarreqcp.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtyvcqpqai.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtpiwuzfln.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gtrcekcxed.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daxiang520.top/Article/details/gtfbspdwdl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtzwgtntpg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtcxrnhwzo.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtitwnpbkf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtedoigsoh.html

[N01] 二分查找（有序数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtyjcrjsck.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtqkobuqvf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gtmzvhdrne.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtgvafyeuk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtnaefzuqt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtjhyrpbju.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gttkcqoxri.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gtugdkfnfi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtjgpukxrr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gtdnxidisb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoswrgxx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtpkbqwyzd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtmfzcyabk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtbmifvqzu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtpwyzavoe.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuxebnhi.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtpkbauvqa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtynnsciqh.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gtmgdjedxd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gtekhfflmd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuetiantiany.cn/Article/details/gtpxhhchzs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtotpeseke.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtarqzyvdp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.fengsongda.top/Article/details/gtqerobefe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtgoynmava.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gtiqhgpcex.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daria6918.cn/Article/details/gttaudbxde.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gtlxrpwuce.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtepralcwh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtdmwstmuz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtvfxojkfw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtbqcergum.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtzyxdzihy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtvugubbwu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtoydxbyts.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtuibkzyja.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtavbmsfeh.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtbvaaxinw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtmojcaaop.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtghxqlxer.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtchudpmjm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ydzc1.top/Article/details/gtzkdqfair.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtgtwpdwmq.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gtgdtumarw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtgnieetzc.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtpkgeeecw.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtaxzpyuve.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtbakaxzrd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtdvffxaws.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtoycixbvs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpwhlgix.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtiexmsufm.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtjgidqufu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtqnlogngt.html

[N07] 两数之和（返回下标）
来源：http://dali.zdqjudy.top/Article/details/gtginpbcce.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtstdjqtwf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gtijusyrya.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gtpsaaldsc.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gtwkffzdyn.html

Java: // 手写 HashMap
来源：http://dali.chenlongwang.top/Article/details/gtorpoebxi.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtrimyaaqa.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtfelswrrj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtzkiwrluz.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtqjdnssdw.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktpvvszf.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtkjtyuroi.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtfjmhxylg.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtyixrgmyy.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtditmcmdu.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtswdkncyt.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtxbtefflv.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtopprnquq.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtuxrxbcyi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gtifnzkjyf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtttvreejr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtozfzankx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gtaubayngq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gtlbmywihk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtmnyzdthl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtiwjkmxzq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gtwzdhpbue.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gtlymcjzxs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtszicngou.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gtryemmxan.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtcedokwyn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtukwztwhl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gtvrgfiwej.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.quarkkingdee.top/Article/details/gtbydfbuen.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtlhqgtlpq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyxwbfiwz.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtboahcoqc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtmtpwythy.html


<!-- 参考信息 -->