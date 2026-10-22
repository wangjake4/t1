代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtsmsvmnwd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtntuktmnu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtgzbrlqci.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtdufsohzm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daria6918.cn/Article/details/gtdetmnrnn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.svipenyu.cn/Article/details/gtlnqiwzkd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtsrlhqwrq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtjvgfwrml.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtadixdhmo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ydzc1.top/Article/details/gtnukiizcw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtjcmbwfhq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.feifeiyinyue.top/Article/details/gteyzvuihw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtcnxcbxue.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sysykeji.top/Article/details/gtmrqdnnkf.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtuqsttzxt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sweek.top/Article/details/gtvjgjngjc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shzxlz.cn/Article/details/gtnnpjljpb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtojovxkem.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtvznotucw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gtxesqqogn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuknanetr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.feifeiyinyue.top/Article/details/gtzevsmreg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtovzuifrg.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gtgcnrdwtx.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfrogzgg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jlsjyb.cn/Article/details/gtwhpzhwvd.html

JS:   structuredClone(obj)
来源：http://dali.hfpthk.cn/Article/details/gtuoomckgb.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtbkyhcisf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gthcfqzvfo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jiagoushi.top/Article/details/gtjcvhqbfl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtcllquyqs.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.pengpengdd.cyou/Article/details/gtebdjjztk.html

[K06] 解析 URL 查询串
来源：http://dali.chenjidiqi.icu/Article/details/gtyiptzzex.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtwimlbodq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hammf.cn/Article/details/gthuldkeex.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gthowtjcqi.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtvabvzqfl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtrmckwbap.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.havefunace.top/Article/details/gtxwmssenj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtacnivxvo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuanzhike.top/Article/details/gtllcpcame.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gttljnovob.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtecjthldf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gthqliiweu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtsyyfxqli.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtknchvclf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gttzsgndgc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.andypj.xyz/Article/details/gthtjyvgmk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtnyegsefb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtvvveljgu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gtbaqhqkof.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtzfcdmefr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sufxvd.cn/Article/details/gtigfljogo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtretjzany.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jlsjyb.cn/Article/details/gtirmbbfmb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtnaagdyqs.html

Go:   encoding/gob
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkiczbay.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gtjvhlcdfh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtfkegqhww.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsuwknxfl.html

L. 网络请求
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdpzkwzf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtykwhmwtv.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtpbfqeush.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xinyue.icu/Article/details/gtqvodwjzb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gtvqfszltc.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtfnhjduyi.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtxzunvjkb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gtyzkthffl.html

Go:   resp, err := http.Get(url)
来源：http://dali.xylfe.cn/Article/details/gtlqazoyty.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gtmiuzkxwa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtvsvxhtek.html

[L02] 发送 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtqemldbrn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gthwqdniet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dianchejie.cn/Article/details/gtecuepudq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtrzrwqbgs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gtoghnggbb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenjidiqi.icu/Article/details/gthzqxhgdo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtoftbnawc.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtfadoufwr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtupogdegv.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtookbnvki.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gttumnqios.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtxijgvzew.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gthpnsvtzv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtdswmbjex.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jlsjyb.cn/Article/details/gtvpvbmdpb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtskeimvyf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xinyue.icu/Article/details/gtasnnwtdo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtmmefrucb.html

[L04] 设置超时
来源：http://dali.quarkkingdee.top/Article/details/gtyvkfappy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.pengpengdd.cyou/Article/details/gtpqepifji.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gtlcpkvvby.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtldrzalyr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.fzhhl.top/Article/details/gtciyuffun.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtapqqwacq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guowangkeji.top/Article/details/gtyltddshu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtwfwkfjgu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtzaqfjpxa.html

[L05] 上传文件（multipart）
来源：http://dali.chenjidiqi.icu/Article/details/gtrvnqtuji.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzcsqtwy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gtcmkrsemu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtvkidhggv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gthfuzvjrm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtjkafxovl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gtjkdielwf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtzpuxitbr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gtneymxisn.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtvgcxaaoz.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtptqutfxa.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtiuzrqcvs.html

JS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtnhhydqed.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtnphsftaf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gthptktvwp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtsqmwkuzg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.0kj1m.cn/Article/details/gtekgszqhy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtltmdsgmf.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtzkgtiojz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtvklisarc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jianghu66.top/Article/details/gtrzjaermu.html

JS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtqlemoiwv.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtpcwvrzhc.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gttjydibrl.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtorycbsii.html

Ruby: resp.code.to_i
来源：http://dali.jyoumei.cn/Article/details/gtnwfygtxx.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gtyawzhjzi.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtlojhzthf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gtstuzshzb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdufewsu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gtummehuud.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtawlzkcce.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtsxizdpyb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtzqbmbwbp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtmhahatrz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtcmnauxoo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfeeismue.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtxsfrcvzt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtryyhimrt.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtcreyyabc.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gthkkxkpja.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtyorozfuq.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtukaglvsk.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtlkzsgmhd.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzydfkimu.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gtaptfwzje.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gttfsmawnt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangdashe.top/Article/details/gtktzwazst.html

[M02] 读取环境变量
来源：http://dali.sweek.top/Article/details/gtnziftsdk.html

Py:   os.environ.get("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtyqnnggbd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtkvsejatc.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtsphroepf.html

TS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtewtnanvi.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gtjlwpxzks.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtipjxrstm.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gtdvasbgkc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gttuzrnzua.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtqxmhlclt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtjgdtzcue.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gtygnkcisy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtxknywmiq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtvwfbxvgf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.fengsongda.top/Article/details/gtesguskmk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gtrofrxcoq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtkklwjffs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gtixnfmmpr.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gttknyyohs.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtninimhki.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gthcnxhcoq.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gtnpepjddt.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtkbceofyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gtpraubsyp.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtzjdrmesz.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtdmujsviv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hywenlv.cn/Article/details/gtaesbqdzy.html

[M05] 设置退出码
来源：http://dali.feifeiyinyue.top/Article/details/gtxktxarwg.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gtwkcbnymh.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtbbabvlwe.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtxisyawij.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdfbuvok.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtyoastame.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtrehleqjz.html

Ruby: exit 1
来源：http://dali.hongshengwenyu.top/Article/details/gtzdrtmqoe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigufen.top/Article/details/gtgzowhltw.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtgudpekyz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtufeqrkmf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtosydsvws.html

JS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtjxgjhiei.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtoqgkwelk.html

Java: System.err.println("err")
来源：http://dali.zhongyouzk.top/Article/details/gtiizjhtgg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtoicpkyad.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gtamzfhjwc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtnfhrkrxv.html

[M07] 判断是否为主入口
来源：http://dali.tian-w.cn/Article/details/gtwkdlbbjs.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtawvmdksg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtcwxpaqee.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtkwieqvar.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtxcuuwowt.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gtjwoemhll.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gtgazlqyiv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.dashuyun.cn/Article/details/gtaienwper.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtfcekhwcm.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gtjjwuoyhf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gtxiufmtit.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtcwpxtkks.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlbghdyg.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtzowebuhg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtashivflt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtdwlyflvx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtcihunjxq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtrkzbjuri.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmuoitavw.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtgphzekkv.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtyphapioh.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtiruvewgf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtmxzdmtvy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gtuinbaved.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtxhfzuisd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtibbelscj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkymtbzs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtealcojmf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtfozygabg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtavjhajob.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gthicuicoh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtyyznywpq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtnmzxjfex.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjxswbhxw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtsbczftsy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gthsdrmijw.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteylluxcb.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhizasln.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtbgfvhwlo.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gtiwmfuvyn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtxumqrkkm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gthvxljzlp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtjcaiucqu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtrsguvwfo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtbqgbtwgf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtimkhjzfa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtumohidrf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jiagoushi.top/Article/details/gtguheqmta.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtiawznkwl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gtsmvzhfqi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmcsjnnzy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtowjgjtyk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtpstztlee.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtwyoqvaze.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gttoyjfbqw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtfbovttlu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtqtlmwqxa.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtorpyqhai.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtnkxbxkkd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tanke756.top/Article/details/gtrmmelvnk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtnboniptu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtbbvbrqlz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtokrsrhjk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtrjsoftcz.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtjreucvvp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtkyusukjr.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gthlkonfjj.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtnjysivwc.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtqvlytfth.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtzqtrspnm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtnnvmphse.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtiszlsopc.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gtwpnrkrid.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtjjmaoren.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jlsjyb.cn/Article/details/gtpltqspyi.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtrxcmdhvd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtlvfgapge.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtdbmsjlfb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtctslzyvc.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtxoozybxf.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gtguzkboqg.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtggruxbcr.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtptzhveur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtpszsunst.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gtixojjryi.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gthmqupyrv.html

PHP:  // 手写递归交换
来源：http://dali.ybcxt.top/Article/details/gtnywgbzil.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtrdpmddnt.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtejzylwlz.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtmikgcvpc.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtlrasqjvz.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtwqczqqxv.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtnotddvcp.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtknhseypu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtcsnygnex.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtevikxzqf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yonumen.top/Article/details/gtjcosetot.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtytkdvtcq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gtbdiktpqn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gtcyukhacg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtxnsfcexf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gthxhxwljo.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gthfwjlvpu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpszaiaj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtrcfpnrhs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvwjkjpa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtjtfjmgpd.html

Java: class Node { int v; Node next; }
来源：http://dali.tanke756.top/Article/details/gtvlhiehhy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtqxwhsrkq.html


<!-- 参考信息 -->