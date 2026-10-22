代发 wailian999

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtasiwsnoi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gtbhnpyidg.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtnmxsbqxh.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtuwabribe.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtlgfjmwmn.html

Go:   json.Marshal(obj)
来源：http://dali.yuxming.cn/Article/details/gtrepqlado.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtductvfhz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gtopbkomke.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctoydfsb.html

Py:   json.loads(s)
来源：http://dali.ivvv.top/Article/details/gtefpizehc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtqchbbokl.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtzummeyqs.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtaqrsjabf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtjllbqivv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtufpeghox.html

Ruby: JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtqcgsgfez.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gotoacloud.top/Article/details/gtdolldhgn.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtytwsoqif.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gtptekdkru.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtjpcegcfo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtjazpkacv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtepmnrzfn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtcmqdwqxg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj20258.top/Article/details/gtvnfabaay.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhengqikj.top/Article/details/gtngaavedo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtvnavahdi.html

[K04] 读取 JSON 文件
来源：http://dali.gaohongyu789.top/Article/details/gtnckhzjyu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aibaodan.cn/Article/details/gtedztbhlp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavtdgube.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtmnanweoh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtrwrgknci.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtdkjsyscd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtmyvsshqo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtelhzrsnd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtfgkfywkc.html

[K05] 深拷贝对象
来源：http://dali.svipenyu.cn/Article/details/gtdwilvvfq.html

Py:   copy.deepcopy(obj)
来源：http://dali.ivvv.top/Article/details/gtqnpswher.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cqqwz.cn/Article/details/gtqxbzizyh.html

JS:   structuredClone(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtlauprkdl.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbphvjbtr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtbuwiarlm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtzfhcuevq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gtstbcirpt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gtvzcgndyk.html

[K06] 解析 URL 查询串
来源：http://dali.cheryme.top/Article/details/gtxqzdjcmw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjroihxf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gogol.net.cn/Article/details/gtfkildfgo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtmlvzllza.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquazvael.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sweek.top/Article/details/gtmrnnloku.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gthhumccgq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtwdwhmdpt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtamatggwc.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gtvtaepiws.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtdjucplro.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhengqikj.top/Article/details/gtobpbpmhl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtnntlujbk.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtfnjafujg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gttnaxrsko.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtvnywknsi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.haohaochexian.top/Article/details/gtmnwykmqm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtzqmmyovc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gtfatefuyn.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtmwppwtpo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gtileeldtr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyugzgujh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.dianchejie.cn/Article/details/gtcspksxwa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gtcopnftod.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gtnmbbxzrf.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtuycwdlgh.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cqqwz.cn/Article/details/gtivvtvxmn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtxdgpxeri.html

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gtpzzogkto.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkonszcuo.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtnmyqkfhf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtivttygqp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hongshengwenyu.top/Article/details/gtqpyeezpi.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtfhifuryt.html

TS:   await fetch(url)
来源：http://dali.sysykeji.top/Article/details/gtkueobpyt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.9152youxi.cn/Article/details/gtjhkblvqs.html

Go:   resp, err := http.Get(url)
来源：http://dali.ivvv.top/Article/details/gtlzaquyce.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhixingplan.top/Article/details/gtkorhstal.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuxming.cn/Article/details/gttzwsepkz.html

[L02] 发送 POST JSON
来源：http://dali.mhx1999.top/Article/details/gtzkadnrli.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtcehcvajf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtffmndrys.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqjipzna.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtoikviegf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gtkooxqdtf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gtbcvgwpqq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gtqyrlrrox.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gtcvubnqdk.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtebhvbkuw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtktmfvmyu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtasoeprjj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtoohmzmpy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gtglnsismu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gtmnmiynpm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gtjoctgwgy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtdgbklony.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtfnptckbv.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gtqhmfvtwc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gtvwhypiaf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxinkj.top/Article/details/gtxsfswhcc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtbynzhpjz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtmcqutcns.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gttibexzyy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gtgdgotydz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258.top/Article/details/gtpusujihy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttejsulie.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gtifnijnzi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtfinstbxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtsdwvalmz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtunjgzwxr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gtbbtoxqqk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nanxinkj.top/Article/details/gtnwigwrin.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gtuopkudig.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtagisxkgf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtcqbioaih.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtgwexhuiu.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtauctwlid.html

PHP:  json_decode($body, true);
来源：http://dali.vqdsnc.cn/Article/details/gtsqtefgue.html

JS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtofyfjkua.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gthoyjfdrt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtkeizwvje.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gteiosggim.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gturmxklct.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gtjtnhqyty.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtojfiokwk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cdnleiting.top/Article/details/gtmahpysxu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhiwuduotai.top/Article/details/gthkbjhfea.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtkeonpcjv.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtrpuaklzq.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gtmhbwgodr.html

Go:   resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtsvaxzldf.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtjklqklkm.html

C#:   (int)resp.StatusCode
来源：http://dali.jiagoushi.top/Article/details/gthafijmrj.html

[L08] 并发请求多个地址
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypbygfus.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gtbwyzpgmr.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtctbhegqi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtrssazmbq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtylbjifwq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtdxpeyicw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ivvv.top/Article/details/gtxrquexfo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtupwdprob.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtdntnwczi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnywbanxs.html

M. 命令行 / 进程 / 环境
来源：http://dali.aizwys.cn/Article/details/gtoqlfnwmu.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gttucxygkl.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtfdmmfalr.html

Py:   sys.argv[1:]
来源：http://dali.cucudq.cn/Article/details/gtrzwjxtmg.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gtxabjbbjk.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtqytqkkik.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtelznnpyl.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtihdiashp.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtujruymkw.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gtjgtkwvgo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gthwyzizhf.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvffvwqnw.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtynmopefg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtluvivhrh.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gtojedkhgn.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtibqqspgz.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtjmxnulfu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtztonvzxx.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtnxwvgctp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtdhnudvgr.html

[M03] 执行外部命令
来源：http://dali.hongshengwenyu.top/Article/details/gtpmrtkecm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtlittfeuj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gttrpfbeez.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinqigufen.top/Article/details/gtaqqudaku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtflhregfq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtvgorwshs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtfxjolqfi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gtfzikxupw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtxvrexuvt.html

[M04] 获取当前工作目录
来源：http://dali.shzxlz.cn/Article/details/gtnlotqygz.html

Py:   os.getcwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieczydve.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtrormlkyt.html

JS:   process.cwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllnnaimb.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtxzrxlzqg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtljihiqgk.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gtriyrmkkw.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtexzwlwou.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtfenaixsx.html

[M05] 设置退出码
来源：http://dali.jqgufenzy.top/Article/details/gtmtojabio.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtjkyxhhne.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtrkdllsuf.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtopugizhj.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtpwgauojt.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtqslqepsg.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtkzahjvzw.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gtgmmesbfh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gtdexumohj.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gteidrfway.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtraypcach.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtgypeoxrs.html

JS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtahypemyx.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtqbeotngr.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtjvtabbah.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtwjxqlmov.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gthbogvtbp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gtbzqdvvmh.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gtvmyhgalj.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtdlujzjgw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtetzgisfn.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtfjivalfe.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtyvghvvci.html

Java: public static void main(String[] args)
来源：http://dali.birdmap.top/Article/details/gtbchztzoy.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtzyuazbqw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gttnbmnuwi.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyfnpyoy.html

[M08] 获取系统与运行时信息
来源：http://dali.guannengcc.top/Article/details/gtxtzulehz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gtnxwxsuoq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gtoqgqftfy.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtlwblwldm.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtnsgnciuk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtbwkhqpso.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtdioyrmiz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gthprxpxbf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gtxuictflj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtoodssahu.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gtnqsqzumq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzopwegeb.html

[N01] 二分查找（有序数组）
来源：http://dali.cqqwz.cn/Article/details/gtakcleyyl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtdpjsmvji.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtoztikuzc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtvlaypwtz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtkewuovtw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtvvjdujon.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtjtwwxexq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtmndjqbof.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtwcjjjkkh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtbnezmnmh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guannengcc.top/Article/details/gthrklwjyv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtbfqkuujl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtrcaboypp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtpgeqgggd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhongyouzk.top/Article/details/gtcslwmfzp.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtoqbersej.html

Ruby: arr.sort
来源：http://dali.cashguo.top/Article/details/gtrykajgsu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoxezfgep.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gtkzbvluwt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gtuvmngwei.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtvcgecxcj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtnoqdyidt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsigvuxpj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiupmwroz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtnldkgwdv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtvywcuhnm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gtipiakpgp.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtouqoontu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtsiunkcgr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sxryk.cn/Article/details/gtvwgfpqqr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtxztmcaey.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtqvmkiycs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtentvwcfu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gtvedbcjbz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtqeqmwrrs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtyagvlgtz.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gthpvqciai.html

Py:   math.gcd(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtjxjyxrmv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtxfskgdmu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgmactcrq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtqolkusvp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtsndeqozc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hysaishi.cn/Article/details/gtrjdvgxvw.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gtnfjhhhws.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gtfafppvtb.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpujtoui.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtglovoaqy.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtfukwovkr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtrixrwssu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtszkfmvol.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hysaishi.cn/Article/details/gthqhjukwd.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtqeaukidi.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtbvhqgskt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtbizsginb.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtaploijjj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtooiufndr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtvhjomdla.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtzyyaqmys.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenlongwang.top/Article/details/gtewauwxww.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtpzmewatb.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtguizkfvu.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtwycbdwln.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtzdnzndyx.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyouizuy.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtfiyyzgbv.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtyhldofwl.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtoehhytqr.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtvbvhgdmw.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtzypigdyd.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtvjiliicn.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtwmabxsem.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtzolnisuw.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtfhrklwzh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtvqgrtqhq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtwgsdbrdv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtysxzjsts.html


<!-- 参考信息 -->