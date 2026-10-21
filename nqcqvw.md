代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gtusuezwsa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtymiupjka.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gthqjflyzx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenzaomai.com/Article/details/gtymyawjmd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtgkslvcrg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nanxinkj.top/Article/details/gtoljumwei.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtnvtiyrpr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gtwipwkgym.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtimjyduwu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtlqygmysl.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gttsekuxxq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtmjysjzng.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj20258888.top/Article/details/gtkbnkefat.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtguzskwgo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gthiwselqw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtkzrurfgx.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtvjsqxwoh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.0kj1m.cn/Article/details/gtsijtrhxi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtlohhieyu.html

[K05] 深拷贝对象
来源：http://dali.gzhubu.top/Article/details/gtqidssnlw.html

Py:   copy.deepcopy(obj)
来源：http://dali.wangdashe.top/Article/details/gtclgzbjdr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtgkeabemb.html

JS:   structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gtrtshrxoo.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtvldudurx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yuxming.cn/Article/details/gtoefkebnu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvddrzabl.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.bjfxy.top/Article/details/gtqptjkpit.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gtattldsfx.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gthlfttrxi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gthytdnehi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gthbprnnoo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtvcznubpg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtndsbrwpx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzucioyhi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtboijxoeq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtqsmwvoaq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtlclwpgxl.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gttlceptig.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtwuzxgedu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtubqnwwot.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtimcpezmu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gtvkdqsxhi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtgbwtlkcb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ydzc1.top/Article/details/gtmrrmsips.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gtfutjacmp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtmcchzeho.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gtedwveecj.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gttzekizga.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtmgxjfbfm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwguiyeu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtcgnhewbg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtafboxbwm.html

Go:   encoding/gob
来源：http://dali.hnxiangtu.top/Article/details/gtjinvmzpj.html

Ruby: Marshal.dump(obj)
来源：http://dali.havefunace.top/Article/details/gtqfwbaagx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtmwpwutzv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcusenark.html

L. 网络请求
来源：http://dali.chenlongwang.top/Article/details/gtmweuvcgb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbzdjiyzx.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtnfqwxzal.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gtpmedceqf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtnxbbujyr.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gtmpczphvm.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtygaxqosi.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtdtaqarrh.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjfxkqxw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gtfajpljpi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtgeyzviem.html

[L02] 发送 POST JSON
来源：http://dali.sufxvd.cn/Article/details/gthtajixcc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtmehmares.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtkershzyv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtyosxwmar.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yangfankeji.com/Article/details/gtntvxdoeb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtaxeipkmn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhixingplan.top/Article/details/gtwnhrnctd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtyidxnumo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtriwgshny.html

[L03] 设置自定义请求头
来源：http://dali.kuanghao11.cn/Article/details/gtfinhbbqo.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtagxzmufq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gtabgcokco.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtbicvjfpu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtxditygkz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.9152youxi.cn/Article/details/gtpvpfglws.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtsehagrtb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hysaishi.cn/Article/details/gtieyoojfp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gthteuygnt.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtoyaauatm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgufenzy.top/Article/details/gtqkregord.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtnpycccsw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtdtvttxzf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtdjzajahf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtoiztyzdu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.birdmap.top/Article/details/gtuqmyfaqd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xylfe.cn/Article/details/gticjtqway.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtayeuxkkj.html

[L05] 上传文件（multipart）
来源：http://dali.snrcjt.cn/Article/details/gtvlrrvxvq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gtpwvdzwur.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtmnvqxxni.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gtgtvvnkkz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtlsaituay.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtedrbetzl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenlongwang.top/Article/details/gtdgkyimvj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ydzc1.top/Article/details/gtwtzyhjyn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gtgwfzjvdb.html

[L06] 解析响应为 JSON
来源：http://dali.zhoulong.xyz/Article/details/gtehqdjrno.html

Py:   resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtwwzbogxu.html

PHP:  json_decode($body, true);
来源：http://dali.zhixingplan.top/Article/details/gtqtdfyfls.html

JS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gtyvgamcnc.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gteyrzecaw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gtnkcnsklw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxuanxn.top/Article/details/gtgeurzxbp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtglssahur.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hfpthk.cn/Article/details/gtbhjoyzed.html

[L07] 处理 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gtnsxxqbgo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gtkqpnyhfx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gtftjljhge.html

JS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtyarykkpm.html

TS:   resp.ok;  resp.status
来源：http://dali.yuanzhike.top/Article/details/gtpclipvbw.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtnuvxfcxz.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtckmujywd.html

Ruby: resp.code.to_i
来源：http://dali.pycfn.com/Article/details/gtsurchwsy.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gtrbtvnmef.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtdbqgrwnv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gtrukitpdk.html

PHP:  curl_multi_init() 系列
来源：http://dali.dianchejie.cn/Article/details/gtiytmnilu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtshbysfys.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gttvyzfsvn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gthhcyzaav.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtbudunmew.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gtxxidtyht.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daria6918.cn/Article/details/gtonwiopnl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtshktumxu.html

M. 命令行 / 进程 / 环境
来源：http://dali.cdnleiting.top/Article/details/gtlbidibek.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrsntvofe.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtexvyrevm.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtvxobbfpq.html

PHP:  $argv;  $argc;
来源：http://dali.svipenyu.cn/Article/details/gtxljepwoc.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtmwwwwwox.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtiryxmgxy.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxackrmd.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gteptwjjjn.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtplvmlkdn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.havefunace.top/Article/details/gtjntydenp.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtbtuzklmy.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtgavcktfo.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtfnahcjtp.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtsqkxsiic.html

TS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtyosiicva.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmezkjdwm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtrgdqugcd.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtezqdnzdy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtqalwkozt.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtownndgji.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtoosqiypq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gtcptctqmk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gtharyvdeu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gthdxirluv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtkmckllce.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.smart0.xyz/Article/details/gtdsrftaof.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkzgkcib.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yangfankeji.com/Article/details/gtkcmuuhmt.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gtsslejwcj.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gtmizoyayj.html

PHP:  getcwd();
来源：http://dali.kuanghao11.cn/Article/details/gttqyinarm.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtabxvwogg.html

TS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtpzxmhdsh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gthpgfjkab.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gtdriysfsm.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtluiuvxzn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtqbhtuvth.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtqriaejll.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtirjjmlvv.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtjkjjzhbl.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtpynoyfip.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gtwjssyhzf.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtyumscfck.html

Go:   os.Exit(1)
来源：http://dali.birdmap.top/Article/details/gtydgoqjzo.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtbklakyul.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gtvckvlaec.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gtsnkzunsd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtalzjifai.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtzytvmlta.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtqdrtjneg.html

TS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtsjivymyz.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gtnjqzmlvp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shzxlz.cn/Article/details/gtvfkpqbdc.html

Ruby: warn "err"
来源：http://dali.redwolf501.top/Article/details/gtbpjyahji.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtmrgyxgta.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gthjkfeknx.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtzuyxasia.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gtbjtqeggk.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gttrgahtof.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtivdkrcxm.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtqgjqkzar.html

Go:   func main()
来源：http://dali.jyoumei.cn/Article/details/gtjfcqnebl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gtrveaomly.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtdrbvavam.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtqahaikre.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gttfjpzoea.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guowangkeji.top/Article/details/gtydpvbtei.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtjuhudxya.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtnbonqloj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtegediwny.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gterchbiet.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gtyxmiqnpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pengpengdd.cyou/Article/details/gtkdkewkpm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwjozucuf.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtkmzxjkqa.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtuimgwpyl.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtaotyfogh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtggdmseqa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258.top/Article/details/gtbehehomo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtcetofqku.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtuilqknjn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtbkzljlee.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtmchfdeuf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.bjfxy.top/Article/details/gtejubibro.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtbfntxhiu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtopffbvrv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtlrycpvak.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gttojvzrlp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtfpmarapk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtsglmthwr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yueranfly.top/Article/details/gtfjkxigdw.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtnjvucxoc.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtpxmpecpq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ppjwa.cn/Article/details/gtwrjftkan.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtjnbyafax.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtttzxileu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gtzvmivrbc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gtmskyzrqb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gteuqpvtdx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynvmsqiv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtklklusnx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gtmkcskxdg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxuanxn.top/Article/details/gtycqvkhir.html

[N04] 斐波那契数列
来源：http://dali.wangshuangyany.cn/Article/details/gtkfzncito.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtgfznvjww.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtxthgcbqe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtuzcqubfs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtkggawnkn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtcufykbhj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtnpklyphd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtoyecexeh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtofczaewy.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gtwjowdlrq.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gtpyeyqnfn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtodquhbpr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtgwmlhqdm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtqgtdvjcr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gtqnygwuyi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxadtlgyi.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtjdzwhsfw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtgqpkkbso.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtjgvpilri.html

Py:   s == s[::-1]
来源：http://dali.zycfv.cn/Article/details/gtzylnnslj.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtmqxywugl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gttfntyemw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtveoyrkev.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jiagoushi.top/Article/details/gtvbypcnai.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtmysoexop.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gtdpubwqqt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gtiqgksepk.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtvlkegjjm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gtlfrzjgoi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtugkadbzd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtkwdxbdkj.html

TS:   // 手写 Map<string, number>
来源：http://dali.0kj1m.cn/Article/details/gtmzvtgvvn.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtyxyucgsk.html

Go:   // 手写 map[int]int
来源：http://dali.gzhubu.top/Article/details/gtqvumxqav.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtcdetegfl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gtukrilcne.html

[N08] 生成全排列
来源：http://dali.shanyushiyangtech.top/Article/details/gtlclpobgv.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtvnwpgret.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gtvwkxuumr.html

JS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtfojisdow.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtaraalrci.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtumaapfvj.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtkvpyjtsx.html

Ruby: arr.permutation.to_a
来源：http://dali.c1oappe.top/Article/details/gtxlvwxdjp.html

C#:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtzzbsweut.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gtufeimodq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtsdadiqhv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtssoanvxg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtrmabxmwp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtvsvyejub.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtkncrejsy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtwufqblsx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtjsnvvudd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtvzcckywf.html

[N10] 链表节点定义
来源：http://dali.shzxlz.cn/Article/details/gtgaiokbfi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtasrrwczo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ppjwa.cn/Article/details/gtazgocoaw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtnttiqrif.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gtuwsksmaf.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gtriccoavf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtkprjrroj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gthrgcrnxg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdojrcevq.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtzzjyqwzu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gtlqkhpqyu.html


<!-- 参考信息 -->