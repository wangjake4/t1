代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtekregadh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtlvgbzaug.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtwowdyapp.html

Ruby: JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtcdwczejq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gtnxtmcdel.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuanzhike.top/Article/details/gtojzwvkjr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcqaxuij.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtqzksorhj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gzhubu.top/Article/details/gtxhzrkcip.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtmouqfcpb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gttcqzlrap.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuxming.cn/Article/details/gtwkpqfppj.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvdcfrgl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtkkculcfi.html

[K04] 读取 JSON 文件
来源：http://dali.cqqwz.cn/Article/details/gtjvdoljgt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.dianchejie.cn/Article/details/gtybvakpjl.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.quarkkingdee.top/Article/details/gtyaaljdpa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosnkpben.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvowvgcpk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtvlssogxv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtpvjjlmbg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtkpvblmka.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtsosgxvzu.html

[K05] 深拷贝对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnawnxbe.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gtuyiyeocs.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtghxuxwld.html

JS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtmjhssdnu.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gtgunoelvd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtddyozdxg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuxming.cn/Article/details/gtrmnqoysk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtztbjucdq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.birdmap.top/Article/details/gtjmfzcalr.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtldsepaht.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtfgcthrqn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.birdmap.top/Article/details/gtbyrdursx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtzncdcwyq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtyrmocyfn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gtupfdrbwn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gtcshdcuuy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gthmzdtjjo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtzjwpkfev.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtgqsxxrwo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtftyxvaho.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxuanxn.top/Article/details/gtpeqhryao.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlbaflfx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gttgqvcnuk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtgfoxveki.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtgwnmsafw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtxlvikxbu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtccbbrwse.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtluifbxrq.html

Py:   pickle.dumps(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtonbnmkoz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yvedp.cn/Article/details/gttbbuoovq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtfwvmuwfo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nwbrower.top/Article/details/gtqesopacv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtmeokpfmc.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtgpnxjzuy.html

Ruby: Marshal.dump(obj)
来源：http://dali.yongpay.top/Article/details/gtbtzuouia.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gttqnrsgtx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvxgpbsw.html

L. 网络请求
来源：http://dali.sufxvd.cn/Article/details/gtyymumggg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtpnhcwghw.html

[L01] 发送 GET 请求
来源：http://dali.ivvv.top/Article/details/gtglfnokkg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gthvwoouhe.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtguilykyt.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gtguqghknx.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtewyrfhzs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gteisgmvnc.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtbfvdmqzb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gtownpuvyz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.svipenyu.cn/Article/details/gtplzdxhoe.html

[L02] 发送 POST JSON
来源：http://dali.iojbl.cn/Article/details/gtgdayxgjn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cqqwz.cn/Article/details/gtczwmvrwd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzywohyyg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtzdjwbkgb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gteilrhsxi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gtvlxmwdjy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtyzulkbtx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmiyeppc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hysaishi.cn/Article/details/gtatghtpdd.html

[L03] 设置自定义请求头
来源：http://dali.yj202588.top/Article/details/gtlfqbhbym.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhiwuduotai.top/Article/details/gtwiemzcgg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cucudq.cn/Article/details/gtmmeipwgy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtxqfpmotp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtfuioowyw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtfhanuaiz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtjwkvgfsn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtbegviokc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtxnkvzoyu.html

[L04] 设置超时
来源：http://dali.ydzc1.top/Article/details/gtyqjpoohp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yueranfly.top/Article/details/gtajqzsnuj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigfzy.top/Article/details/gttsankhxm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shzxlz.cn/Article/details/gtdplchadz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtdgmcwhqu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gtlbgvtfyc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcguofeu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuxming.cn/Article/details/gtgdptbske.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gtlgekjuux.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gthsshfqiv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtxcezmdej.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtrldqpwhy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtabtusltq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhengqikj.top/Article/details/gtvxwqsulf.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gtcagyfrxc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gthpzvzkby.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtbcmizitt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtuvocsiai.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtgnshrvse.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtwwwucdcp.html

PHP:  json_decode($body, true);
来源：http://dali.ydzc1.top/Article/details/gtlvrnvnrg.html

JS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtiihiwfhx.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtqjqdssoq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtobqzloxp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gaohongyu789.top/Article/details/gthtvshhvr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sufxvd.cn/Article/details/gtxhgomfgy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gtwymdlfwl.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtcolbgvnm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gtppigqkgy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gotoacloud.top/Article/details/gtnphrxmwf.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gtlmrnsbsu.html

TS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtmseybrac.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gthrjcihvg.html

Go:   resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwdgklxp.html

Ruby: resp.code.to_i
来源：http://dali.nanxinkj.top/Article/details/gtztgvhsik.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtsfgwpooj.html

[L08] 并发请求多个地址
来源：http://dali.feifeiyinyue.top/Article/details/gtnywoiggo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gthfuahgff.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gthrwiwgig.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtlyqnjnzo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtgrqsglsd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gtrnobpfcv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gtiwsaxxgy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fengsongda.top/Article/details/gtgzypezip.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtixlfizkc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjbpcbkfo.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gtxgiswwud.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtoekqjhlg.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtubbbgiqp.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtvstbkvbl.html

PHP:  $argv;  $argc;
来源：http://dali.hnqzz.top/Article/details/gtnogstgwc.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtduffaugi.html

TS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfmntimwy.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtlxkktqjx.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtbxcoplrf.html

Ruby: ARGV
来源：http://dali.yuxming.cn/Article/details/gtemjgtkll.html

C#:   args 数组（Main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtaikgnzmg.html

[M02] 读取环境变量
来源：http://dali.birdmap.top/Article/details/gtlpdanmzt.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtudnzszhh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtvmbioboj.html

JS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtrkvdvafp.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gtlxlgjtaa.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gtlsyuudyx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtmvfykgme.html

Ruby: ENV["HOME"]
来源：http://dali.cheryme.top/Article/details/gtygdhsjjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtxnjvxvou.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtxulrqjek.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yonumen.top/Article/details/gtgidmvqdy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxtipuek.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gtsgburkyd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtjsdprhlk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtzeoitefc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gthdjitoqj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sxryk.cn/Article/details/gtsarhquoa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yonumen.top/Article/details/gtpkyjwynp.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtqmbhhepi.html

Py:   os.getcwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtmircyhjh.html

PHP:  getcwd();
来源：http://dali.xuanzx.com/Article/details/gtursynijs.html

JS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtpnogarxt.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtzflyiywr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nwbrower.top/Article/details/gtbtcgngam.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtkoylhvti.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtrclwnwlg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gteujzhwnl.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gtkwkioauk.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtwvswastk.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gtgmnzijsn.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtnrwsutuj.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtswtncjif.html

Java: System.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsfmjjnxj.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtkzcvlnbm.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtguopouaa.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtfmljwcjm.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtqitrsasc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtsdwhcdmi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gtzhkbicgw.html

JS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gteewdxkmp.html

TS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtwlygifgt.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtncatggmu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtcaxncrdw.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gtdwyoxwvv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtcxjvrsek.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtnhqiirrr.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnqzihbt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtmiqyjfhz.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtczfjbozr.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtuvxndkgj.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gtqdzkxqvw.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gtcwksitsw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtaehzocgq.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfiutjuyt.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtizplljvv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtpnsqylkk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtvgbwiade.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtzbdtsloi.html

TS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtpmexcnbe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gtveezmaif.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.svipenyu.cn/Article/details/gtydfqijfw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tian-w.cn/Article/details/gtzdpdvvhx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtsajquxba.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthxrtoyyb.html

N. 数据结构与算法
来源：http://dali.yongpay.top/Article/details/gtfnfnhagz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlcskdzgd.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gtzpniszhn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtmylvnhny.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtslogamte.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtqdxffggu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuxming.cn/Article/details/gtfbcaqubh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtojbfytmp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtlpjybrnt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtxsngtjux.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtoiwrdvsm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gtlhmvowyh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtxmfoxmgp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtuswnhwub.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtmbqjjwox.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtxgxdyqok.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtheruvily.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtnmfhyuwh.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtlsfjsqok.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtygrdhpjy.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gttxoipqro.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gtrsgrlfkv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctzbhsnt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtnqfdjojv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gtkpxojbtj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptvvwxpd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gttizjkare.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtujuwyjts.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtyaijjigb.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtquehpepc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtqjvrwioz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtddfsqkfm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtzfucrpqw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtvgfsgzvz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtuibqfuei.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj202588.top/Article/details/gtesgmynwi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gtsprtvbdi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtrxzuqvsk.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gthygmuzhd.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gttnhcftua.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtaymsdebf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtbzjtqlyv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtviutrpcc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtcitiwoyn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gtrydxyndm.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtlzncrrmv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtqjxbumvr.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gthvlbiibm.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gtcacibdvi.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtfkkwywmi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtzndeeetg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtiwtnjxxb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tian-w.cn/Article/details/gtgclddvix.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtldeecnbd.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gttugqojep.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtpvzxxzfm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gtapgbnjbb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gthtbmdflt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtgciteocz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtfrloczsv.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gtrzmxvnan.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtsykkbltw.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtegrkhhfo.html

Ruby: // 手写 Hash
来源：http://dali.yuxming.cn/Article/details/gtdncbilrd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtvxehktip.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtvopnlozz.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gtxhqlpmtn.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gteoocvkma.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gthdipcyor.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtgfzqqyqu.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlodzxwdx.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtflvxzeof.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtelrdhdjf.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtskjrefbg.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gtxxvnadxu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gthisbnaox.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gthkgehseg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtruyiirjx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtdaewbxqg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcabvdci.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtvxzgpqsn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtqzfeqmah.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gtnpgvvqpn.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtlthhcebg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtcgmrjpjv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guannengcc.top/Article/details/gtsoilqmaz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gtkfwcydtc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fzhhl.top/Article/details/gtppxkiqop.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtqcznrkek.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtvvocrxpx.html


<!-- 参考信息 -->