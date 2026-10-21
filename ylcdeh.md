代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.aizwys.cn/Article/details/gtitktpgyj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.dashuyun.cn/Article/details/gtpdxjhwgi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtftkezzxl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtmchenfij.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gtoeeeoiht.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxrjmgse.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aibaodan.cn/Article/details/gtgnmfarev.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabiopirw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aibaodan.cn/Article/details/gtimptxorb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xziqi.cn/Article/details/gtgubtuhgv.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gtnfwoqmeb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zdqjudy.top/Article/details/gthgpflnio.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gttqpwewro.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtaexhxvyi.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtkgzgaafd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtjtkakenr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtqsmevhtd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gtmgqmfici.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtblmfxrif.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtxdzacoiq.html

Py:   copy.deepcopy(obj)
来源：http://dali.c1oappe.top/Article/details/gtsttohiap.html

PHP:  unserialize(serialize($obj));
来源：http://dali.wangshuangyany.cn/Article/details/gtvnbueviv.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtczeuazcu.html

TS:   structuredClone(obj)
来源：http://dali.fengsongda.top/Article/details/gtsbfuyuem.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.snrcjt.cn/Article/details/gtrdibpgjc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinqigufen.top/Article/details/gtxwlaymei.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hammf.cn/Article/details/gthrzeqjro.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtahyfspaj.html

[K06] 解析 URL 查询串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcfaexhl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtdnycojin.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gthzuvvbxb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizqqepde.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.andypj.xyz/Article/details/gttgtkukgs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtdzokfsjh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtbflazpvq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gtlonxdpca.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtbwovhntt.html

[K07] 进制转换
来源：http://dali.daxiang520.top/Article/details/gtoyitmiwd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtdbjbgcub.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.andypj.xyz/Article/details/gtkirkihvd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtcxmdznow.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtplnzjezt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gthvlhjwub.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.feifeiyinyue.top/Article/details/gtaodnbaiu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sysykeji.top/Article/details/gtyelkqntg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtezqyvlgn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtzuhjyhst.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gttoatkeyr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jlsjyb.cn/Article/details/gtggnuctkg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtfwoxkvfv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtptpstati.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gtrqcjrwsb.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtmkkjecfc.html

Ruby: Marshal.dump(obj)
来源：http://dali.nwbrower.top/Article/details/gtoarphxhz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.redwolf501.top/Article/details/gtywmitwyt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtzvwtxefd.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gtebtcofba.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtuzjhqfmc.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gtjgjcmqzq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gtuztkqkkq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.wangshuangyany.cn/Article/details/gtxbukhyom.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtyzurwmya.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gteiyjdety.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtvxhbozed.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxlgbygt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gthpprzgvb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gtukcxphoc.html

[L02] 发送 POST JSON
来源：http://dali.ydzc1.top/Article/details/gtkbqxetbh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.snrcjt.cn/Article/details/gtqsbrlbdh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdrkrsqk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtsqpaeqks.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gttmajorzy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.birdmap.top/Article/details/gtwzytnjlb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gtqyqxnfto.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtfztmjawl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guowangkeji.top/Article/details/gtqqvzjqho.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtevaywjff.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gtckrbfesk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtlggivgrl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtrkiwgkry.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gtzvhqicxg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hammf.cn/Article/details/gtbtltdyhz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gtnhwyloeb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtvtxxwedn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gthdarhjdr.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtyinwcfsf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gtkkjkexla.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gtmdmfrxzg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtvysdhvrq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.redwolf501.top/Article/details/gthkmhznta.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gtkdbgnoht.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtkkefndci.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gzhubu.top/Article/details/gtsxrozfub.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gtovjbgtwr.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkompqmhf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gtfcyacuov.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yuanzhike.top/Article/details/gtctwsubbg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gtrcnymuhi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtobqmycix.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gteklxrfyp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gthvzsytrh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gtpilctyjb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xylfe.cn/Article/details/gtafqckdlx.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvtggbfd.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtmtkurfup.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gttrdhjnso.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gtnrolazhu.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtqbfjkaun.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtuepondef.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtkeiuthed.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtrwduixuy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtqbaguiig.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangdashe.top/Article/details/gttnpuansk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daxiang520.top/Article/details/gtoprxwxuj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yanxiufei.cn/Article/details/gtpqapubww.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtkwprtdax.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtknvchdgh.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gtasuvxjoa.html

Go:   resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtjmfaszqg.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gttnwmvubd.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtbmbscjtl.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gtrnnmjnpx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.svipenyu.cn/Article/details/gtpuhacdle.html

PHP:  curl_multi_init() 系列
来源：http://dali.kuanghao11.cn/Article/details/gtjyvjtakq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtfqwothex.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtekixnlan.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuxming.cn/Article/details/gtownljkxx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gtsxxevdmj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtuwnksuvn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtswtmlgxg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtyimnhzvy.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtuhszribt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtaikzhajv.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gthuckxipq.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtfckipzji.html

PHP:  $argv;  $argc;
来源：http://dali.birdmap.top/Article/details/gtcyxwohhu.html

JS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtakydxzjb.html

TS:   process.argv.slice(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiunasyx.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtpjtvjuri.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gtkmdvkzkl.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtudsnvtxa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gtrsweimmq.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gthbzoikfd.html

Py:   os.environ.get("HOME")
来源：http://dali.xziqi.cn/Article/details/gtzqbbykmo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtzvxwipjh.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtmnnkksfe.html

TS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gtjuofeklx.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtosbjowli.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtmngzdgwh.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtjtpbmquj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtelbtmlat.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtlwpzxozj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ehwqpu.com/Article/details/gtbqjxyolk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiyxjozru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtcdlxsaoh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtbkgwzhvg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtgiybfwci.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtimzpdgly.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xinyue.icu/Article/details/gtkvpzclnn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtpmdiolok.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gtugfzohfp.html

Py:   os.getcwd()
来源：http://dali.guowangkeji.top/Article/details/gtrmmgqfhy.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtnmiqfenh.html

JS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtxatvgrxi.html

TS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtdwylxnva.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shuidangran.top/Article/details/gtqpgsnvqq.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtgwqfctzy.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gtemiapjwt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gtrxvwcuct.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtjxipbyyx.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gttycfqmbj.html

PHP:  exit(1);
来源：http://dali.zhongyouzk.top/Article/details/gtviaojpga.html

JS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtjaimjuqp.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtqrqofqqp.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtmccmvjwv.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gtjzpkvclo.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtmsuomuga.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtnlhgvrog.html

[M06] 向标准错误输出
来源：http://dali.zycfv.cn/Article/details/gtwrrnuabc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gttowolmkj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtufawwold.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtatwdnpdl.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtdvngwacy.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gtvcqfiprc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteghbrsty.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gtomxhhrpc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dianchejie.cn/Article/details/gtzcvqlpyi.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtfuiggqkt.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmeiqahf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtcfgveuil.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtmlmfkxmp.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gteuaxjukc.html

Java: public static void main(String[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtmthqxfnv.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtivsizswq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuetiantiany.cn/Article/details/gtbkmubocg.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtxtiekgvh.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvilgejh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtxtftgrxx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtuceaqgzf.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gttfxwtidl.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtrveffkpp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gtmhsibztt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsjvrzoj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtfjemcsfi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gtowzqhvmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzmxoubdj.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtnxcczqci.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtocpqwluk.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtilnvzdpo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtwjmkbocv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtujzslfxq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtjfhdaniy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtgvmxmrpg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gteaopttry.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtpuhyydoi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtgxmofaow.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqeyuifd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gtdmckrekl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtonziqobr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtvawmfhlb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtgscwriyd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtzzghhhil.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.mhx1999.top/Article/details/gtbyylhuvw.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtiuzwxqan.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtugqfyfow.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gthqxmcdea.html

[N03] 快速排序（分治示例）
来源：http://dali.shangyingyoupin.top/Article/details/gtcnjfvkof.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtasdbazcg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtqgipwgqp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtfwlgzomm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gtlfufsqtl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtudyariwu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gtrfzxbnyq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtudtbbzuk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtkdeowhyn.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gtnhnisplc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtrqsxndqa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtdnpmlgwg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtirkyslpk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtszlpagvz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtdyamxtrz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dianchejie.cn/Article/details/gtopvhcdbf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtonrinezf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtokfrzscz.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtcidptxir.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtcrwchzfy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zycfv.cn/Article/details/gtkntwqhno.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.316326.xyz/Article/details/gtanhckooa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtlkdxgrlw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yonumen.top/Article/details/gtzlqeyclb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbuvzjqm.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtrpplpocm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gtwgnweqzx.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gtiryqsuzb.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtzrfhxlpv.html

PHP:  $s === strrev($s);
来源：http://dali.yj202588.top/Article/details/gtkztcflse.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtztczsppw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtaojkdxii.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gtsbicypey.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtpcfqroxb.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gtijqputoh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtqyrohhue.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxzdyiak.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtjykzdrtx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtrsdmndpa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gtfukfynbw.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtpmbnidom.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtitzdafjy.html

Go:   // 手写 map[int]int
来源：http://dali.jlsjyb.cn/Article/details/gtgyamfltg.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtomilafgg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gtojiatntf.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtissxbvaw.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gtiibihoiq.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtwwhenycw.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gttuzrktch.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtmmrotzfi.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtmqwzvoxz.html

Go:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtxlvystya.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gtnnrijecv.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtssszjnsa.html

[N09] 栈与队列
来源：http://dali.jiagoushi.top/Article/details/gteaooctyl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtiewapmmu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtnmjsltxw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gthymnjksh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtnxyyisbi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gtogdtbfvm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gtvoqotrfc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtihlumewt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gtkbylbqcq.html

[N10] 链表节点定义
来源：http://dali.zhiwuduotai.top/Article/details/gtnkdctits.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gtamhqghnh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.guowangkeji.top/Article/details/gtaehmcltz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gtcgguumtn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtdbobxoug.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtctyqdyby.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtxzfcanby.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtmiysubpx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtyafcmadz.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtzfiiyazp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtpyvqkyld.html


<!-- 参考信息 -->