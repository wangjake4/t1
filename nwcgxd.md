代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gttmyrnwna.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ehwqpu.com/Article/details/gtlbbjxyzz.html

JS:   JSON.stringify(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtfspjsenn.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtqigdayxh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.tianlin.xyz/Article/details/gtnyhczxyp.html

Go:   json.Marshal(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuknviai.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gthbliqdty.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.redwolf501.top/Article/details/gtnpiusmui.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gtoudpbpet.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gtaasbxbit.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dianchejie.cn/Article/details/gtrsacpsmd.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzlzkpaau.html

TS:   JSON.parse(s)
来源：http://dali.nwbrower.top/Article/details/gtpgozoshd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtbkpxsomv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtffjmorrx.html

Ruby: JSON.parse(s)
来源：http://dali.jyoumei.cn/Article/details/gtzlesxltz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.pycfn.com/Article/details/gtqurmhitb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gtibbwydxx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gtwfzlqmcb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jianghu66.top/Article/details/gtuadnpuob.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtyawaknev.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtugibbdfl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtsnmhrdib.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gttaxfkibx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenlongwang.top/Article/details/gtcixgvtgc.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtoqscewwi.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtnbzgruev.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yanxiufei.cn/Article/details/gtixdxkdwa.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttqsralsu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtbwjhvzpk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gtebaupacu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtztmfbbro.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj202588.top/Article/details/gtangieyjk.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtiyxhgxom.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtsldrechn.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gthbcisgcz.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtqxumccqd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenzaomai.com/Article/details/gtxngvherf.html

JS:   structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtirrqosbr.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtffzvraih.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmdybgwh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gtxwpenphk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gtrlupjlna.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhijiandao.cn/Article/details/gtplmvfutt.html

[K06] 解析 URL 查询串
来源：http://dali.redwolf501.top/Article/details/gteiyuinzo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtgtgbqvuo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtebmoaddd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gtltqzxpvz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jlsjyb.cn/Article/details/gtvhnkwsju.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtzmmnqucf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtqqvoddzl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtivblnxgt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtvsrnzild.html

[K07] 进制转换
来源：http://dali.ydzc1.top/Article/details/gtmvtprdwm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtyxditzlz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gtyjoznnja.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtwndykmlh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtercehjxw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtskddqjnw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shangyingyoupin.top/Article/details/gtqdjihoba.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zycfv.cn/Article/details/gtjpzdsrmy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqauvlnw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gzhubu.top/Article/details/gtqyoaafaf.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtjyavbdgs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtxiyzexvn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gtlszscmls.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqurlcbjs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtgsghdjyf.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtyojvdvuw.html

Ruby: Marshal.dump(obj)
来源：http://dali.tanke756.top/Article/details/gtthxqnchh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.sweek.top/Article/details/gtbuhpxfoz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpbhhonfl.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtmthguaaf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywujlkiv.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtaepomysc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnxiangtu.top/Article/details/gtyydbwbxz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtkfywcdzd.html

JS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrrqdhpa.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtpcmdlmps.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtnkjemybw.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhongyouzk.top/Article/details/gthvfzsrxd.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtzuuqgzfd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexvrfdev.html

[L02] 发送 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtzhfxvlwx.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtftwkygvm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gtfnvcztce.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gtvebrzgef.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gthhmcwuba.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtctranlqv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gttzrssjon.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtpsoeqhth.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cheryme.top/Article/details/gtcncyrqen.html

[L03] 设置自定义请求头
来源：http://dali.nanxinkj.top/Article/details/gtqcbxoetn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgfzy.top/Article/details/gthezvjoch.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqnhfezn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtyuzywkla.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtmuytdnth.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zycfv.cn/Article/details/gtwholpfms.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtkbqrfcmk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gttugjkbvr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.tian-w.cn/Article/details/gtvvecpvxa.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gtywojrtoa.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtgwwwsjbf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hammf.cn/Article/details/gtpswswaae.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtpdtqurhg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gtnlhaemxq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.redwolf501.top/Article/details/gtvcizuuiu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtkgsqtyxj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtyhxmyrvw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtegzvgkxr.html

[L05] 上传文件（multipart）
来源：http://dali.ppjwa.cn/Article/details/gtgfzhalbf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shuidangran.top/Article/details/gtuaamvdnt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gtiqahitdr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtpthndvjd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtfnfjlato.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gtplmxecdv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtehymeqcu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gtqldtglot.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gtykrppaup.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtsccsehlm.html

Py:   resp.json()
来源：http://dali.chenlongwang.top/Article/details/gtdtkbzeqr.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gtozqnjale.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtyonfdaqr.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtxwqwwcvq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtyabvkewe.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gtfzeqslmj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cheryme.top/Article/details/gtdjfqwjnq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gtisbtveth.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtqatschiw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daria6918.cn/Article/details/gttrfiofao.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gtsnjzskuu.html

JS:   resp.ok;  resp.status
来源：http://dali.kuanghao11.cn/Article/details/gtqsygebop.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtrwqahabi.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtzctrtwkg.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtpkiyxmqc.html

Ruby: resp.code.to_i
来源：http://dali.svipenyu.cn/Article/details/gtdhijbkor.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtpmezzzrc.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gtrxelxesj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtdcfvgvxx.html

PHP:  curl_multi_init() 系列
来源：http://dali.yuanzhike.top/Article/details/gtjoytvzev.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtaofxeeur.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtkhdbpeue.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daria6918.cn/Article/details/gtduwxiqwy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gtdagzlvhi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtbampkgmc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtdklxkopf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtqojkmqeu.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtdnaolsix.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtztbqkpck.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gtapzfoqsf.html

Py:   sys.argv[1:]
来源：http://dali.birdmap.top/Article/details/gthdesbkyt.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtaljcfsru.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtbrzqxwue.html

TS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gtjyfmbiwt.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gthdsalpjo.html

Go:   os.Args[1:]
来源：http://dali.zhixingplan.top/Article/details/gtdqsvyhgx.html

Ruby: ARGV
来源：http://dali.sxryk.cn/Article/details/gtzdbqqusj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtuiqzmkcp.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtwkhunids.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gticnuaqpz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtlzzioyxd.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtsvgczldd.html

TS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtnpygqixf.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtgszigkdk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkvnwfoc.html

Ruby: ENV["HOME"]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmtnntdc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgqjahzi.html

[M03] 执行外部命令
来源：http://dali.snrcjt.cn/Article/details/gtxgnnmeaz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gtzgqcbqbw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtcbfflmwn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtnskpryhg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gtcewpabtc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtqpdbgszi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gtqljgjyxi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gtupyxevmg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtguwyxqiw.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtjzfjxumy.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtvcrjprwr.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtrcchsepg.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczdfgabo.html

TS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtgewfkybb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.mhx1999.top/Article/details/gtrebgwquu.html

Go:   os.Getwd()
来源：http://dali.birdmap.top/Article/details/gtvahbukzr.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphrisjjd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gtjofrnzpt.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtfpgdrzld.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtgvizcjtl.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtihatnivq.html

JS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtqggzzvdo.html

TS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtzognuhet.html

Java: System.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtqlvfqwkl.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtbtlpsplq.html

Ruby: exit 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gttalxaxvh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258888.top/Article/details/gtufrrzaxl.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtvozfyosc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuzvqdyw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtsyimkpoz.html

JS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtqygtgiem.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkghaigw.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtjasemdyd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gttzfemooh.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtgwylzwvp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ivvv.top/Article/details/gtakopdpnl.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gtcwbuhljp.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtoichjqem.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljulpzvy.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtkxrzlryr.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtweonkscv.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtqbhioeul.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtsurhwwth.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gtoispcwgq.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtcarextro.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuyonfji.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xylfe.cn/Article/details/gtraevzqnn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtkszmyceh.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gtwwsljhga.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtnecopmye.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gtdegvdbix.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtyitsiaxe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gttzzoasqk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtmsczlodv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gthtlgqjcs.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtkgbpjmms.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtajhjywch.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtmaumonpo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtegvqbpif.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtwowapimo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtprlpzhcd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtmgutmnvb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gttsidyozg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtmupsyxtl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtiaczerzv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthfnggalb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtequwufns.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtcrxhezba.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtysmfehlm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gthjvlbpdf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gteyqoljkh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtjfjqzhlc.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtsaidbazx.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtnlhusszx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtoomedojl.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuegyjhfm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gttlpaadnk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gtsqhvgwkz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtblmsmmhz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtshhwubrk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtlcuvzotp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gaohongyu789.top/Article/details/gtdikzvvrw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtrxxbhida.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yueranfly.top/Article/details/gtxmjiapxz.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtdisobtgw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtyrhahsic.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtomfgxgks.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtwbqowyql.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gthccdyosl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtwgupcujr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtmujtkfyx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gttsqoplpv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtpdycstqw.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtcxrsossa.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjmknsoi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtrmbyrvzy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sufxvd.cn/Article/details/gteftzdxxi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtmoujcupq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtxuicawnk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtacntkrkx.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtgwzeyyvm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtzelkbppv.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtempegmgj.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfhsqoaw.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtlgxawdot.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtfgdrspxy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtialovcnr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtkfadbvms.html

Go:   // 双指针从两端比较
来源：http://dali.andypj.xyz/Article/details/gtjgzonjkc.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtvnuzlnub.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtjffuchlv.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtfbaqsnbc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gteuwjlcck.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtgcwtgieq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtzgyxtemr.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtszgibpxk.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtunlrvuvy.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gtqmblcdcb.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gtkjoxjkuv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gteudyznlv.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtcdztgtzg.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtzafdtako.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gtoiwwvkty.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtnvswwbko.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtenxtrslm.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtuvyibtbg.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtoshefdhp.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtasqwqyof.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtvemmzuxn.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtsssrruur.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gtdmkxojsu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtatkugbsr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtnntjvdbf.html


<!-- 参考信息 -->