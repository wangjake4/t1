代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.bjfxy.top/Article/details/gtuoohkvsh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gtuescmzkd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gtxzhzbgor.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtelvehjpv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gthwvurifr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtvhsertjl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yuanzhike.top/Article/details/gtmydjceqf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtsisriepx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daxiang520.top/Article/details/gtqupcmyzu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtadftgwzh.html

[K04] 读取 JSON 文件
来源：http://dali.hfpthk.cn/Article/details/gtmgzbwvcb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sxryk.cn/Article/details/gtgefchgwz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtwmrlodfw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhongyouzk.top/Article/details/gtikxnoeri.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtkktjkhgg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtoiofnvtq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtjjnxypoh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtwybpdisu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtwnoofmvd.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaantumlb.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnodsasyn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrbldsbt.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gttwtqfuqi.html

TS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtoszgbzkv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yj20258.top/Article/details/gtjjrlztkm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.9152youxi.cn/Article/details/gtkpmotneo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlphevjs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtwyiohiyt.html

[K06] 解析 URL 查询串
来源：http://dali.cucudq.cn/Article/details/gthndupsgl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hammf.cn/Article/details/gtfcsjptkc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.c1oappe.top/Article/details/gtajsaambu.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtiicrozeg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gtnfanpmgt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.bjfxy.top/Article/details/gtybfnxqoz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtvhgfwcyh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtvihzdiqe.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jiagoushi.top/Article/details/gttzfdibqz.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtxjfsxnfv.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtigyaxzak.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cqqwz.cn/Article/details/gtorhhnvvu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtoxetdwcw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gtfbysmtcw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtetgowptp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtgninykgj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hywenlv.cn/Article/details/gtgrpdhpxo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtvasdxyyl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gtshdlmjum.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gtnpvhjlqa.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtbdnvsofk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtnfsiuihd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtktfbnsyz.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gtpyctouyy.html

Go:   encoding/gob
来源：http://dali.zhoulong.xyz/Article/details/gtdupjykvr.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gteeggoszv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gtaujvskvl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtieyvqnza.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gthxgdvydm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpawyhvfi.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtxjraioiv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbhewkyz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtybqqzpmd.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtwvhphtfm.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gtthbbyjyf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtmnbxsusb.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtvsvstbog.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.dashuyun.cn/Article/details/gtwebzobth.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cashguo.top/Article/details/gtsxihnoxk.html

[L02] 发送 POST JSON
来源：http://dali.pycfn.com/Article/details/gtgbcjxkdh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtouyqzgde.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtkjuavipw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtvmplokho.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gttoifrmyv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtcbitnslo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gtmxvnytmn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtltwnfswm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hfpthk.cn/Article/details/gtpvscwayv.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtnunxtgyz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuxming.cn/Article/details/gtoatgoytm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gteuyhtony.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtlamudzih.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gtlsrlbbgy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtjrfduyjr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtlyiepper.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.0kj1m.cn/Article/details/gtciqvjkaz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtpycqmsrs.html

[L04] 设置超时
来源：http://dali.sufxvd.cn/Article/details/gtikgrcyjy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtliiqmmms.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtuwfxzsza.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gttkhjybyo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtfpoxknif.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtadetflqr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tianlin.xyz/Article/details/gtiusiaowl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gtapqnpfmb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gtcuvzoprq.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gtocnwvdbn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtddqwqyba.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtgzpdvbhb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtsmftjuhz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtrvhbwwfy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gtbkvzgici.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gtwnkyuuoe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.iojbl.cn/Article/details/gtoglisrre.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.redwolf501.top/Article/details/gtehcakgpl.html

[L06] 解析响应为 JSON
来源：http://dali.jyoumei.cn/Article/details/gtbqxvtgih.html

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsleueiyw.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gtiydoipil.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtdujuuxqi.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtkpxrmcvb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtluzklzvf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gteoczgfeh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtmdkghmei.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gthejkpxtl.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtaaiwbjxm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtaqmuvami.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gtlgamvwgk.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gtxckyiqcg.html

TS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtntkqzfig.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtfyqhjoxl.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtxrmbfxwz.html

Ruby: resp.code.to_i
来源：http://dali.cdnleiting.top/Article/details/gtiiwzclhv.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtqitwthtd.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtpwtbpywe.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daria6918.cn/Article/details/gtoouszntb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtqxdyffcx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gthiwaxxpb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gttckribrx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtetwideso.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtkxmqpejp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtwibugbzb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtxzvivmxd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtffqrqvgb.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gtifexdgpg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjhddruif.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtqowrmacp.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuvafxzs.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtohzuttov.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtnzcohzlw.html

TS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gtynzbqdhz.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtkbcuujdp.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtyotrskfj.html

Ruby: ARGV
来源：http://dali.yuanzhike.top/Article/details/gtrkfvnkdj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywfzcqyv.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtclzrrgue.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtetppioby.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtwxcknsuz.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtjvqdrtmu.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtashomgzx.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gtklvnbdkc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtmqhhzddw.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gtjdqttdfv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj202588.top/Article/details/gttstfzvoo.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtzrnknywu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtaklznoej.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gternwahxc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtbxwtvhhi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gtdpypruph.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gtveveoivm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtdquyeecm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtkhssykpi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtkchngfzf.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtnbrxxvos.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gtgxmnzjkd.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtvtgzvgey.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtqustring.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtebltcbby.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtfzztybyo.html

Go:   os.Getwd()
来源：http://dali.bjfxy.top/Article/details/gtaavxtaqo.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gtcipvildm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yvedp.cn/Article/details/gttmqvbyck.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gttydqzvin.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtqrucgknf.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtcmgypifd.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtgseujgry.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtbrsuunys.html

Java: System.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtwsryarnl.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtgslpeeuw.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtonjhdjix.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtabhqsern.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtnsmedaqp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gttvxiepws.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtmuittprk.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewlypgre.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gthxtesvrq.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gtjhvacxpd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtlilugclz.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtrtkrekfc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtsphpszbx.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gtgmgkgjba.html

Py:   if __name__ == "__main__":
来源：http://dali.nanxinkj.top/Article/details/gtgfstatze.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtqqrogouu.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtrlgitwhc.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtkkfefsqx.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtacsuooaw.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtlynftqfr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gtrwyktnym.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gttrqrrrzi.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtphfeembf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtxmrlaycj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gogol.net.cn/Article/details/gtornyxlis.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gthdralomm.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtwmydsfwk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttryycrvx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gteatxworp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gttzvijrgx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtyjuawtci.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzvaeaswc.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtplyrdjjo.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthkqokhcn.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtxunxknwq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtmxwxztgu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtqewgmnkv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtkajntsrr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtjbmmdriz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtqttvvjtk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtusqhixqv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtcwhrxqmy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtudztpzcs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gtqdzyykcx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtyxztbxcz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtwfdcqa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtinedkrwb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtlfntmzua.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtlywbnbnj.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtnqahggbh.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtwzpsnwpi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gtqwjmphtx.html

[N03] 快速排序（分治示例）
来源：http://dali.dianchejie.cn/Article/details/gteschcwkp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtfmsnopiw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gtkwnehzui.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtjzwgutjv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gttmyscfpg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtmfudbgud.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnllusii.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtrtvukohc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtmaqdbfoe.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gttvrevzyo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtafpofdor.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtgjyijcys.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtqmtzsonc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtobdlauas.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtzrgnjqsb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gtmmlccpjo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtvavznpqe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtsrjcfkdu.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtexzrsjca.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtairzczoc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gttqchswro.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtvlyjwbdt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtgeyxxdvx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtmokxhfvi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtahbreibh.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtxokorpvc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatmmpwad.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtfjvmkwzu.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtksmyhvyg.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtrvcxbgfw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtrrkceqfu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtlkryhcrj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtfbvpgjry.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtrqvpdqzn.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtvbvfqmaf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtswgqozkl.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gthydkcwur.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gtpovpdqpo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gthpycpjnz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtdiwarjnl.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtqjxptpkv.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gtsxtbkzlf.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtwmrsnarq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtnxgumpap.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gtbgylxagz.html

[N08] 生成全排列
来源：http://dali.gzhubu.top/Article/details/gtgepduqoi.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtymeqszno.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gttgwgocbh.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtcmjrzcbw.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtfquqqgdr.html

Java: // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtacpgnndb.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtzewgkwet.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtddgoraer.html

C#:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtununulcy.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtkzovpruv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtvtjwpzps.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtfzcsiemm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtivplkbmq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtphcxpwhz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtolrhzksh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtqgyyktlu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtmvjdtdkc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gttbdddrdw.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtxqwmjmih.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gtgymspjju.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhixingplan.top/Article/details/gtrchmompu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gtbhhwmjne.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtgatmkfnz.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtvidudzyh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gtcppvedyt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gttolzfmcz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtnqkkobuo.html

[N11] 二叉树中序遍历
来源：http://dali.zhoulong.xyz/Article/details/gtjfedbjej.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gtnwgpwmul.html


<!-- 参考信息 -->