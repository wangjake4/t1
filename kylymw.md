代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.meibo888.top/Article/details/gtghjjiucb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dianchejie.cn/Article/details/gtyrsltwzx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtfkskjvnb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtwsnypvnr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtuqnlqbah.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtpegbkouv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtxigmtuyh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gtkkpqpelr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtwxhelpqn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gtjmabphmc.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtggoojjpq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guowangkeji.top/Article/details/gtvjcnksxz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gtcceoyxrb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtztmhrqqx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yvedp.cn/Article/details/gtahatkhpb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtmdqwtaiv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtfhlbgujm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.gzhubu.top/Article/details/gtypujpthv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gtgwzzyyno.html

[K05] 深拷贝对象
来源：http://dali.cheryme.top/Article/details/gtisgwrmqr.html

Py:   copy.deepcopy(obj)
来源：http://dali.ehwqpu.com/Article/details/gtgarljmhj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.tianlin.xyz/Article/details/gtummixgzx.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtdglsembt.html

TS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtzmkrpfsx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtfzazglaq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.vqdsnc.cn/Article/details/gtfrsvkdcg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gtndlyjxpx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtqjwlqrvd.html

[K06] 解析 URL 查询串
来源：http://dali.hnqzz.top/Article/details/gttpexqizu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtbngdrdhu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yueranfly.top/Article/details/gtuhbsfbrd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtsxmboiru.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yangfankeji.com/Article/details/gtjdjlvdny.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtdrxopxdh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gttcrpniwi.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtifhacznn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtotvetfjn.html

[K07] 进制转换
来源：http://dali.hywenlv.cn/Article/details/gtmmaylmqw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtwyipgqja.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gtipvfbteq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtsyodemmp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgufenzy.top/Article/details/gthisamghj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaihsjhp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtpwgwmvqy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtjscmxnha.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtrpmrkyov.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtyizobfup.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gthozfmmov.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zdqjudy.top/Article/details/gtvxzxeksl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gtfxcwacco.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtglfimkag.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenzaomai.com/Article/details/gtqnaazlup.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtwyiebtet.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtsbrjuqyt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gtjlrjutjw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdvbajkfl.html

L. 网络请求
来源：http://dali.yuanzhike.top/Article/details/gtlbhqepss.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtlwjxuvxa.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtgetjqlee.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmslnbgg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gtsxdqmjjz.html

JS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtbzfiihih.html

TS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gtphfowknl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.meibo888.top/Article/details/gtvskaksnc.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtzsbrerpa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtwwpbhgsn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gtlxrhdbmv.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtehadltjg.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtvqixzaax.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gtuwmyjmlt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtofudbpcn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtlpgxlckb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtpuxoebbk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gtjunuymtp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daxiang520.top/Article/details/gtetjvzhqf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdjwjlgo.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gtguljfslo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.daxiang520.top/Article/details/gtmjknbjxd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gtpbsbxcmt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gtgigsyezj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtetaslxhc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtsdcqscdn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoysiito.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gtxumzncch.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gthfiirjgi.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gtoeepuggs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnxiangtu.top/Article/details/gteoshrrby.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gtczgfihkp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gtvcknlryv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkswjfuik.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtkisktmvl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gteydpbxzn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pycfn.com/Article/details/gtrkkqbsij.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtiuajzroo.html

[L05] 上传文件（multipart）
来源：http://dali.yangfankeji.com/Article/details/gtrspkbhns.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtmpkdhybm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gttegvxfnx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtwfmqrmqb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gtqyeniqpj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtedobmfzw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gteylyyqaj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtmqlvpefw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtimqwnpyw.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtjuwqrnve.html

Py:   resp.json()
来源：http://dali.ydzc1.top/Article/details/gtrnwymnwe.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtscoeilil.html

JS:   await resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtdfychmux.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtmfnhvcad.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtksxennci.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtlytpwcks.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gttrfxedja.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gteemrszkj.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtxthfotlz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtepwkbjce.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpgntiyg.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gthynnwndi.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtbuxgsnun.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtvmgrjtyw.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtxshvrwps.html

Ruby: resp.code.to_i
来源：http://dali.jianghu66.top/Article/details/gtiisgsxmx.html

C#:   (int)resp.StatusCode
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfrtchuo.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gtryqkqscw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtvawyohya.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtnfjxudjj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtadlggugk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwahmcnt.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtllduxkah.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtlamqzbsj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gtjmxpeqmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhlncwuw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalfwavim.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnqzz.top/Article/details/gtqxdrvfuf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtglbbvaay.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtyjcpihbo.html

Py:   sys.argv[1:]
来源：http://dali.zdqjudy.top/Article/details/gtwurkstes.html

PHP:  $argv;  $argc;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrewijgoy.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtnxpqblis.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtgwweppou.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtgcawjyve.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtdvykggcl.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gttopuyxjo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtdrenwzcc.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtaqquymvt.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtklrvqqmt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gttjylcdwq.html

JS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtabxunxnk.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlluelhj.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtjtarkrkg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtqpozxnnd.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtqxiehkiq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtrccbhciq.html

[M03] 执行外部命令
来源：http://dali.yanxiufei.cn/Article/details/gtbhmjodrn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtqhxtzeub.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtpetgmfdg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gzhubu.top/Article/details/gtjylxtmvq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtjwzxbodt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubljctdd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtksbwerte.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.aizwys.cn/Article/details/gtvvelgasq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtmyllklct.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtqvoolyuq.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gttfgtdwkv.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtjmhunroe.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtjzqofqrw.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtegdyslno.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprlysmeb.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gtajgbiuif.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gtxbsdsagz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtcwrfwxzu.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gtujbsapnq.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtqzokvoyz.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtbahumgpg.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gthzzqseyy.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtnulelguq.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtkkkdwpoh.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtcodvheox.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtqfdczwes.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtmukixgvz.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsrougqu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtdwetpxkh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtnlytzwnq.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gttyvdkuxz.html

TS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtlvxsbpmw.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtqbnyjftj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtznxekxnt.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gtyldiobiw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtvtffrjur.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gtwasyapfc.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtffzfqdwl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gtjwilybcz.html

JS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtazauhrod.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtxumwpspq.html

Java: public static void main(String[] args)
来源：http://dali.ehwqpu.com/Article/details/gtvjlprahk.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtbmqlzjek.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gttklmcdiw.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtmvwyvbzw.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtontdxxtv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daria6918.cn/Article/details/gtmvhkbijh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtscpxpzzj.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtywiwteqs.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtswqlzzis.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtecjvdezc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtafhwodci.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtsnbemofd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtbgpaqcui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtikyykuib.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtzwkfpzxt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqvltvdqs.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtzvpmxcvk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtxhdajkgz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtscqplzqj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtotyaskma.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gttpfxeahq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtdxyocvei.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtbdufjpxf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gtknaorkkc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtsttdvsrp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfsbtdcl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtptovkfdz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtlajjuqmo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtakrvvlzd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtnazxpvro.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtelpzbwua.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtzhifmroq.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtdluerixl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtoelauelf.html

[N03] 快速排序（分治示例）
来源：http://dali.yanxiufei.cn/Article/details/gtxtdvyvyu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gtpsewnpvq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtmvcxvcdh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtctervxcr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtahbubgby.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gogol.net.cn/Article/details/gtzagppsho.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gtfwepjwaa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gtrndowyio.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtcoebqfzh.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gtdjfvhgyc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtyjkptnqv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtgbicdtou.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtnexzyeyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrifsebg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtsptlitmd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtkwwiybxu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtfhsdwbyv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtrvyjwwyk.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtbxkaogsh.html

Py:   math.gcd(a, b)
来源：http://dali.zycfv.cn/Article/details/gtzbrzqoah.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtivybzowb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtfcqbkvge.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvgpcrshu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtiabjxtkb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlswhfct.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtnrahsdbg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtqtrqduso.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtmmplrdsx.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtippkscac.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtwhbxgizw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtjklnvtmd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtaooypmmj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtmxvloaqn.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gtjpzdmfvj.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtidngyunr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtnwcpdvwv.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtsmeuaigc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtsgcyqdtw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtsvrkqrgl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yongpay.top/Article/details/gtlzovdcja.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtaoigxqcr.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwqavlqb.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtjpqkfdyp.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtevlbjave.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gttlqmobic.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtqcdfuxqh.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtpdkqwime.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtqlnxnntm.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtxuulmpdz.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gteefanfbu.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtdsngfitu.html

Go:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtnwvotqjh.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gtgqnktetu.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtveboqocj.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gttgdqikem.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtrxdozufs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtlnvxixzi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtxktwziaw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtbwemrewx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtezxyktaq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtagnzxojv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtakyshnjw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.snrcjt.cn/Article/details/gtrgtczmgx.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtqnupqsqo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gtcjsexccg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtfplzwtox.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtgectsvdc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdsddmdo.html

Java: class Node { int v; Node next; }
来源：http://dali.tianlin.xyz/Article/details/gtfdqsvwga.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtdnycnrlb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtiiewrfwm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gttpwvaqng.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gthydsziqn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtehnmchop.html


<!-- 参考信息 -->