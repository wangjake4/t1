代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.aizwys.cn/Article/details/gtnnyircki.html

Go:   json.Marshal(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtmmlvwjml.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gttnbuxjwa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtfbvhvcwo.html

[K02] JSON 字符串转对象
来源：http://dali.daria6918.cn/Article/details/gtyymgjrop.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtipxwhvia.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gthigekups.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gtywafavoy.html

TS:   JSON.parse(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmshurayh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtqapvmipc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtuviopjgg.html

Ruby: JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtaqfbbpvb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenjidiqi.icu/Article/details/gthgfoqypd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cucudq.cn/Article/details/gtwtmxltec.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnxxxzmb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtqdyydayb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtppsywxhe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtznxrnegy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtuugknlad.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhoulong.xyz/Article/details/gtjsmygdol.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtqhlncthn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtxhkrzgvn.html

[K04] 读取 JSON 文件
来源：http://dali.dashuyun.cn/Article/details/gtrhoixghe.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gtrmmbnmtu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtmubfjkey.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenzaomai.com/Article/details/gtxqntfmfm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ppjwa.cn/Article/details/gtgepxmfgw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtfzrqktzp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtzmogtsaa.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sweek.top/Article/details/gtxlkxdncp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gttuutykwf.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtkdbjkmzd.html

Py:   copy.deepcopy(obj)
来源：http://dali.svipenyu.cn/Article/details/gtaoodxyku.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtevhsivyc.html

JS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtmqgoncjt.html

TS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtnlpcwhbi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtyndekgap.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtulmuayfx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvrcspej.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ybcxt.top/Article/details/gtsxympjve.html

[K06] 解析 URL 查询串
来源：http://dali.xuanzx.com/Article/details/gtjgpdrqce.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ybcxt.top/Article/details/gtjrogpxbt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.redwolf501.top/Article/details/gtztjizmat.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtpsnumhzj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtqmlbxpmh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtrrcjjalj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gtmfvucxgs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtsrknrtwk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtuiuigsuw.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtxmpepndm.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtzpqiqiwo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.guannengcc.top/Article/details/gtckbydtqd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtgbwjjfco.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtxjcrhpwk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzelezlrr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gtpafichod.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gtucdvnsza.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtaxonpmrn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yonumen.top/Article/details/gtnfkujicp.html

Py:   pickle.dumps(obj)
来源：http://dali.jianghu66.top/Article/details/gtyfrrmmkj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.c1oappe.top/Article/details/gtqyorrtxn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtvujqkmog.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gthveicdqf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yanxiufei.cn/Article/details/gtzifdilbu.html

Go:   encoding/gob
来源：http://dali.c1oappe.top/Article/details/gtuwzyuqjw.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtrusxhmya.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtylbmniry.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfyonrivn.html

L. 网络请求
来源：http://dali.aibaodan.cn/Article/details/gtustmtgid.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtglgpxoll.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtdfjzuely.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gtjdlklaaf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xylfe.cn/Article/details/gtwnyetkpp.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtjttdwxte.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gtqymgwlqe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gthlgfauhb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtmdfjwywn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj20258888.top/Article/details/gtqspgshky.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gtrmgcplqx.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtrnjvblpv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtrudegymi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigfzy.top/Article/details/gtjeppsmam.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtnzkacvmj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtlisdiquv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yuxming.cn/Article/details/gtrvmckqwf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.svipenyu.cn/Article/details/gtawszvltv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtbfufxxbc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtiwkagqdr.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwivejfcq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ivvv.top/Article/details/gtezfwwiio.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gtiuqkdfts.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtvrqswxub.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtycufzuyi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nwbrower.top/Article/details/gtcueizulp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtdrvzurns.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gtwsfzngmg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gtgthxtzqn.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gtzfccikow.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yongpay.top/Article/details/gtbnbwviyq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sufxvd.cn/Article/details/gtllrcpphq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtalqyzaag.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtrwrderdi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtmsjacueg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtchopcxmj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtqmfseevn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.svipenyu.cn/Article/details/gthwpulglh.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtjktzwcdm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangdashe.top/Article/details/gtgbhwkppn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtcsrqmakd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtcbxkygap.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtdumbakdn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gttxdxmxzy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtlbuiozbr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtjnkugeqi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtwmghtcbn.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtbalkuerd.html

Py:   resp.json()
来源：http://dali.shuidangran.top/Article/details/gtzthjisku.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gttbpxpign.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gthefbxdqm.html

TS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahbdikct.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gtcmqzaisy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjljdsudn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtxpzhxoqi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtituiauow.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gtorkjahfa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtabrlxkkx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gthiwlwgot.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gttgjckhpj.html

TS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gteuqdwlik.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtllschbrp.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtukfgdugr.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtbhaegbdg.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtbncagymo.html

[L08] 并发请求多个地址
来源：http://dali.xuetiantiany.cn/Article/details/gtgdedrgss.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtzqweiabm.html

PHP:  curl_multi_init() 系列
来源：http://dali.sweek.top/Article/details/gteogfoasq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtzebaocuv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtglpjnzot.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gtbbkzvsua.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtpfdsljsu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.fzhhl.top/Article/details/gtsombdrdw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gthfhwpdku.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkysbftpr.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtqaacmerl.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdudzpzdh.html

[M01] 读取命令行参数
来源：http://dali.nwbrower.top/Article/details/gtxywhkphj.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtieenqpry.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtbebjgyfy.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtimxaescw.html

TS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtjpaezlbd.html

Java: args 数组（main 方法参数）
来源：http://dali.gotoacloud.top/Article/details/gtapfwugmn.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtyrpsizuk.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gthmjcnrzr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gttdgqslso.html

[M02] 读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtfteltsig.html

Py:   os.environ.get("HOME")
来源：http://dali.daxiang520.top/Article/details/gtcajcrpkq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtgqakgwyk.html

JS:   process.env.HOME
来源：http://dali.snrcjt.cn/Article/details/gtznhznssx.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtxijxrilv.html

Java: System.getenv("HOME")
来源：http://dali.sweek.top/Article/details/gtbxagnzjm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtzovyemeu.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtjqgqhulq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtlaydvhlm.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtxqdowxrt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gtieaabctk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuetiantiany.cn/Article/details/gtbscnuusk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtnujlyvsb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtqwlqgqqb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtkyynmvtg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gtttnofaiz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gtympdmwvq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtbdqlyopp.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtxfzitesq.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtunlaqhqr.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtyrmduxnn.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtesjwnzua.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtdenammit.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtltiwkooo.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gtzcvrycex.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtwijhqkuw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtdzsjkfcg.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gturtreaji.html

Py:   sys.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtpmxgewzn.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtrelomirc.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gtjnohseoe.html

TS:   process.exit(1)
来源：http://dali.yj202588.top/Article/details/gtdjhnymlt.html

Java: System.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtmukdqjmk.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxsozckrw.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gttsruaqfc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtkoizeaic.html

[M06] 向标准错误输出
来源：http://dali.zhongyouzk.top/Article/details/gtufsqcvsv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtlrrgympj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yueranfly.top/Article/details/gthkmcullg.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtreswyhwh.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtfjnlavjg.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gtmivutqny.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aizwys.cn/Article/details/gtbrdyuiwf.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gtzpcvflzk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hammf.cn/Article/details/gtkzrvfwak.html

[M07] 判断是否为主入口
来源：http://dali.jlsjyb.cn/Article/details/gtqtithfnb.html

Py:   if __name__ == "__main__":
来源：http://dali.aibaodan.cn/Article/details/gturvmvxmj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtpbbuztmg.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtwaakvijz.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtuyqaeokc.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gtbthmezqz.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqgyfjeo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gtpzuextuv.html

C#:   static void Main(string[] args)
来源：http://dali.gotoacloud.top/Article/details/gtzmqtbawa.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtmzrohrty.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gtpapktraw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gtspwybjlo.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtxexfmmaf.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gttukqokdf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzbxuxwt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtgkbhebop.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.haohaochexian.top/Article/details/gtbbultlkw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtqomnmjff.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqqqfzvjc.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtqyokmcsy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyjlmtzjm.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtprdklknx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtesibkcqa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtaxzrobrm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtzjauidta.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtazhioffx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtjmnbdfxl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtvdvsbfnb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fzhhl.top/Article/details/gtyucisfrx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtbimybihs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtyetnrbqo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtpkilnago.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tianlin.xyz/Article/details/gtlwrarikh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtkcqxwhom.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtfilxrlry.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtvwgxlzar.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtcqdfulbe.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueiqnuib.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtcjpwidbr.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtbepibkhp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtqopmiqno.html

PHP:  // 递归实现，或用 usort
来源：http://dali.andypj.xyz/Article/details/gtzqwkmcry.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtjcpthndc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtcnqowlqa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shuidangran.top/Article/details/gtwligvnyw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjqhcniu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtqaunmhgy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gtbgjzyjqt.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtmmmnkntm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gtgytdbnuv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gtanvveeqc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtaxlyldzx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtncfzubbq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gthmjnacyj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsvymhsi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtbyuwpqtb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtbfnitizn.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtyfvdnjby.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gtxerhdnxh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtsjljydex.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtzxeidjsj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiuxodsyh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtjzvgkscc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtbavcxoag.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtvwcdgmep.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.redwolf501.top/Article/details/gtttlkwyjw.html

[N06] 判断回文字符串
来源：http://dali.yonumen.top/Article/details/gtyvfdnkab.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtllunxjkp.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtfjaaaoew.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtqvxsbdln.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtncyrzdwq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gtraurzbvb.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gttsmzdfjc.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtbbvlnsaw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtwbjilqmc.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtbsrslvlr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtgbnbvxnc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gtagzhpnwg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gtzltavxxc.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gtlpbrefsl.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtncibeqdg.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtopjtccya.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtbhdpdraz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtfghynzqc.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gtflskwrhh.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gtrnlylqdj.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gthczbyrwq.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtljnupdud.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtbwogmtlu.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtgmayqkgd.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtbgdfcmtp.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gtksxfatdl.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtzpxpmytw.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtlptajreo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yvedp.cn/Article/details/gtwuesjezk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtqfmftaun.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtcdrnvsci.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukuxgzmo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtlizzfzbl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtjpjemdei.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtykvahoxy.html


<!-- 参考信息 -->