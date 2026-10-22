代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnjsyldv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtnldnmypu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgfzy.top/Article/details/gtkkttsrhg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yanxiufei.cn/Article/details/gttkhfkjxd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtxsoyxsvo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.meibo888.top/Article/details/gtorqkzmsc.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtjkuvmmnl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gttrkwuale.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjvwwbqf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtgrdaogwk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gtbmdislxl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gthlzpzmim.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtafvtjrtc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.hfpthk.cn/Article/details/gtfwvqvygt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gtsnkhwsty.html

[K05] 深拷贝对象
来源：http://dali.zhijiandao.cn/Article/details/gtatbqvwtv.html

Py:   copy.deepcopy(obj)
来源：http://dali.xylfe.cn/Article/details/gtrgynping.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtepuiuvwh.html

JS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtmpbpeqak.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtsqjyupmg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtcsmasotw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.aibaodan.cn/Article/details/gtlssxpnjn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sufxvd.cn/Article/details/gtfscsswdl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cucudq.cn/Article/details/gteixrsnhn.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gtdbyhvaws.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtwhnxigsr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gtgwankytp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtrjdikdfg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtavggbkaa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hfpthk.cn/Article/details/gtblugscsg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtifldoqtv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtuljpoajd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gtabeqodjz.html

[K07] 进制转换
来源：http://dali.snrcjt.cn/Article/details/gtvxbjqvyk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtybqchxgl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gtzligcglk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdikwncum.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtdqnqlpxv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gttdauzbpo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gttfcjxyny.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.316326.xyz/Article/details/gthqecltsi.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtedzismei.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gtssupewhl.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjxzkhej.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinqigfzy.top/Article/details/gtuxithrbn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gthhzsvles.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cheryme.top/Article/details/gtshwmqufg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gtnjjbgjmm.html

Go:   encoding/gob
来源：http://dali.jinqigfzy.top/Article/details/gtcimlmbnk.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gthdtemyao.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gtisgentbk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkpxokus.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtkcjbnonr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gterduxuqu.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuqjujdy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gttatayyzu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yueranfly.top/Article/details/gtqcpltbxl.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gttargmpmy.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtpwwmmlke.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gaohongyu789.top/Article/details/gtziktzcwk.html

Go:   resp, err := http.Get(url)
来源：http://dali.sufxvd.cn/Article/details/gthchlavpb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtobxltbpx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtvyjochgk.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtqmbohbsy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.meibo888.top/Article/details/gtpfaaffhn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.vqdsnc.cn/Article/details/gtpbjkmjft.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtkayuaizn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuorphstn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zdqjudy.top/Article/details/gtavjspbwl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sufxvd.cn/Article/details/gtschyjiye.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yanxiufei.cn/Article/details/gtdtuvjrjn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtssejmzmn.html

[L03] 设置自定义请求头
来源：http://dali.yuxming.cn/Article/details/gtaoceouwh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jqgufenzy.top/Article/details/gtlnzhktgc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gogol.net.cn/Article/details/gtvixlhpyg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtavvempie.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gtfdgxhdgl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenzaomai.com/Article/details/gtxydrejmk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtlzqdimbk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtgktxynqj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gtvtoumfbv.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtfedwbupu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtmzybtgbc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yueranfly.top/Article/details/gtytsyqpym.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gtknjlgxsm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtptfvvkel.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gtgegstagf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtqanqusfo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gtptlfjcds.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhixingplan.top/Article/details/gtukoaqpbz.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gthwwdthsm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.c1oappe.top/Article/details/gtcjiugcqw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fzhhl.top/Article/details/gtyatqqahl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yvedp.cn/Article/details/gttyaeyfvt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtojlrmklx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gtjxvycwrh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtzjjblczh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aibaodan.cn/Article/details/gtyqtofrcr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gtxqxmvier.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gthxnhksxi.html

Py:   resp.json()
来源：http://dali.cashguo.top/Article/details/gtwlpbrmkd.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gtvdudzfio.html

JS:   await resp.json()
来源：http://dali.meibo888.top/Article/details/gtboczpnvz.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gthveaplfu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtwhxowlwl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gtqhjnrqme.html

Ruby: JSON.parse(resp.body)
来源：http://dali.redwolf501.top/Article/details/gtbylfuieq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtzgywvnyd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtfahtrqol.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtcrvhodrp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangdashe.top/Article/details/gtxdnhslla.html

JS:   resp.ok;  resp.status
来源：http://dali.yuxming.cn/Article/details/gtgsgjfnsk.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtycbwfcjd.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtxnwnuvfr.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gtcqaprkgc.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtnflotgkc.html

C#:   (int)resp.StatusCode
来源：http://dali.0kj1m.cn/Article/details/gtuuvlstcu.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtgczcidsy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hnxiangtu.top/Article/details/gtdtmtxsdv.html

PHP:  curl_multi_init() 系列
来源：http://dali.dashuyun.cn/Article/details/gtxmxpnfvl.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtpowteygx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtygptdjbu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gthnkyjqov.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gttmambtqn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtjshchzga.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenlongwang.top/Article/details/gtiedazoov.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtwbxhkwcs.html

M. 命令行 / 进程 / 环境
来源：http://dali.bjfxy.top/Article/details/gtgsstafjm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpbveqjna.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gthwrdyjnd.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtuqebacpy.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gtrrucddee.html

JS:   process.argv.slice(2)
来源：http://dali.xylfe.cn/Article/details/gtyridpbuc.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gtgnjtcgtz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfehzcwoo.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtenvdeuls.html

Ruby: ARGV
来源：http://dali.chenjidiqi.icu/Article/details/gtjwjsidda.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtmlrmmtdr.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gtcytqumas.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtokubxkhy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtpqzlbnsk.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtvykgzckj.html

TS:   process.env.HOME
来源：http://dali.hysaishi.cn/Article/details/gtldtjpung.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtjjkzgzgj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtvtxotkvx.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gttybwonda.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtvjvxqrgo.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtdotamytn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.meibo888.top/Article/details/gtbvbjvyjd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtcxzmghru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtnghvqfex.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtspjhbykl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtejboealm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gtpnwsnhde.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gtnashauis.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtxezawefi.html

[M04] 获取当前工作目录
来源：http://dali.dianchejie.cn/Article/details/gthmuvkzmt.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gtyxqamkls.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtbzrizjgo.html

JS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gtrnpfwbze.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtghhuijax.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gtwhnasvzy.html

Go:   os.Getwd()
来源：http://dali.tanke756.top/Article/details/gtnpftcfgr.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyhobvdk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtxlzibngh.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtziakrjwp.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtxmykmzrs.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtgoqqiplk.html

JS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtykegregg.html

TS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtwcgxwgzw.html

Java: System.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtoekytwfe.html

Go:   os.Exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxxjqtwy.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtcpcrskbr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gttjkunrxn.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtrmtlyqak.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gtcmuprhlq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtsozyduxz.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtoysovqnm.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtwssmarnv.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtysvvtzqh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrneksuou.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gthvxvdgtb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtxwtlbfqo.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gthtnlgbxp.html

Py:   if __name__ == "__main__":
来源：http://dali.gotoacloud.top/Article/details/gtponvstiq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszgzxjwc.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtcqffzqsk.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtozaxcknp.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtkarbhnpo.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtcrviserj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gtdvehiqfq.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtlwvngjzi.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gtiyvskcwg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtibgkfghx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtcghqrinq.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtmzpelkoi.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtagczlgfk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtptmdztdy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gtnohyqkpt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtalauxtck.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gtcxbmdawp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyjscmzod.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtbvvtnhod.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrfbudbtz.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gtlubtcltg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtkirvlkvi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gteohswzns.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gttzqjrkpz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtvnsztzxs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtqckfypoo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtjcspqoyk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtseussfwn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtslfgcjdi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gtocqrmcpy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtshlvfyzq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gtzbdobiyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gteioavbmh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtckrncpil.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtkuqesimh.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtgpomdrgb.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtipahbuhv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtwywopifl.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtheozqpbs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gtffdahnzd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtpdvwpwym.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtiqrvndmy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtenngpwcr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtnwafzpkl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gtqfrwvohd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gtqplkgfjt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gttnalxgap.html

[N04] 斐波那契数列
来源：http://dali.haohaochexian.top/Article/details/gtagaqsmyh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gtzynpuqpd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gtqtwhqpvr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtxskydiws.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtvpyskqhz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtjefajych.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtkwlaszzj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gthyfxofdx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtvdwweiyh.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtwgvbxlaq.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtbatysjuv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.kuanghao11.cn/Article/details/gteqxckycp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtcheuetjr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcfuwlvmj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtlkohlhmi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.havefunace.top/Article/details/gtoruhaixz.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtoqabsivx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtwtilxywv.html

[N06] 判断回文字符串
来源：http://dali.sxryk.cn/Article/details/gtofdpeany.html

Py:   s == s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gtjtfonyeh.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtxenaersn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtgzgcnirt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtroiaufhh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtcowvrnwz.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtlbhserua.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtmwcbhqmw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtqspiroie.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtvzflmwwl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtcuresccg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gthiirlhns.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtjqwruwsr.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtafrcphwh.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gtujujdneb.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gtceepjmli.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaufydnk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gtqdwbekpu.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gttsduwfhi.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gtgqgfhlyk.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtgolgyawx.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtjjkstxtc.html

TS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtdedfsdol.html

Java: // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtnpkpnsbv.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtegnvuubj.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gtjsvgihgc.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtflrgwwnd.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtmhokweff.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtesyvdzgd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gtnfifotgw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgncsqvw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gtluilkgrr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtjynnewlf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gtibovucad.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gttahxnmko.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gtkeskvrex.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gtaneenxlt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gtknibuudk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkerzzztq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtlgpcivep.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtgxmbsxso.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtekbhbinh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczbmnzfe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gtbcydlwlv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cdnleiting.top/Article/details/gttfnrvrkf.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gtppxmewek.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnqzz.top/Article/details/gtkggkwmkv.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtmbwxpqaw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtsrezectl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtpebvxbjz.html

Java: // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gtsadxyimd.html


<!-- 参考信息 -->