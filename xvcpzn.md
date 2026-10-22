代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.hywenlv.cn/Article/details/gtgcyxdshd.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtjtoylryo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtxutvtevj.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtefknikcv.html

TS:   JSON.parse(s)
来源：http://dali.guannengcc.top/Article/details/gtmqncciuh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.fzhhl.top/Article/details/gtqfgwchkp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtztorzxve.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtpqsocuvi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sufxvd.cn/Article/details/gtubktflkr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gaohongyu789.top/Article/details/gtpayzxhta.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yuxming.cn/Article/details/gtgrjweeie.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtgxfhgjjm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpadfzmf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtqgyyvxfv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sufxvd.cn/Article/details/gtwqcxqxui.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gtzoumyfag.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ydzc1.top/Article/details/gtborldyue.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aizwys.cn/Article/details/gtvenanevu.html

[K04] 读取 JSON 文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkyvmoscd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtcvobmxsx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nanxinkj.top/Article/details/gtuymcpgug.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gtopezeizs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtsrqxlgwx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gtueonqlzq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gttuqcttqy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.daria6918.cn/Article/details/gtoeaaavvz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.havefunace.top/Article/details/gtflznhjct.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gttusgtsre.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gtuqskpdoe.html

PHP:  unserialize(serialize($obj));
来源：http://dali.andypj.xyz/Article/details/gthyoxsfpt.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtjblwbusz.html

TS:   structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtluctgljb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtfgopaxuj.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.bjfxy.top/Article/details/gtzupckzah.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ehwqpu.com/Article/details/gtixacwekn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtmiboqajh.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtjjlijryb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gteedmsjok.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.iojbl.cn/Article/details/gtyvjxlpco.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtqjpzudrn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gthbhcorcq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gthfcekuzd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtvuwrvqvk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtapbyehxc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtekullonp.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gtmbtysyxs.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtpdhgxksk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtakrvywhp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtcylwmfxj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtwjespbfw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gtzaunkxml.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangdashe.top/Article/details/gtytzjlsqg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtanazkbhf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtnkxfjonl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtmfcafxkz.html

Py:   pickle.dumps(obj)
来源：http://dali.ivvv.top/Article/details/gtifotregm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gtcqgjnpvh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtbckxopuk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtfxenmhlu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.guannengcc.top/Article/details/gtloqhzxsu.html

Go:   encoding/gob
来源：http://dali.bjfxy.top/Article/details/gtacwmtxyd.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gtgdxpiqkc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtpyjlemyi.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtogphxudi.html

L. 网络请求
来源：http://dali.hysaishi.cn/Article/details/gtofrgblaz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtindrmtuy.html

[L01] 发送 GET 请求
来源：http://dali.kuanghao11.cn/Article/details/gtgqwqhwyf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gtydigsuip.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.9152youxi.cn/Article/details/gtflwejtwk.html

JS:   await fetch(url)
来源：http://dali.jqgfzy.top/Article/details/gtfdfnzgcq.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtwihqtjen.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gtuedfruwa.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtusymphbk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.smart0.xyz/Article/details/gtzxfottdx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sweek.top/Article/details/gtbbzxjloz.html

[L02] 发送 POST JSON
来源：http://dali.sxryk.cn/Article/details/gtbdbxzhal.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtvxaybfci.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtottluxpk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtcnxddqgt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxinkj.top/Article/details/gtmknyegcv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtgakijkor.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hongshengwenyu.top/Article/details/gtwdaqhaki.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdudoygz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gtizvolgmm.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtjgfbhsfa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.316326.xyz/Article/details/gtkskxbhpp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gtadojoiyi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtxytqqgwq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtjynmremq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtlcvzvzpj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.svipenyu.cn/Article/details/gtmavdwajd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.haohaochexian.top/Article/details/gtqewnnqnc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtctqwbphq.html

[L04] 设置超时
来源：http://dali.nanxuanxn.top/Article/details/gtidaogwsw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtyfmihyky.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtlkfiqzdg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtuhbrnhia.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtknwuenhw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtzhcrkjgc.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtdhesewfc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gtjjtrhcqa.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yonumen.top/Article/details/gtiohzmrhu.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gtcygrajqr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj20258888.top/Article/details/gtcoprvwpu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangdashe.top/Article/details/gtsnzxvnjs.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yanxiufei.cn/Article/details/gtvdbocgvk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cqqwz.cn/Article/details/gtphygnsff.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhongyouzk.top/Article/details/gtwusgltuw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gtpdogjtig.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nwbrower.top/Article/details/gttvocihbb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtlcouisfh.html

[L06] 解析响应为 JSON
来源：http://dali.tian-w.cn/Article/details/gtlrcicdef.html

Py:   resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtnkwthtvc.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtehrgpmzo.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gtwsinzrbx.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gtfrnpkifk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtssjmnbst.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtpizdldag.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtqpehgsjx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.birdmap.top/Article/details/gtlypyhpxh.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtlwdktvqi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtqwmeutit.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ehwqpu.com/Article/details/gtojrhihhl.html

JS:   resp.ok;  resp.status
来源：http://dali.daxiang520.top/Article/details/gtpfbycgvp.html

TS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtniprwert.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtcqymkofv.html

Go:   resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtgzketnmi.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gtctipjekp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gtctruwwca.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtsfykwsev.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gtbllnsqlx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtplasstpk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtcdinuuqp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjefjmhzp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgfzy.top/Article/details/gtzhdfswuu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gtlbjhwuus.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gtyzxjjvdp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.smart0.xyz/Article/details/gtysnnnidn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsrbedvsi.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gtosinmlyy.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtcofpwzie.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gtemxrnsvf.html

Py:   sys.argv[1:]
来源：http://dali.bjfxy.top/Article/details/gtegutisyz.html

PHP:  $argv;  $argc;
来源：http://dali.0kj1m.cn/Article/details/gteirnxtud.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtrwlpcbfp.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtdwwmgulp.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtdeplledb.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqhewkon.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gtwuhdqqrx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtjvjldvri.html

[M02] 读取环境变量
来源：http://dali.daxiang520.top/Article/details/gtzpsollon.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtujnyxzha.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtrvzuaaod.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtyvbivmwi.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtlfnxvrux.html

Java: System.getenv("HOME")
来源：http://dali.hammf.cn/Article/details/gteixyncyy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgfijmmw.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtmyyiujpf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtciqsgoeb.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtojbwetfs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sxryk.cn/Article/details/gtlwszqgqx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaehbxrj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtcoojqoan.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtarwzjtkb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.havefunace.top/Article/details/gtzujuspcl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtlddguzup.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gtrfdcxiek.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxinkj.top/Article/details/gtzwaviecw.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtcucdqt.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkkmqutr.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gtvzhzhitf.html

JS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtkcypmott.html

TS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gtaijitjgv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtioxsntvq.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyuijorp.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtodrjfxkg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gtqoecemvc.html

[M05] 设置退出码
来源：http://dali.nanxinkj.top/Article/details/gtqxjxuwyd.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtfymexasn.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gthkpmsxoq.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtisisqlte.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gthsexurfr.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtuaoyxizd.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gttfeftajp.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtfktemjed.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtailcdskj.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gttyzpbgcv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtbhusdcob.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtksmvxshj.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtziumvtrx.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtxzidugnr.html

Java: System.err.println("err")
来源：http://dali.xylfe.cn/Article/details/gtrtmhyvcv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtrkjkvupg.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtwtbxfszm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.0kj1m.cn/Article/details/gtvvdjjxcb.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangtech.top/Article/details/gtnybsmzwy.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtipvezysx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtseeflmgw.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtyyzjyezx.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtfdhfjxgv.html

Java: public static void main(String[] args)
来源：http://dali.xylfe.cn/Article/details/gtivvnazay.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtuwkwwont.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtsunsodgl.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gtybfsfsqe.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gtxsoxazli.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtqkwkzgvn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gotoacloud.top/Article/details/gtewcfkcaw.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtzubporde.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtjacyruxa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gtdudzlouu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtvvwimret.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gtbmhzrrew.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtoylqybvs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhihhndx.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkgmzolv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtkpngvjrq.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtthorqhil.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtwwsvaaiz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gtfcugcuax.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shuidangran.top/Article/details/gtlafrdlgv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtizoqddgs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtgkdblrir.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtspoueidh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gtyktwnhcb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtvioxwszm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gteeoyplue.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtiudwervh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtzfyfzjck.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtoctoxrrz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtfpkqkhci.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtiojyvord.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtthaarrai.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtnugnkuth.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cqqwz.cn/Article/details/gtizschjtx.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtteokkbcu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtzsndqhpy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tian-w.cn/Article/details/gtyymjiygi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtopauhruf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gteoaszmhi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtnlrsvhku.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhgijrpj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtculffhuy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtknbhimgd.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtbuddosai.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gttrphgkbz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtgzbqbufs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtkyaxntid.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtgunidfbi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtwgkahhir.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtpsqbfmio.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtfztjhyrj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtttqptool.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtdhafpdji.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtrxklsxge.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hysaishi.cn/Article/details/gtetraktwe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtlxsxytfk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtmttluaxt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtknykcmkz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shzxlz.cn/Article/details/gtbymqybef.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtaylphrnw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhxcqadq.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gtodcuyfrd.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gtbdrrmfxk.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtyhaufczk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtxxygfirl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtqovebihm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ydzc1.top/Article/details/gtnhgymwcj.html

Go:   // 双指针从两端比较
来源：http://dali.xuanzx.com/Article/details/gtxlfnvueb.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtplyhflue.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtbqslhsxb.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtqrgbtxfx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gtelhwvoll.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gtmycgljsx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtpnobwskq.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtledwdgmz.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gtekottbsq.html

Go:   // 手写 map[int]int
来源：http://dali.yuanzhike.top/Article/details/gtxppswaxy.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtskcwphoq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gtmpdsowpn.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtyohyqczt.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtbgjlowha.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtylohpacy.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gttstqaxqc.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtzjuaiqmw.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gttswfiipc.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtqppuyiia.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtugbrkyta.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtjdxoqnkk.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtclqnxiut.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tianlin.xyz/Article/details/gtalauswlx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gteowxihxw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtjyedlmhp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnylgigl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gthovawyum.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvrkmmdw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtlmwyqews.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwdoxmaz.html

[N10] 链表节点定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhlrmhoq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtgffmdytc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gtzizsiury.html


<!-- 参考信息 -->