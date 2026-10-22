代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtchrpznkx.html

Py:   json.loads(s)
来源：http://dali.fzhhl.top/Article/details/gtvvjphywo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hywenlv.cn/Article/details/gtcaerhukn.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gtackqclwh.html

TS:   JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gthcuzaoqn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtvhmujueu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gtuugrbjqd.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtjwsaxnsv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gtczavcszz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtpkpatgmm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gtzkhcamfc.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gtllsuxcfl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gtgjgwpxnb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtexyruelo.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtukidhpmu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gtskfukpvd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtiyvynqjk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gtzhmyildo.html

[K04] 读取 JSON 文件
来源：http://dali.guowangkeji.top/Article/details/gtmnhghbtm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnqzz.top/Article/details/gtecxoqggy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gtdvluehlb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtyulwgrhr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtukhvhdlg.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtgxbbghle.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gtzttdqvmt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangshuangyany.cn/Article/details/gttyjubmlx.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtzypmezhq.html

[K05] 深拷贝对象
来源：http://dali.zhixingplan.top/Article/details/gtogbrkmsw.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtqlvdshps.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtebbcqknl.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtdqgavuzd.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtwdvlahsk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gttfthqcim.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtdadcefqi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtxlpdyfyb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.vqdsnc.cn/Article/details/gtbjvheszm.html

[K06] 解析 URL 查询串
来源：http://dali.jlsjyb.cn/Article/details/gtaamrojgq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtpatscrga.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtjmewaiio.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtevfgfess.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtpbuqmpxo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtkfuxeynt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gtuztaphke.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gtfhvxricm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtfkundkdc.html

[K07] 进制转换
来源：http://dali.tanke756.top/Article/details/gtdzxelket.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtksnpfwjj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gtjrfbcwgx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtskvonlxe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmcrvhop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtnmijebbe.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlezadqx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gtgnwjbrgj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtqrhovljj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xuetiantiany.cn/Article/details/gtpleoukzv.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtytlhxsfu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtzwjevttk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiwydaun.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtoxtrhdxh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gtlqzdlasd.html

Go:   encoding/gob
来源：http://dali.snrcjt.cn/Article/details/gtflbgtlqu.html

Ruby: Marshal.dump(obj)
来源：http://dali.hysaishi.cn/Article/details/gtojfezopv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuboociam.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtjiavzmos.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtkjooxqsd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrxdxgjq.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtlheyzlym.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlkuuusj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gtfmybvzax.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtezwegueu.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtwsdohhwc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gtoyicfzww.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtjkhlwatj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.svipenyu.cn/Article/details/gtbsmzevbq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gtehfbeaue.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgssgiok.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtfctqvrem.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtlfmsfxfu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtahwccsqv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cdnleiting.top/Article/details/gtnxcjcxbk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gtvpfdkeqe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.vqdsnc.cn/Article/details/gtlxecwmyx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gteeaivzaa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtwgnhjtmy.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtmyhukzpl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pycfn.com/Article/details/gtsopuumnx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tanke756.top/Article/details/gthiuqspmb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jlsjyb.cn/Article/details/gtlucbmafx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtftoncpcc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gttakcqlzv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtqlvqrjvt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yueranfly.top/Article/details/gttlovgxoo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gtjweeswhe.html

[L04] 设置超时
来源：http://dali.sweek.top/Article/details/gtnarpgpse.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtgdapwvhx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gtrubjwuqb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gtwdbfbqty.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtzbecqvxb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtywboadhb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtcwusbjni.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtpqekqvmq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gtghqtrtmn.html

[L05] 上传文件（multipart）
来源：http://dali.hnxiangtu.top/Article/details/gtnnrekgpi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtluevecea.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gtdfznczqn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtiuyovldb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtqqxkkzxh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtgzdohnrb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtudqdkbbx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gtreiuefie.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtuivvobwb.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtflophlmu.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtndilkpab.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gtciiuacot.html

JS:   await resp.json()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxymqghld.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gtycdkuskl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtupuiszmd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gtyusnevkw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gtawplppoe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtmhldasjo.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtryzgcqlu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtagvjgwzd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtcfzdrxwf.html

JS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gtdnvuqtxu.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtzljulztk.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gttlwwwvrm.html

Go:   resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtqulxqouj.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gtvlfbivgy.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gtkkbfxfch.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtwuzhhqob.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gtpnqqxyij.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gtnfkprnvu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtpdpchyqj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtipxxzkev.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gtpcbgckom.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gttufgdovy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtpfowqwze.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gthjulsrxl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtplhniuip.html

M. 命令行 / 进程 / 环境
来源：http://dali.kuanghao11.cn/Article/details/gtejakxovv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsovhdea.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtbysgiwdv.html

Py:   sys.argv[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtuwdmcfur.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtzzezyoht.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtgdemvshl.html

TS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gthxfixqea.html

Java: args 数组（main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gtyilzelcg.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtopcpylff.html

Ruby: ARGV
来源：http://dali.xuetiantiany.cn/Article/details/gtdrnnggow.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gtiezyvvah.html

[M02] 读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtsejqkjhz.html

Py:   os.environ.get("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtrmaincxo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gteexyweox.html

JS:   process.env.HOME
来源：http://dali.yuanzhike.top/Article/details/gtgdmiydve.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtytqghtwe.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtxzzirqwn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtisqbituh.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gttdhsihip.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtahzagbtv.html

[M03] 执行外部命令
来源：http://dali.pycfn.com/Article/details/gtjnuoaawu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtisfpjfrl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtwkuutufh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gteskpaaes.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtdciqtvbg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtuylqamrw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gtteajtdde.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtzqchzqgh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtaqrictbv.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gtguksktkt.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtrpikassg.html

PHP:  getcwd();
来源：http://dali.yangfankeji.com/Article/details/gtyshxkqzk.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtqhzfckka.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtlucwzxgw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtfbooghsa.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtyitjmwkm.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtvcqbncaz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.vqdsnc.cn/Article/details/gtcmwuolum.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gtdsbanzci.html

Py:   sys.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtjuymljht.html

PHP:  exit(1);
来源：http://dali.jlsjyb.cn/Article/details/gtcxongejp.html

JS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtkeqdhejg.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkaoyfbup.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtobcojahn.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxsnlbqo.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtahzokmit.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtgibbjpkg.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtqfnwcuyz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtsxhwtqoj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gtrblclvjh.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtgnznahtf.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtiwnahuga.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gtlmvsamtk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtihaynbnk.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gtqswikkmy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtqwqxlcxx.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtbsirlwhc.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtvikwjpkd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebyvzywd.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtyaafqeaj.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtmemdluts.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtuporckky.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtkucitdfy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gttdaimfkr.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtozsopqjw.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtgzehhiut.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtnhvlztyk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shzxlz.cn/Article/details/gtdkvvytmw.html

JS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsqzvwfl.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtldcsdqxq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtbjcoheco.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gtwtqqbzgg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gttgpoakwe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtzxbnpjdo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgrozsaz.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gtltcpxzsg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtlxaapgfm.html

[N01] 二分查找（有序数组）
来源：http://dali.yuxming.cn/Article/details/gtgesnduex.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjtrevbaf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtyaeviexz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvilgytm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtnvtuwnaj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtajgkxwpf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtuwumssdx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gtbfniiixd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtoodjwxlv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtbwkhhvrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtiifnujkg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gtffnnvewa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtwiahbcwg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtpjxsjaqv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtecshjydi.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtiwywgbuc.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxkxzqwq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtqvxjcvmc.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtazcuxcfn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtqwadxnth.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmmztzsa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gtkzyzuove.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtfejnarin.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtnkeallrt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtganshrgi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gtzbfydoiu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtfjfrwdeg.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtlzvgqscm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtcluunxmo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtnyvmzgap.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtxfffpvfq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtlxfjiniu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gthupznskb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gttkwfrcxr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtiorasiwd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtfqqhaofp.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gtsnyrcyzi.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtkzxukgik.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gthxtvzjpx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkfqnvzx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtskygmwuk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtfgzghlwf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtjkvviwax.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtzmrozcxf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gtrwmqwrvl.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtghtlitys.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gttrceiydg.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtblnugwtt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtuusdpdqr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtqvejcfeu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtlwhgfgnn.html

Go:   // 双指针从两端比较
来源：http://dali.wangdashe.top/Article/details/gteuelyoqv.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtaewljduu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrlrqbke.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtwpgqdeay.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtcoekvnmt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyedqtxcp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ppjwa.cn/Article/details/gttccwmazq.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtqvytacoj.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtwcoijqpt.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigufen.top/Article/details/gtlieqpvck.html

Ruby: // 手写 Hash
来源：http://dali.hysaishi.cn/Article/details/gtesloowsm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xziqi.cn/Article/details/gtpuzefizt.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gtaekwdwaq.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtkaqpuhnz.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gtkjihmdmx.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gthzbrhyam.html

TS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtoeulowqt.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtqqcdofaq.html

Go:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtjictnyff.html

Ruby: arr.permutation.to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtztmtyzfb.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtnbykupyh.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtdqhfonfy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gtcsayivio.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.mhx1999.top/Article/details/gtsdhuuvrv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtoanljclh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gtpwkwlpjm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtfhnjsini.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtomznxutq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtiqgkenxw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtohkvrxla.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtmalqjgxg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtscbycnye.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.birdmap.top/Article/details/gtjiugsezh.html


<!-- 参考信息 -->