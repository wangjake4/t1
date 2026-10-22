代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.cheryme.top/Article/details/gt2qnumkfqz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2dlxghsij.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2qcirocwy.html

Ruby: JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2xmzzkyfz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.havefunace.top/Article/details/gt2arkycvwi.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuanzx.com/Article/details/gt2jxceakzj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gt2ebuzpilg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuanzx.com/Article/details/gt2pblsaugj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gt2vhyonqdd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gt2kyropinb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2hqihnhmr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xziqi.cn/Article/details/gt2xovmyhgo.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.daria6918.cn/Article/details/gt2rxbyaqlb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrvhsdqc.html

[K04] 读取 JSON 文件
来源：http://dali.yonumen.top/Article/details/gt2nroyfazh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.pycfn.com/Article/details/gt2kkynfxzq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hywenlv.cn/Article/details/gt2zgchdrwi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.316326.xyz/Article/details/gt2nbgixina.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2ayjqrhkn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gt2tcxmktym.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gt2hxujwclr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2aprtcznu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2lwrxwhwu.html

[K05] 深拷贝对象
来源：http://dali.mhx1999.top/Article/details/gt2nfffsspr.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2rggeapjo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gt2ptohrhwv.html

JS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2lmunccub.html

TS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2bdljgwvm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gt2ipcpbhev.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.0kj1m.cn/Article/details/gt2nitrcwgo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gt2qhkfwzer.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2nauxrwrh.html

[K06] 解析 URL 查询串
来源：http://dali.0kj1m.cn/Article/details/gt2urvryozt.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2ghqsjeej.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.snrcjt.cn/Article/details/gt2rbelaaik.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.iojbl.cn/Article/details/gt2smnkyvjw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gt2lbjujqsy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gt2corizsac.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gt2vjhbcgch.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gt2ymijntfg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gt2lfqrfgvi.html

[K07] 进制转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jrizxpcu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2shjwmxst.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zeiyuhgg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2uzotifbt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2lknexder.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2izcsjxyw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnztnjkt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2ugqsqthv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2jjaxbcek.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gt2mdfvgcok.html

Py:   pickle.dumps(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lylodzwh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yuxming.cn/Article/details/gt2zvypyyvv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2fesxlycl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2lumdekyv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gt2inetiyhw.html

Go:   encoding/gob
来源：http://dali.xinyue.icu/Article/details/gt2qpoyouyk.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gt2aokhkpou.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gt2vcgzwpak.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2xdbxatee.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gt2gnlmgikm.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vozxqymy.html

[L01] 发送 GET 请求
来源：http://dali.guannengcc.top/Article/details/gt2rqomccoy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odywhubs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gt2irbcazld.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gt2ybseguvr.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2bldkjnbk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gt2ifgsgrhq.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2vcvnuvgh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yuanzhike.top/Article/details/gt2hikvmpky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.9152youxi.cn/Article/details/gt2dwgptlwd.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gt2pvhohxxk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzxccuyq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkntvajy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2kdqdafuw.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gt2lsaiagfn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2ixbkrfvs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2wbkbuxdf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gt2lnniiiws.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2miehwdid.html

[L03] 设置自定义请求头
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfcucjnd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yueranfly.top/Article/details/gt2zhkcruvz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sysykeji.top/Article/details/gt2kdbqxqfh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gt2djljzelo.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gt2amkvdywq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gt2wlctypcu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2tyqformn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gt2cesjdlgr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gt2jhcoausd.html

[L04] 设置超时
来源：http://dali.tanke756.top/Article/details/gt2fhcfjmgy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpfdgwgh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gt2npfilisi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2ocqmsgqf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqwtwduj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gt2dyokwruk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hufkkqzi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhoulong.xyz/Article/details/gt2zxddrchm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdmopveb.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gt2yxjcbidm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfkdsnnc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tian-w.cn/Article/details/gt2wsobmlyv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2hljjjtgh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2droubcan.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gt2gmsfihma.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2sgfpczih.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2tgajuehw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2vhtactrt.html

[L06] 解析响应为 JSON
来源：http://dali.xziqi.cn/Article/details/gt2mdtrcaaw.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gt2bzgkqtzp.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gt2jotzjxfd.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2wgiwlrfd.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2nsncrmrm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2oeqcxyec.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pawngiuh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2qyzahorg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gt2xatkonny.html

[L07] 处理 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gt2lqjukrot.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2gbydpyrg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lpiojhsd.html

JS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gt2hovsimuj.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2syrecbtp.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2kcrasqyn.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gt2nmnjpnfv.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gt2glqflyxi.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gt2palyaaoy.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gt2dmksogqx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gt2hwpphmvz.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2mdemfkwp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gt2tfodocuy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2oggfedew.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gt2sjomsvrc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gt2mzcekqji.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2dhowfipz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2chywojhn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2pjdzndrw.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2knkjmiyj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lozakxfn.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2akfvccvy.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gt2usxukgwe.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gt2iysvspdc.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2qbaabxuh.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gt2sqwxuoae.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2ogqckqui.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulohvdyr.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2sgbxprkr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gt2kkiutwdk.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2qznbxpnx.html

Py:   os.environ.get("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2peduwepm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2afnufwlc.html

JS:   process.env.HOME
来源：http://dali.jyoumei.cn/Article/details/gt2fbjbnekn.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2ufqclwtm.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2qtsyqwbv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2djdkxhca.html

Ruby: ENV["HOME"]
来源：http://dali.yangfankeji.com/Article/details/gt2qcsufozo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2heywvzfs.html

[M03] 执行外部命令
来源：http://dali.daria6918.cn/Article/details/gt2hazoslre.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.snrcjt.cn/Article/details/gt2wassadaa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2rqbkqsjq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2vhrglfas.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gt2iavpzywz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gt2huwvnpbu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.0kj1m.cn/Article/details/gt2gcxrgsra.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gt2gerssdrs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2fjectwyx.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gt2ubrimpaf.html

Py:   os.getcwd()
来源：http://dali.jinqigufen.top/Article/details/gt2pcexcsmj.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gt2lkkgeqmb.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gt2kzwbxkch.html

TS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gt2gatlyzgt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2ffhjcews.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gt2fupmawnm.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gt2fxswumfm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.svipenyu.cn/Article/details/gt2ekmedcri.html

[M05] 设置退出码
来源：http://dali.aizwys.cn/Article/details/gt2kijjnsbe.html

Py:   sys.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2miajmduz.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gt2rrislwfi.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2knwjlnrt.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2vtcivnwy.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2nqlbcext.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2sdaqxauz.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gt2svxofyhm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyuzaltw.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gt2yjzypyps.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gt2koyowpmk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2syidsuxt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyafndl.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2agaspckl.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gt2tlsvbstn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fzhhl.top/Article/details/gt2ongzbulo.html

Ruby: warn "err"
来源：http://dali.nanxinkj.top/Article/details/gt2pgjzaeaq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2nfpcaxea.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2rfmgbfoe.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gt2qbyvabsg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2zhaisrdp.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gt2vtfqzrmq.html

TS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2bdubljte.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gt2jimjnyjk.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gt2lltayqhr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymokudtg.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2odphoygl.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gt2sffrboqa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gt2hndyuywr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gt2fhtemmse.html

JS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gt2xsqfektw.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2hbrcrehd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2ttepyadx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gt2bkhhzlpj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jynxcatn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2tbzmjfqj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jlfggxnp.html

N. 数据结构与算法
来源：http://dali.jinqigfzy.top/Article/details/gt2kulrzzlg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2optlwhlt.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gt2jydoxmmy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2gocrebkk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gt2evyaozrz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gt2ovoqgzvf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2nnuwerka.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2ohofotez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2ggcdqmpb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gt2dxyvdgcj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2xoepjbxi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gt2oadhwkxo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qliwqoas.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2lbahhjvi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2kuzbhyja.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2xreppaaf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gt2dcqvavba.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpgoklsz.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2pvtjiece.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gt2ahjrnmhr.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gt2kvzxwrbh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gt2yajcojas.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gt2hcsukvvz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gt2njdwvatb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2kmauiwjl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2fnbazqlj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2oykxuutg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.meibo888.top/Article/details/gt2zfiuvggc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.dashuyun.cn/Article/details/gt2tefwbkaf.html

[N04] 斐波那契数列
来源：http://dali.mhx1999.top/Article/details/gt2epfmyhlp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2rmkdujnp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2mtwqxdug.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2syhaqcep.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2wplfgpyd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2jplldoxw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2fbfwfoyj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2ekfspqwf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2qbkbpqpe.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gt2sydpziis.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2vhlskrkf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnnbtuh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2yegckvog.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2avekjpzi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenzaomai.com/Article/details/gt2loioxnwa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gt2gqlqkdje.html

Ruby: a.gcd(b)
来源：http://dali.jinqigufen.top/Article/details/gt2gecbljmg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2wdyxgiho.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gt2vkxthmij.html

Py:   s == s[::-1]
来源：http://dali.yongpay.top/Article/details/gt2pygepzdz.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2wyjsbgig.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2porvukjl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyatdmt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gt2ggknuhxn.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2guhpwcbj.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2ompfecxm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqatopeg.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gt2lqhcspme.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gt2iojwjfjb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gt2fuxtrihe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xylfe.cn/Article/details/gt2opopupmp.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxinkj.top/Article/details/gt2oypgmrqt.html

Java: // 手写 HashMap
来源：http://dali.tanke756.top/Article/details/gt2fzekmwpa.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2mgekxxht.html

Ruby: // 手写 Hash
来源：http://dali.yonumen.top/Article/details/gt2lagdtvqh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gt2cuoqftfv.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gt2omocvhsk.html

Py:   itertools.permutations(arr)
来源：http://dali.316326.xyz/Article/details/gt2rrctpuzg.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gt2jjndzmzj.html

JS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2zfnsoujj.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2cwlgsedp.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2bywhoixj.html

Go:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2gihdvdzs.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gt2niyuikzx.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2xbuaanou.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2smobcvay.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2wxpncmcp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2mxaacsbu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2nqfoicnb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gt2lnykfxid.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gt2lxyfplyn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gt2voruaocs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aizwys.cn/Article/details/gt2ldycoiqs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2pntrtymf.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gt2iruhrsqc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guowangkeji.top/Article/details/gt2mkrdvbvc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tanke756.top/Article/details/gt2pwlyirdb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gt2cnzixgva.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gt2qflbvgyi.html

Java: class Node { int v; Node next; }
来源：http://dali.fzhhl.top/Article/details/gt2iiewqhzt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgxkjfrp.html


<!-- 参考信息 -->