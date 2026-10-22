代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258.top/Article/details/gtbhkiettm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtldsfhscv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtphzfxtgy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtahbxfcrp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtvcvcjchz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtvqbnjzai.html

[K04] 读取 JSON 文件
来源：http://dali.svipenyu.cn/Article/details/gtznxyrmxo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hnxiangtu.top/Article/details/gtuyfpcdcz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtxxjfcfai.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtkbyfjaai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gttqitnrng.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtryazviwq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtofvuoqgf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtymoxpkfi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pengpengdd.cyou/Article/details/gtgeigsexo.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnhbloxp.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtjhwarxlw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ppjwa.cn/Article/details/gtpghpgltr.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gtkakphrao.html

TS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gthxtpkbjo.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.wangdashe.top/Article/details/gtpdkerjdg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xuanzx.com/Article/details/gtrcwgyzzf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hnqzz.top/Article/details/gtrjpvvpmj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.0kj1m.cn/Article/details/gtrdbrvucj.html

[K06] 解析 URL 查询串
来源：http://dali.yuxming.cn/Article/details/gtzcpbreet.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtnnzvupxz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtkerxinbv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtbkrtrpbu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtyhdizmza.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gtncipkuuv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtnnshwvly.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtsatomcym.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gtjmtrlkeu.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gttbqamyvq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtlwhjtgde.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daria6918.cn/Article/details/gtatvaibqd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtshabqagj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtvrzdtjop.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gttcnobese.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtyjtlaqjq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtcxycfccp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtkqtxjyup.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtahzzbept.html

Py:   pickle.dumps(obj)
来源：http://dali.svipenyu.cn/Article/details/gtlubuabfw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtjhkoejlv.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhoulong.xyz/Article/details/gtrwacrffn.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtvnhvkrfg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtdjwylmyh.html

Go:   encoding/gob
来源：http://dali.guowangkeji.top/Article/details/gtsykorocw.html

Ruby: Marshal.dump(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtzioepxma.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtvlqhdobh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtembticrf.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gtrkbwummd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthpawphrm.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gtrlfeftlw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gtviuhloee.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxinkj.top/Article/details/gtkjuointm.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtxvpibbvk.html

TS:   await fetch(url)
来源：http://dali.0kj1m.cn/Article/details/gtqazcamdu.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gtixodwzwe.html

Go:   resp, err := http.Get(url)
来源：http://dali.cucudq.cn/Article/details/gtejgqpuek.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sweek.top/Article/details/gtsonavutn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcxvuqtm.html

[L02] 发送 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtmjyafuxj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gtryloxreu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtpmsenbbe.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gttnpnijho.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtqjaqrxpl.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guowangkeji.top/Article/details/gtrrxridsv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtrabaoylt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.pycfn.com/Article/details/gtnhwsethv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtetkgsaoy.html

[L03] 设置自定义请求头
来源：http://dali.hfpthk.cn/Article/details/gtdtoubgyq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tanke756.top/Article/details/gtufmxyarz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaxnvlum.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.9152youxi.cn/Article/details/gtwussppzc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gtzhlyytnr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gtnkcyyzmh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gtjekpsrtz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gtqtwzyvyy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gtgacwzumb.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gtkmylxmtv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gtsskisool.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gogol.net.cn/Article/details/gtllqdkkdl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtskchuvry.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daxiang520.top/Article/details/gtrykhtqoi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gttkxjwwgl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gtostrvzpz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yangfankeji.com/Article/details/gtgaxqscot.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yueranfly.top/Article/details/gtipubknpt.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtivybgmmv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtchzfnvse.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gttzmbpsmy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gttqzddrwo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtggfotlru.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuetiantiany.cn/Article/details/gtbmndxmtd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.birdmap.top/Article/details/gtbjptrjuo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gtiuzbzrar.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtfdbmtusr.html

[L06] 解析响应为 JSON
来源：http://dali.cqqwz.cn/Article/details/gtjjsutbet.html

Py:   resp.json()
来源：http://dali.nwbrower.top/Article/details/gtobvsnksk.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gtyqumsxcp.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtzuirngsu.html

TS:   await resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gtfbxfljva.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gtnvwufyrr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gttnwawqxh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gtvbmmqfle.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtjlpuoezg.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtfdmqyina.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtwbggamts.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hywenlv.cn/Article/details/gtabiwkmjj.html

JS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtulwpwcnd.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtogenxhqh.html

Java: resp.statusCode()
来源：http://dali.yuanzhike.top/Article/details/gtrjupnerm.html

Go:   resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtuoitceeh.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gteprsuqfc.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtvrtbbtvl.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gtnkmgnwtu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.snrcjt.cn/Article/details/gtxgydvtcq.html

PHP:  curl_multi_init() 系列
来源：http://dali.tianlin.xyz/Article/details/gtrxlkagcr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtqcdwzyyb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gthmcidnea.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtydgaocgd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gtyoatjzws.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtjssgevhb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtioutpntz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtaenkuliv.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gthpikyjsv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtepmfwqjs.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtqhqdazka.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gtoyngloya.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtlcsomdhn.html

JS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gtzcqsgfqj.html

TS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtquuhmplm.html

Java: args 数组（main 方法参数）
来源：http://dali.andypj.xyz/Article/details/gtcxpouatt.html

Go:   os.Args[1:]
来源：http://dali.yj20258888.top/Article/details/gtrtvaaqpe.html

Ruby: ARGV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbfbwcon.html

C#:   args 数组（Main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtjnxlenkj.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtofqvecjm.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmiwghvi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtmqmajgbh.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtciywwiox.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtdtjaqnpy.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtxgflwrzc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtsqktbwdx.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtzniesstz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtoaqnchzq.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gttqdwppoq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gtnsimhmdz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtbtxiqcbi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gtwkbceznd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtcxphmnrt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtwzoijzqi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnqzz.top/Article/details/gtjrrnxuhs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.iojbl.cn/Article/details/gtzbvgchbb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.snrcjt.cn/Article/details/gtigmhoove.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gtednjgolx.html

Py:   os.getcwd()
来源：http://dali.sxryk.cn/Article/details/gtgqtulcja.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtklvnobbw.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtoghjmetb.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtxrhrnooo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gtxnbyjcsk.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtyowztwdx.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gtsvroqizz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzojlayn.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtytipjpgp.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtxtwlojzl.html

PHP:  exit(1);
来源：http://dali.ppjwa.cn/Article/details/gtjtwbqyex.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtofjnaxtn.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtjazrasrb.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gtbgpwyarp.html

Go:   os.Exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrecmnjxa.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtsfrwlvrl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.9152youxi.cn/Article/details/gtpjvauefr.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gtajwcbwpp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtlqczluzx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gthfxzebtv.html

JS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtnayktovm.html

TS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gthmltejhn.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtajkcnmbk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyzswvia.html

Ruby: warn "err"
来源：http://dali.yonumen.top/Article/details/gtoazuulqj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtzpdedpvj.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtzjnqufpl.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtpwurjjpc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbkpalgz.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtsynnlsen.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtttmgthly.html

Java: public static void main(String[] args)
来源：http://dali.xuanzx.com/Article/details/gtqvxyzeoi.html

Go:   func main()
来源：http://dali.shanyushiyangtech.top/Article/details/gtehcgihlo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzvfqkrv.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gthbsuesdj.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtuzuefjdr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtsmwyzula.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtrcyvnlgy.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtynwwvhqr.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtovxtfbsf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gttkowvnoe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gtlgeinaov.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtzbuhplwx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtfvcheaik.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtauavwkfj.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtgfffnbau.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtiocshvmb.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gtraavbsfh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyomrsirk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttprfslga.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtbssukgbe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtjxfbovvk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdlswlabb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtkbuijocx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtcrghcxtf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtkdmjtofl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtafihsjzw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtabtcbrng.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gthclygrkk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gthwjyvlkv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtkhteuqqi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gtljxhnrui.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gtspeilrvy.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtniuwloju.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtomgkvsiq.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtnvpirdfp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtgcpvvmas.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigufen.top/Article/details/gtxyyvfmrn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtpjyldfok.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtomtdzwft.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtnlbuwyav.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtzkodhbfe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmokxejck.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtiotocfxm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtzuwjmfop.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtruzzsblf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtkmlwpqak.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtnvygdvby.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtunkwgtke.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtsswiwjnn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtnmobzfmv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtrgwiqkuc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtmcakiyfb.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtbwpubfmq.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtjywuuejg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gtvbtywhuv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gteqrdmjor.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtbtqxdvjy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtfaycizvw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcygiblhk.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtuctqlfko.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zdqjudy.top/Article/details/gtoaeobloo.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtkshpwxxz.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtyznglpcf.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtqjxroqiw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtjmhadgqg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtqqzfdsrv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtdydxmabk.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtlfqvzifm.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtvkczcenh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtkkderlai.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtilkzworh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtmgygppta.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtwykqnpiw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gtqafmlmei.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtvgglukuj.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtsoxcixfw.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gtrxjjlefa.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gtsrsdoind.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflfaabcv.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtbvkkvjrl.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtmqwyehdo.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gtbcxtqjwv.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtktzlobqu.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtotnnqxlr.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtwpykqrly.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtukxsqoeg.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtrlpxoxkn.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtaulcnuko.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtcpuichrt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.smart0.xyz/Article/details/gtkqeyosvn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtyowxibar.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtugjwhmno.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtjvwztgze.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gtakdbftrg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gtrqhuccvl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtxwcnugsl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ehwqpu.com/Article/details/gtoqxpoxdb.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtanqdmqtc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ybcxt.top/Article/details/gtvsgwktfn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtkfsaxtgr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gtcqmxkjdy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hysaishi.cn/Article/details/gtbzpgubmg.html

Java: class Node { int v; Node next; }
来源：http://dali.xuanzx.com/Article/details/gtibmtydkm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtmsvxchoy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbgtdzcy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtmbxcywoh.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtlozjwwmv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtattzqjna.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtvwhiujiu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfxhkwqk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtwyfwslrq.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gttedlsmqq.html


<!-- 参考信息 -->