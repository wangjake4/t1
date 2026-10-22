代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dashuyun.cn/Article/details/gtpcvtvdiw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtgqsrwsmc.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfjijjncf.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yangfankeji.com/Article/details/gtrvqlzopk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtboicrqsn.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtvnhbbofq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtyjbumxvf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yonumen.top/Article/details/gtkvhbydxs.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtynjankel.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.guannengcc.top/Article/details/gtubtkfwrh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtrmbmdvqf.html

[K05] 深拷贝对象
来源：http://dali.quarkkingdee.top/Article/details/gtzhjvxeph.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtjwpvdood.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gtmoftbiak.html

JS:   structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtjzovuyir.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtfxuyca.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtppqwtugs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yvedp.cn/Article/details/gtialejvia.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sxryk.cn/Article/details/gtplmwvhmd.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtcjbxamag.html

[K06] 解析 URL 查询串
来源：http://dali.chenzaomai.com/Article/details/gtwiljlfgi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtyjazkzoe.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkhhaszi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtxlhdrcdm.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.9152youxi.cn/Article/details/gtcbinkpao.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gteeretfjb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtowoxvvie.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtokjdhiku.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yueranfly.top/Article/details/gtmpwjeggm.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtpmdjzyzn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwijlvmtz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.pengpengdd.cyou/Article/details/gthclrggmp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtgvcmjanh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtijetrhni.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtpcpyxdnz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gttxwwrebr.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtexqpnwyf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtddvgwfnu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yuanzhike.top/Article/details/gtcnghgovj.html

Py:   pickle.dumps(obj)
来源：http://dali.sysykeji.top/Article/details/gtbrnazlvk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gtphmwjiex.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gtyjbvudup.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.iojbl.cn/Article/details/gteqjdsvwm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ydzc1.top/Article/details/gtofsahorn.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gtwoxmxkgg.html

Ruby: Marshal.dump(obj)
来源：http://dali.gogol.net.cn/Article/details/gtecoehngx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtghccseeo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtsyhqvunk.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gtgtdafjws.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdmpuydbp.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtcftynxjc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtazxatmic.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtqoegcpes.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtblhfktzx.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gttmrlkqmw.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shzxlz.cn/Article/details/gtheghpedf.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtkuqpmzht.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gteaxfxloq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtclkdpkqg.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtoiwahcms.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtdulofcir.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yangfankeji.com/Article/details/gtmovhwbvh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.0kj1m.cn/Article/details/gtkdmiaobj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtruxgoysg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtghefowit.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258888.top/Article/details/gtckqikjpl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtdcwcbequ.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gotoacloud.top/Article/details/gtdijvvjis.html

[L03] 设置自定义请求头
来源：http://dali.316326.xyz/Article/details/gtlvqkrryz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gtddjjqmtd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.bjfxy.top/Article/details/gtllhefocg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtlvmnxkqu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gtuwshvqun.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gtfpppfhei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtjxplncpz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cucudq.cn/Article/details/gtmhtufjyk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtmcjldijp.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gttagrugxn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtxmvpivhh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangshuangyany.cn/Article/details/gtsagevsog.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtbigneynr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtfhzccirz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinqigufen.top/Article/details/gtgvtqcndd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtpjsommhh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtwblnlrbh.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtzdxncigc.html

[L05] 上传文件（multipart）
来源：http://dali.aibaodan.cn/Article/details/gtbcylnamk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gtjlvcqnaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sweek.top/Article/details/gtwpufzypm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tianlin.xyz/Article/details/gtrcpnnvmo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gtrazrexax.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtwuntzmct.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gzhubu.top/Article/details/gtrfvdrlvr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtssdibygs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtnjmovcat.html

[L06] 解析响应为 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtssrecbht.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtygpdfplt.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtgkzdsgdh.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtlthvkcor.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gtsdfqrtyt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtcpymhmdg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtfmcjgmod.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtkgwybxlm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtucwzlaof.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtlimogyrn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtacbtudrc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtdkdouskd.html

JS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtfauhsvyc.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtksxsoitc.html

Java: resp.statusCode()
来源：http://dali.zhoulong.xyz/Article/details/gtptjheujk.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtaabqtgae.html

Ruby: resp.code.to_i
来源：http://dali.feifeiyinyue.top/Article/details/gtxwodrdyx.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtpzkqkjuv.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gtmybuwisv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtqetrktnp.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtksonsyaf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtkymlsiiw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gtifpltyvf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yanxiufei.cn/Article/details/gtjifevniz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtefqjvcol.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoimquwfu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cucudq.cn/Article/details/gtkjmfttfe.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtllpwchdv.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gtzgsahfqd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtoapjugms.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtfwntfeza.html

Py:   sys.argv[1:]
来源：http://dali.jiagoushi.top/Article/details/gtnkejowqg.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtsbkyafag.html

JS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtbthxjodi.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtzezgdqmh.html

Java: args 数组（main 方法参数）
来源：http://dali.gaohongyu789.top/Article/details/gtkahfhikx.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtbsyzynav.html

Ruby: ARGV
来源：http://dali.fzhhl.top/Article/details/gtvozzxutw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gtcrdhlyww.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtpuftiuco.html

Py:   os.environ.get("HOME")
来源：http://dali.zycfv.cn/Article/details/gtfunoilxs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtmyawlzfv.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtzcidpkho.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtyezatbig.html

Java: System.getenv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtbllctxoo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtyjwjgdlq.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gttdydzdjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hysaishi.cn/Article/details/gtqvcgekha.html

[M03] 执行外部命令
来源：http://dali.cucudq.cn/Article/details/gtmjvlvxaj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yuxming.cn/Article/details/gtrlpmhbzz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtjovojral.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtvewdexvj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gtulnwqvpa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jlsjyb.cn/Article/details/gtgkvfaozw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.vqdsnc.cn/Article/details/gtyovyaddz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtvytbspto.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yongpay.top/Article/details/gtixjsmpgs.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtnruneejb.html

Py:   os.getcwd()
来源：http://dali.hysaishi.cn/Article/details/gtrjcgwako.html

PHP:  getcwd();
来源：http://dali.zhengqikj.top/Article/details/gtwueouadf.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtnpxgrkjq.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtvwkqwjfh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gtdqglgkyp.html

Go:   os.Getwd()
来源：http://dali.hfpthk.cn/Article/details/gtepzrtqli.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpzcfpxz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gttrqqazks.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtiyoijnxq.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtracmtceq.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtouirfkfe.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtazxcggyd.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtqeopujur.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtwjpihipt.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtktwwnixa.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtxgkrdbvn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gtlobpbkpk.html

[M06] 向标准错误输出
来源：http://dali.hammf.cn/Article/details/gtwopxhrvj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtjorpgndi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ivvv.top/Article/details/gtybhdirwc.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtyfxegaqk.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtthoqccdz.html

Java: System.err.println("err")
来源：http://dali.xinyue.icu/Article/details/gtgfybpdyj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gtujuucwat.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtpmptxojh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gtebvlacrm.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtgbtotawf.html

Py:   if __name__ == "__main__":
来源：http://dali.bjfxy.top/Article/details/gtsmlonqio.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zycfv.cn/Article/details/gtwbbhhjte.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtpmtfczec.html

TS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtvtutvmig.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gtaagjbtec.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gtqxcytfza.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhixingplan.top/Article/details/gtfwboilir.html

C#:   static void Main(string[] args)
来源：http://dali.ppjwa.cn/Article/details/gtstyzdsgb.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtigoxvmrb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gtpootdzba.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gthlhktczn.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gtjpawqurz.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtkevdcxnx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gtwdvmsvpu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gteoxlqlhp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtyhtnampn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtstzndxdn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtaocbcpgr.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtrxtrbtxq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtetroyrks.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxuanxn.top/Article/details/gtpngexpxp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtnfkljitd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtqxdfbaik.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtqdbuvleo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gttugzmuld.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtjeifntob.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtnwmvtmnh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj202588.top/Article/details/gtfvoyaxtk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gttwulclzr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtwyugluhy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtgyjwpega.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtjjebvvdm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtdkjssprz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtnejdygak.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtwcceiocq.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtyuqhpkab.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtvjaqwonq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daria6918.cn/Article/details/gtfxtgevbr.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtnjeiwzsk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cdnleiting.top/Article/details/gttkdmflje.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtbbppuirs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtvfetpwmh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gtyotnehxb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gtiikabxlc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtysswopri.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtthtpnlck.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.c1oappe.top/Article/details/gtrnlmsjuw.html

[N04] 斐波那契数列
来源：http://dali.ybcxt.top/Article/details/gtmydnafyo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtdgbdqqwr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtkpyvgtgr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtpfttnyco.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtimqbipgu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtesfuxbhr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtwfxhsrij.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtgicjgxqx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtofpbdxwb.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtrvcxvssh.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gthgmfaphe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtggikefcz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtskvihktz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyvbycglz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gtadoousph.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtthzpigwe.html

Ruby: a.gcd(b)
来源：http://dali.zhoulong.xyz/Article/details/gtmluyfbvs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtpdozusup.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtrizblkzo.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtsetugdgt.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtekduvrga.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtsvwlwefn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtqvypffzc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gttgqpbzks.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtjbeuwady.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtxqermvmd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtfedkmmwz.html

[N07] 两数之和（返回下标）
来源：http://dali.meibo888.top/Article/details/gtljnpqyux.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gtiptczjld.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gtipzxypgr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtniyckbdu.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtpgerrfcr.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gtcgwtkseq.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gthmdprcjj.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtrwoswspr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtfarfjeww.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtfakcoxwc.html

Py:   itertools.permutations(arr)
来源：http://dali.yj20258888.top/Article/details/gtzupqyvnn.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtmsloqaag.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtbunmjatu.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtnplaplqi.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtpdbsgypq.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gtixnsaxlh.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtmdsnmexe.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtbmzitmnb.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtfiypaxej.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtgxktizef.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsicrlava.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtkqfbxirc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgfzy.top/Article/details/gtiogibywl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtkutuwalv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtbnhcgzmn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtrtcidswc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gtbrnflyeb.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtcztsjeul.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtelqadjws.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gthlqbdzqj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hywenlv.cn/Article/details/gttuovmsmm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtpqhykdme.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gtargwcvbn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gtnwlfshak.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gtbqvumkua.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtxurcxqev.html

[N11] 二叉树中序遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtqwftlwbp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gtzlieecvu.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtbdfwvfvh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtmbguwifv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtkuwalkeb.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gteigwcagm.html

Go:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtvsnhveps.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtuzmubtot.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gthhpvztzc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtkhnlwpsd.html


<!-- 参考信息 -->