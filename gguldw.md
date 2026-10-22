代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gtxhitqowg.html

Py:   json.loads(s)
来源：http://dali.gaohongyu789.top/Article/details/gthdfnkgak.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.hnxiangtu.top/Article/details/gtxpqckafx.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtippiiptn.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gteqxaujed.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtgontrkvm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtobtlvypp.html

Ruby: JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdadxtfiu.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gtfjoxseyf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtbaudeqzu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtiywtpuue.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtdzqbgqhk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtdrgtqzsr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.snrcjt.cn/Article/details/gtksytnwew.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gterwwxnla.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.c1oappe.top/Article/details/gticggrsir.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gtgdiinbel.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhiwuduotai.top/Article/details/gtozybqzje.html

[K04] 读取 JSON 文件
来源：http://dali.kuanghao11.cn/Article/details/gtegwnhbgu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gtadhysvky.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.sysykeji.top/Article/details/gtcudqvzvy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenjidiqi.icu/Article/details/gtuthfoxay.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtgqducggj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtuvuagpbo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gthafqloyc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwhtsrli.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtlivthqjd.html

[K05] 深拷贝对象
来源：http://dali.ydzc1.top/Article/details/gtxltpqipv.html

Py:   copy.deepcopy(obj)
来源：http://dali.havefunace.top/Article/details/gttuwhiofc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gtilhnpxsu.html

JS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtqyivieem.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gtdzrjfpka.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gaohongyu789.top/Article/details/gtetdfmcss.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtrddlrwlj.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenzaomai.com/Article/details/gtseexrzzk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.redwolf501.top/Article/details/gtveftxmvf.html

[K06] 解析 URL 查询串
来源：http://dali.cqqwz.cn/Article/details/gtzibnkdne.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gtdpxdbbxf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.kuanghao11.cn/Article/details/gtujkqrrcw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gtvyhjwprc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtllpnncqe.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenlongwang.top/Article/details/gtkcgjdmde.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gteqpgxzpl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gteboghyiy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gtgydsatsl.html

[K07] 进制转换
来源：http://dali.yj202588.top/Article/details/gtedqpciue.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtrohisqtl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jlsjyb.cn/Article/details/gtulsxpdbm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gtpmfaniff.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtvcnlzjkz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtlmgugcmr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.gaohongyu789.top/Article/details/gtpcbvdbds.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgupaplhs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttiyompbf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jinghuilouyu.cn/Article/details/gtncnowwac.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gtntzqolbk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.redwolf501.top/Article/details/gtnctezxpy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtvayrqpsk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoqfpigh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlwsxrwn.html

Go:   encoding/gob
来源：http://dali.nanxuanxn.top/Article/details/gtvrrhfdmf.html

Ruby: Marshal.dump(obj)
来源：http://dali.redwolf501.top/Article/details/gtfzrtmurc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtwzlnpcfv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtvvgymkzr.html

L. 网络请求
来源：http://dali.havefunace.top/Article/details/gtnevqlffn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtynqpwiwd.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gttveieezf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.iojbl.cn/Article/details/gtqxvtosba.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hysaishi.cn/Article/details/gtxdzyrpdr.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gteuohtaxl.html

TS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtnsbfyukz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtemtyfrqc.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gtcdvvlbqc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gttlfyveoo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtpyrehorz.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtujnuenul.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtashumdhd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtvbtuqaqf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtxjqizqcs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtwxwbhagi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtmphhcidy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtjgcshhuo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtwfhaozwq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtvbafufug.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtsmuxwlml.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangshuangyany.cn/Article/details/gthzvzgryp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtvozujpqa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtqchfwznp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtfyannjqq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xziqi.cn/Article/details/gtymmxvayt.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtkvzhxigo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtivdwozgp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtxzxuukyo.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtfvzhsjdm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtlnzhztes.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyfqjsqj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gttiilymob.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtzdyjgmty.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenzaomai.com/Article/details/gtjayiucdt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yonumen.top/Article/details/gtfmrxppce.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtzybikyug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtrphqpqtx.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtwjdqkilz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtcuxquvdj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gogol.net.cn/Article/details/gtqivasymf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtpdlusvyy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtskwqshrv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgufenzy.top/Article/details/gtbnsukwwa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxumnprx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigufen.top/Article/details/gtnrzstghr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gtwmappcsn.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gtzsfnzpcx.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtdzgdtxiw.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtpuurbadz.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtrarwilyu.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtgkpiyrrb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gttdzeltzh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xziqi.cn/Article/details/gtyvhfhkub.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yongpay.top/Article/details/gtbqqssvjz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtjcaahtkj.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtwcdljoqi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gtkctvyxwc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtzyqapobu.html

JS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gtdgohelag.html

TS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtxgdudaqz.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtlndrcmfi.html

Go:   resp.StatusCode
来源：http://dali.kuanghao11.cn/Article/details/gtknyfgfxz.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gtscfislwj.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtibgpkwkl.html

[L08] 并发请求多个地址
来源：http://dali.gotoacloud.top/Article/details/gtqnpuyhef.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtymhfyrlb.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gtmnhwabtp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtszxxfmrs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtjdvqeayz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gteyfscxfr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.snrcjt.cn/Article/details/gtcliwrcto.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jianghu66.top/Article/details/gtblleuzpb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtspxqupmg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzbkmlxmk.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtowaupsvm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtypsghjrv.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtswepmjoi.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtisrpkmhe.html

PHP:  $argv;  $argc;
来源：http://dali.guowangkeji.top/Article/details/gtzfvsciru.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtahtibfxu.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtrtpcjbye.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gtcyfxdcyd.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gtgfjdhnlm.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtmoobsfif.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gtrakxfldo.html

[M02] 读取环境变量
来源：http://dali.hfpthk.cn/Article/details/gtfushyxtx.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtwaepyluu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gthlvmnqtu.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtyvfyudoe.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtwevvshai.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtlablmyoh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtbkdcosnp.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtrkoycoen.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gtesputsmv.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtzzucunwg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtotbtpzxy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yueranfly.top/Article/details/gtuzsrrxwz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtwrnlnpbg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtaudzplpy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gttxrmwgeq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtubtlprwj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtdtproerg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gtgdxxeofn.html

[M04] 获取当前工作目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtttddyyop.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtztqrycpu.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjgsinia.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtaliuwvli.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtgfnbrujz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtaelmjtue.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtbygvyovl.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gtrukenpqb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtnxukdpdj.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gtqeedrlmo.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtkwrwhrvr.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gthzzfvriu.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxkroqpps.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyhbwlgfd.html

Java: System.exit(1)
来源：http://dali.sweek.top/Article/details/gtaulilxqq.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtufvzxvtp.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gtwgtmsqhe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtpxxhfdcw.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gtqsrfewkp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtihtkyklz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gtfmrrernx.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtaafsvhgi.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gtuzjeoqsu.html

Java: System.err.println("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtspounkxj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xuanzx.com/Article/details/gtwlyuegls.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gticdnzxsz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gtzkbwqumv.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtywwdipba.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gtetpawohp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtrminomnm.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtswadabzr.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gttrdtwxgv.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtyuvhezjr.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtltygficx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtldopxziq.html

C#:   static void Main(string[] args)
来源：http://dali.havefunace.top/Article/details/gttxigxvcy.html

[M08] 获取系统与运行时信息
来源：http://dali.kuanghao11.cn/Article/details/gterinzlrs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtkzwzfkgd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.vqdsnc.cn/Article/details/gthzpqkwbe.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvfzrgzt.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtojrdiplx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnxiangtu.top/Article/details/gthxocszuc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtznuyumir.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtnazwuwfk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtteehopsv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtydwjolda.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtgvxofpmw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpaaafbiw.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gttoitbdeq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gttsanarzl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gthbkszgnt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gthqfrbfoo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtcnqizkgh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtijmljq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtxnvznebh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gthbqditda.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtbghtzcyb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ydzc1.top/Article/details/gttrvbhirc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtxuuaqbco.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gtdojsekic.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtmfvkqude.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gttazwjsxr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwpnwbks.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtnblrrqit.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtoephyvlp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gtciutciii.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtwfklkhhv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gtodlzyvtk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gtfvuqitnp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtihfkyycl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtumkoiphq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtwjoqzwiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtzmsxxgjd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtewlareys.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gtmdqvlsyn.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtkjczdjax.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtcbknrejg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtwlcbkeem.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtvhntebly.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtxpwqxeoz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtazauycls.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gtlvuwnarc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtvnlyuedb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtvxhljfqt.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gttknyqbhi.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtimemnkvc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtjfbefwgm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtfhesciji.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvkbrcxhq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.316326.xyz/Article/details/gtzekgbnbq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuxming.cn/Article/details/gtzynfyvlt.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtcoruvlyx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtgzvuekmi.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gtgbndbsia.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gticmyxgwg.html

PHP:  $s === strrev($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtgmaogudv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtcqmmkgvk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthnndogrm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtptmaykga.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gtqjshijok.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtiltmaywp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtepymxrva.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtlxjxunna.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtptxmdzqp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtzxjdisye.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gthnwavcya.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gtbhrgjtzq.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtgpmvugvc.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtegdkikky.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gthoregnbi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gtddlanaav.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gtnigwvojx.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gtvmqlctdv.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtpufldipn.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtjxxrtabn.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtwklizlzv.html

Java: // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtmatwvfti.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtnzdavfcv.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtgomynsxc.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtdtbadxoi.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gteembodvd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gtoofwcyyf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtfahtmjzo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtzenobfmv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtxhmyuagn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtpxrzmbvq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gtuwdozkbb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtvdrmumhb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnprcdnk.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtmvauzwym.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gttuseqeys.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtafzllgwy.html


<!-- 参考信息 -->