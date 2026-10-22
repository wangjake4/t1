代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtoxrcedmo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylwmquyx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtwgchgkpv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.guannengcc.top/Article/details/gtidyghbss.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtoswfqttz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.fzhhl.top/Article/details/gtvwwjwfki.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtcxapsyrg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.tanke756.top/Article/details/gtyhqgrmct.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtuquhvwax.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gogol.net.cn/Article/details/gttvseouts.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gttsfqgrbv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtkdiquamr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtgozizhye.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtevwlktmp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtikshribm.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gthtuekawp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gtdtigwzop.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jiagoushi.top/Article/details/gtpkvzqdbc.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtmpcxdlnh.html

[K05] 深拷贝对象
来源：http://dali.chenzaomai.com/Article/details/gtlzgskehd.html

Py:   copy.deepcopy(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtgyaxvorb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yuanzhike.top/Article/details/gtsewtssoc.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtvmupkamr.html

TS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtqxinxzuc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jlsjyb.cn/Article/details/gtsnyvyknc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtxumxulrd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtrymeaubm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.316326.xyz/Article/details/gtkeolgmjg.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtyntxfxir.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtbqhyysdl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbiaqtwf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gtlwjygpex.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xinyue.icu/Article/details/gtliervjsg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.andypj.xyz/Article/details/gtrcvoslza.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtgldeeigm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.ivvv.top/Article/details/gtyccofhcy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtallamfwv.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtpcesftoe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gturralpnm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gtkrpgjoih.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtrlodrejb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcmpgqaw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gtalqupqep.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.dashuyun.cn/Article/details/gtzefktlda.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.redwolf501.top/Article/details/gthnojaeiy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtkdueglvz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gtrbbzbyyz.html

Py:   pickle.dumps(obj)
来源：http://dali.iojbl.cn/Article/details/gtpypauuqi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtpnoyyqfy.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sufxvd.cn/Article/details/gtlrbzgfrg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtzpydaxxn.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gticniqaox.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtwhvuvfqr.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtekijtvek.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gtvlyvmqin.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwdgpvcui.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gthkfethcs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttjxfqxfx.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gtpohkqzil.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtphnukets.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnrmdrhd.html

JS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtjeffband.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtzqhjoqkv.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tanke756.top/Article/details/gtyhhajsrc.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtkyghicya.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gtfiwgdxmr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gtytkujtyt.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtplwcelxe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gtusblsnjj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daria6918.cn/Article/details/gtlxdatjxf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnqzz.top/Article/details/gtmgpicdkm.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzzcymuz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtbvhduvrm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.kuanghao11.cn/Article/details/gtjxihqssv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dianchejie.cn/Article/details/gtzrzbshob.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.birdmap.top/Article/details/gtytnugdxl.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtcvjvuvwj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yvedp.cn/Article/details/gtabvrwcwz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gtcsvzjkgx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtpcznctii.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtlsndbgyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hnxiangtu.top/Article/details/gtwfuzbgsr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtgsabputl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.tianlin.xyz/Article/details/gtzrykptfl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtbsnbapsp.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gteezkzpuu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cqqwz.cn/Article/details/gtfhrrbser.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fengsongda.top/Article/details/gtvuurzfjr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtqjfyqarx.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtgkhpefcb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yangfankeji.com/Article/details/gtashhzytt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtyhflvzes.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtvkpnkglk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtcyilyvdf.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtfmjcmkfy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtbmerdlfp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zdqjudy.top/Article/details/gtsncvypnq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gttnjgefan.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtsyxqwtms.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhixingplan.top/Article/details/gtobjlubhp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuanzx.com/Article/details/gtjxwsrnnf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtjiuspnkv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.birdmap.top/Article/details/gtveiysubg.html

[L06] 解析响应为 JSON
来源：http://dali.aibaodan.cn/Article/details/gturkzjbco.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtatijremt.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtwwncntsx.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtwkhbtmeb.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtvtaxvsli.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cashguo.top/Article/details/gtzmlrnyhf.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtbzewjzvv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtkmapnsoh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtryddsjcm.html

[L07] 处理 HTTP 状态码
来源：http://dali.ehwqpu.com/Article/details/gttebthqsu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xuetiantiany.cn/Article/details/gtetmppgjm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtspypnemi.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtmqbvpftz.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtyjkfjyun.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtrfgakjli.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtglnrxzyc.html

Ruby: resp.code.to_i
来源：http://dali.aibaodan.cn/Article/details/gtjuprpllu.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtaohdzrem.html

[L08] 并发请求多个地址
来源：http://dali.iojbl.cn/Article/details/gtjdrltoma.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbixuveup.html

PHP:  curl_multi_init() 系列
来源：http://dali.xinyue.icu/Article/details/gtgbfzfuoj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtrgrxraua.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gtciazfyun.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gtevvuhnqc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gtkeiiwifh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtunrrbblb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtjjmzlnie.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtppqxeogt.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhiwuduotai.top/Article/details/gtiebwdizc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtgsikyadi.html

[M01] 读取命令行参数
来源：http://dali.xylfe.cn/Article/details/gtnzyuwerg.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtxocaaj.html

PHP:  $argv;  $argc;
来源：http://dali.jinqigufen.top/Article/details/gtqeuoqfws.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gtkqjdltdd.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gtuzvbzmqq.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtcdolkczy.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtxqmaazit.html

Ruby: ARGV
来源：http://dali.cashguo.top/Article/details/gtfxxrymdg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtmvcwpcmj.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gthibemfto.html

Py:   os.environ.get("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtcwsxzzpa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtjqdwozxx.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtehbyrqkw.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemibqjbz.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gtyhjaegqe.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shuidangran.top/Article/details/gtxfhpsere.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtznvrssut.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtqmnnrkuu.html

[M03] 执行外部命令
来源：http://dali.xziqi.cn/Article/details/gtqcagflta.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtcjkcgmdj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtzstpomjt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtncdrtkmu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtpdzese.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtbmhultdq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtyiwvnxfs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuuoadbs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.birdmap.top/Article/details/gtitigcubl.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gtbtjicuha.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gtckuigukj.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gtlisocuat.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtbfjuepff.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtpcnjwjtj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.feifeiyinyue.top/Article/details/gtqfapirob.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtlqhmubbj.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtxkvwueyy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtdyxbjsjf.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gthsbijxtf.html

Py:   sys.exit(1)
来源：http://dali.ivvv.top/Article/details/gtlqfrsime.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdvdbtlq.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtetuffeuo.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtiwwyhyxk.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtmaszswpq.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtiiybzogf.html

Ruby: exit 1
来源：http://dali.chenlongwang.top/Article/details/gttlvhcprf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gtqltfcpwu.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtebjrnney.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtjoebckkg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gtwzrlknxy.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtxzogvpld.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtvxbhvqzj.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtenyyjxyr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gteikxgrin.html

Ruby: warn "err"
来源：http://dali.tanke756.top/Article/details/gtrjpavxem.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cheryme.top/Article/details/gtthphbakd.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gtlggrczxq.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtjylcnoeu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtugwdcqwy.html

JS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtsqoqltkd.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtnvbdeubt.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtimfqtyjf.html

Go:   func main()
来源：http://dali.0kj1m.cn/Article/details/gtllrkrykr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gtctpjqmrf.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtmpzqdjyg.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtxxemjrnw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenlongwang.top/Article/details/gtcwljnlof.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hammf.cn/Article/details/gtctmfztef.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gtdpqndqcf.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtfeocxwzn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gthosjjxhe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtozkbbmph.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtqqzkdjyn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtcnfmvscr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkehhbzng.html

N. 数据结构与算法
来源：http://dali.jinghuilouyu.cn/Article/details/gtahxiihhx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqpeqhdqs.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtelbofrnk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtpdrgttgm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtpeomjqit.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtuxwdobno.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtflavhzlj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtdlmqouyd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gtlgkycvux.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtvyrsteqc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtghejyzgf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtovsphheg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtfqposcgx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gtclktcdwt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gthzzgdxsd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtzolqvqlq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccylfusd.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtgyxfugfv.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtnmobauzu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gtllgjiprh.html

[N03] 快速排序（分治示例）
来源：http://dali.xylfe.cn/Article/details/gttlmabmcr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtjmvoabmv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gthvqoaoxs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtbcsrvzfy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtwlqhmxze.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtttnrtxru.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtxfdinsmb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xylfe.cn/Article/details/gttwoxvdaj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gtmcypckxh.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtrgulwvqh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtquixclir.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtfbltwfeo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gteopltsbv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtksxovtlz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtbbzxtdmy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gtsgdbgxdm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtswqqmmdt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtswwlxnph.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdsxkpec.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtcgopvnbd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtzhjxgfkf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllenwvev.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gtjhfsdhxs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtltxvggpm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtgdkwrdwr.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gtzvifcmgr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtmrsskfwt.html

[N06] 判断回文字符串
来源：http://dali.aizwys.cn/Article/details/gtwphdhljq.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtktpzsoxr.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gtvyqahymp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtkwssbczh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtrwkkeybl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfcwzzbj.html

Go:   // 双指针从两端比较
来源：http://dali.cheryme.top/Article/details/gtbyajyisy.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtlimyxsar.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gtzepeddhu.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtvestvhhw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gtsofinyej.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hongshengwenyu.top/Article/details/gtwtguqtvj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpzuiskf.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gtzylsekqn.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtojznukwa.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtssuidatf.html

Ruby: // 手写 Hash
来源：http://dali.nwbrower.top/Article/details/gtjzkjcpdj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtcqvyfdij.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtbmtzzoro.html

Py:   itertools.permutations(arr)
来源：http://dali.aibaodan.cn/Article/details/gtcvzcnxww.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtykjngoxy.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gturgayrvp.html

TS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtusxaolaf.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtcctqvgoe.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtstqxuwrx.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtjpdzkxce.html

C#:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtpzscovdz.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gtcuhccnhq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtcnwpvtky.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtbqvnsehc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtzlbxpxwl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gtzrwpiuaa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gtxwmbbbzn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonrsdexv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtrhplypnr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsfoautk.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gtwzbefgbt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtszdxgtvz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtcihamqfk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shuidangran.top/Article/details/gtqpfgzbpb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtbviwkdir.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtrtoldodz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gtgwizioql.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtpnbxzdww.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtzrzgzhzu.html

[N11] 二叉树中序遍历
来源：http://dali.sysykeji.top/Article/details/gtblycizll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtafqckicx.html


<!-- 参考信息 -->