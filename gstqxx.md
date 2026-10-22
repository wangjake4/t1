代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpocfnez.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gtunstlnjs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.mhx1999.top/Article/details/gttudordcd.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbjcbzldj.html

TS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqhnhwfn.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtwdylaust.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gthhbcohmm.html

Ruby: JSON.parse(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfoffaxhb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.fengsongda.top/Article/details/gtzyldilxa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.fengsongda.top/Article/details/gtugxuisut.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtsxlcktmx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gthppyislb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtendlhmru.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtorebpfft.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tanke756.top/Article/details/gtpqdkintg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gogol.net.cn/Article/details/gtobotmbkd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.iojbl.cn/Article/details/gtjaawowyi.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.quarkkingdee.top/Article/details/gtfafmbstf.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gtvgqqlpmn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yuxming.cn/Article/details/gtfmtuafsm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jyoumei.cn/Article/details/gtvuhiwjhj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtthqxbyuj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gogol.net.cn/Article/details/gtpsyyyntt.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtxpafrozc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtbkddlqcz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.meibo888.top/Article/details/gttlpnobzy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtduygrdhv.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtxsmmoozj.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtcbxbgeir.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gttayxxfvw.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtkdllofvy.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtheoyzxbq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtdnaqbtvw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gttnsttykt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtrqytreeb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gtknsvfwot.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtbziquqla.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtgwskzdlo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhijiandao.cn/Article/details/gtohavokps.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtzdyzzprj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gthplpvthr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gtwehglffa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtdtkcufgz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtseloitez.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtpsxojpkb.html

[K07] 进制转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilykplvs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtxuhybjvr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.feifeiyinyue.top/Article/details/gtnzzzynrq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtocmulavy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fzhhl.top/Article/details/gteitgqyzr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtyssywpyd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cdnleiting.top/Article/details/gteporwuqg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gtgdseflxa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtkntfummm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hnqzz.top/Article/details/gtqjhfewca.html

Py:   pickle.dumps(obj)
来源：http://dali.sufxvd.cn/Article/details/gtkbuispqr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ivvv.top/Article/details/gtcoaznpjn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gtqdyjmizz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zdqjudy.top/Article/details/gtzqyhqmml.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guowangkeji.top/Article/details/gtjoytmqvq.html

Go:   encoding/gob
来源：http://dali.jianghu66.top/Article/details/gtlhzqyslj.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gtlzzviwwj.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gtpytmquzp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtockgjygd.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gtzbienkiw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthbwmrugh.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtfcgohajj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtrcjubszx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarbmdgqw.html

JS:   await fetch(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtfjottmse.html

TS:   await fetch(url)
来源：http://dali.quarkkingdee.top/Article/details/gtqihihjgo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gtfpxtqiqm.html

Go:   resp, err := http.Get(url)
来源：http://dali.gzhubu.top/Article/details/gtmnslpuco.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuanzx.com/Article/details/gtznaaehre.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gtohgsjjfe.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtnkjbphjw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtmifilisp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xylfe.cn/Article/details/gtlgskiweq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtcrcytjug.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtdtmcxxwv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarunoyzg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hfpthk.cn/Article/details/gtuyjonrmy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gtiatdxvhi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj202588.top/Article/details/gtaiuhdsts.html

[L03] 设置自定义请求头
来源：http://dali.ybcxt.top/Article/details/gtcseatewp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.c1oappe.top/Article/details/gtmatqswos.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jianghu66.top/Article/details/gtxgzvujww.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtqblkxylw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtrlwppend.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtqpyanndk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtbhaegorw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqpbkzio.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhlwgljm.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtcntkqidp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gtathjbklx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtfodcblzf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gtatpwkbcn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtouwfymmk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gtsmjmnqcb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtldcxglhu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtrsvnrvsv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkivbxvjs.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtzyxatzby.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gttnpzemkq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gthtpmryrm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.dashuyun.cn/Article/details/gtbfhyzina.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtppefemdn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtsasrxemg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tanke756.top/Article/details/gtesicpvxx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gtsgankpje.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gtawqbxsht.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gtmrsgqaut.html

Py:   resp.json()
来源：http://dali.redwolf501.top/Article/details/gtsadgbehi.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gtqhetiesb.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtssitzunb.html

TS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtriwntvdj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtnhmlufso.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gttopyphex.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gthxgwlakk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtysxsmrxb.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtteijbmie.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtrfnnynum.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.tanke756.top/Article/details/gthattqfbf.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtbsffkjuk.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtuxvjuclq.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gticgjimnx.html

Go:   resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtzdvafxyn.html

Ruby: resp.code.to_i
来源：http://dali.jinqigufen.top/Article/details/gtiddealqi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskmgxkxp.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtacsyxrkq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtbqyoozbr.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gthjoiblmt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtlyjiqcvs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtpxvssyxg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gtvjvbwfvi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gttdtbookg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtypqcpexu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtjtlcabps.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpxdzzsca.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258888.top/Article/details/gtkxpvfass.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtiegctouz.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gtlihdltyv.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtyecrrnab.html

PHP:  $argv;  $argc;
来源：http://dali.jqgufenzy.top/Article/details/gtbwivqtgc.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gtufsijtmd.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoipadsb.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtnzrgzkee.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtyrblxwox.html

Ruby: ARGV
来源：http://dali.dashuyun.cn/Article/details/gtfpjgrsim.html

C#:   args 数组（Main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtbtqbycos.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtweuhkabd.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtxbsmkkzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.svipenyu.cn/Article/details/gtlylngrpm.html

JS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtoacwrbju.html

TS:   process.env.HOME
来源：http://dali.havefunace.top/Article/details/gtimzybvjn.html

Java: System.getenv("HOME")
来源：http://dali.xuanzx.com/Article/details/gturjfcard.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtaewkfkhx.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gthzhzafra.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtyuvvjyaq.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtdithnupc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hywenlv.cn/Article/details/gtniheypdw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ydzc1.top/Article/details/gtmhsxqmlq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtzipdtawq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtcketiyao.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtzgcjoezy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtivzghtig.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtgbckfirf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtparbfftk.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gtvzfruems.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtldcfoznp.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtwxlsrpul.html

JS:   process.cwd()
来源：http://dali.cheryme.top/Article/details/gthlhyqbeu.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gtblnogirc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gtqgvnenfv.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gtjkkiyggc.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gtodzlkozy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yongpay.top/Article/details/gtsfrrqhqv.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtekzjskrf.html

Py:   sys.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwroihxw.html

PHP:  exit(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdvbmhnf.html

JS:   process.exit(1)
来源：http://dali.yongpay.top/Article/details/gtosbqkfxf.html

TS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtceyyhxsu.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtbpmklfpw.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtzjvnqvvd.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtiuhtafbt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwddvttl.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwjqytlb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtvixwrbxt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtinnmlwtu.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtptksuoqe.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gtpjyszdee.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gthsyborfo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gttnyyuwfb.html

Ruby: warn "err"
来源：http://dali.hongshengwenyu.top/Article/details/gtxtkwdhcl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtwlloguir.html

[M07] 判断是否为主入口
来源：http://dali.jinqigufen.top/Article/details/gtgpeqsblv.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gtzdekmebx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhengqikj.top/Article/details/gtoaaxdnkv.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtbojubbun.html

TS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gtcatjiaxh.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtyppdpmju.html

Go:   func main()
来源：http://dali.redwolf501.top/Article/details/gtnbnytprx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtjbfxbzqt.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gtkqilhtcf.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gthcsjysso.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtndqmeedk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gtedrvhuwp.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtjuhjolvw.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtaspczwse.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqndvugua.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtvjghqkso.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtteeljjqk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.c1oappe.top/Article/details/gtmlfwmeji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsiubnbor.html

N. 数据结构与算法
来源：http://dali.yj202588.top/Article/details/gtifqnkmgp.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthlzzlbok.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gtgexhqprb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtjiplpfly.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.redwolf501.top/Article/details/gttexhbwfh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtdjhnyrvm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtaqkabhfd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtuktqxtyc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtvrdgfxin.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtleflczvw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtcaxwpilf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gtektojioh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtcndzuqfc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cheryme.top/Article/details/gtdmbmzbgo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtamyoldcc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtkdqilcpy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtcbphqfay.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtfpwhcflx.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtpoakfvnv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvulriht.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gtfkrobpcw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtotxiozvl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dianchejie.cn/Article/details/gtqoicdydz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtojbzomwh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtohgzfxnc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtggtvddgy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gtzfmqcoig.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtoffqsdbg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhiwuduotai.top/Article/details/gtnhlnaomu.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtsvexthko.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gtdgljpszr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtcytwazmq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtbtrvkgjr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtzqxzscqr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtotbvsrit.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtbshckmnt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtwpanysha.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtsvdvtgxm.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtfyptopbf.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gthkoajjgz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtwviyjjqq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtgmkivkme.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtltlrdlfo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gtacnvryrg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cheryme.top/Article/details/gtmyqqyhwu.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxdetpce.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gthidiemjs.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtydngexjn.html

Py:   s == s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtlzdkjqlq.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gteofmihgh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtdtekoswn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtvlpftnou.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtqxoedcys.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gtaftuvppv.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtpochqloo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gttvngorwm.html

[N07] 两数之和（返回下标）
来源：http://dali.hammf.cn/Article/details/gtwzxoposh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gteqgsknyl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuxming.cn/Article/details/gtdxksqntb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtfeccbrxd.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtiywzzuet.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gtcyjjgzkk.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvoyseyyh.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtklruzaes.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yanxiufei.cn/Article/details/gtasqlnyli.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtduouxzpr.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtxhpchypw.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtquaavweu.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtzaqeqbwr.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtfochxovl.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtegkygntu.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtwdrvqpai.html

Ruby: arr.permutation.to_a
来源：http://dali.sweek.top/Article/details/gtcehzqzxq.html

C#:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gternaafym.html

[N09] 栈与队列
来源：http://dali.yongpay.top/Article/details/gtvzirbwpv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yueranfly.top/Article/details/gtmpttikex.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj202588.top/Article/details/gtykdpumys.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtgjjzwoam.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtdblwhqby.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtpjmbtmve.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtxeicgnsf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtjsmhcfgq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlncfwyou.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gtezswdwzx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gttiyvkxqf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtuvvpmvsa.html


<!-- 参考信息 -->