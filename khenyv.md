代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtvrfzotbn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gtnforrrpb.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtdzudsqgc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tanke756.top/Article/details/gtqkhpwjef.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shuidangran.top/Article/details/gtuzelhinw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gtfstlbolw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtagsosdjz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmjkksqe.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gtknfhkzzj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.mhx1999.top/Article/details/gtmmapazpf.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jianghu66.top/Article/details/gtdoiwnhfg.html

[K05] 深拷贝对象
来源：http://dali.gotoacloud.top/Article/details/gtqzoqxmst.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtautvclxk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevxldyuj.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtpatdoxeq.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtcfbkfeff.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtbeqhjzyq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtzzwvszmo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtvdprnofe.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.c1oappe.top/Article/details/gttbbunlda.html

[K06] 解析 URL 查询串
来源：http://dali.ivvv.top/Article/details/gtjlsosvvj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhengqikj.top/Article/details/gtaenkcdgw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cashguo.top/Article/details/gtmcyvvsdg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gteaoijnfz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gtbgbcmelq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtqrbdrbxq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtqnpssvwd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtduszaeub.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtrdcznxjp.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtjitmsrdl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtyafuwbbi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtbnxrvaas.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtlfmuabdv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gttytbmyok.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtvqxjscek.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gttlyashjd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yueranfly.top/Article/details/gtpwxpwytk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtyjaudkpm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gtmxfplehi.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gtjxjqtvtk.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtajorzedc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtkjvpnjdk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtlylckeev.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtwkhrrwlp.html

Go:   encoding/gob
来源：http://dali.chenjidiqi.icu/Article/details/gtadvmqkmt.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gthratpjfg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhrloscf.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbpaatybw.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gtszyzsmth.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttopylqwl.html

[L01] 发送 GET 请求
来源：http://dali.pycfn.com/Article/details/gtprnwetdh.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guowangkeji.top/Article/details/gtoeeyjuhc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gtgqprzenk.html

JS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gthxmdnvcb.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtlothobxn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.andypj.xyz/Article/details/gtswvuibzw.html

Go:   resp, err := http.Get(url)
来源：http://dali.tianlin.xyz/Article/details/gtyhudpvwg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavkwheil.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtfnsywskc.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtbxhqdwbm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtzthzogux.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtmmzrsmvf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gtecexevxe.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gttglkxckn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.bjfxy.top/Article/details/gtkyakhuka.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cheryme.top/Article/details/gtwgkhdczy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gtzducejui.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.shuidangran.top/Article/details/gtbxukrzxq.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtwfjzjmpc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gtsuolufwe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtjwbpmppi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shuidangran.top/Article/details/gttccubcrj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gthutcyvmi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcjnirxp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtmjngmksy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtcbinkbqq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gtwblgjyhk.html

[L04] 设置超时
来源：http://dali.smart0.xyz/Article/details/gttxobwbet.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gttdgympah.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gtbiaprooa.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtmanqitrg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtfxfumkay.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtozriuhpm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtrmjmaaog.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gtlehxqtyi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gtjbvuhniv.html

[L05] 上传文件（multipart）
来源：http://dali.aizwys.cn/Article/details/gtccojdgvo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gttkfajase.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzblmeqmz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gtraclhytk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gtahjtntve.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gtzthzqvsd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guowangkeji.top/Article/details/gtzlzqlphj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuetiantiany.cn/Article/details/gtrnyeocxn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sweek.top/Article/details/gtxlfijbej.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtwdzmgfpp.html

Py:   resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtpzzkaprl.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtvdhakckc.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gttmeqlqtk.html

TS:   await resp.json()
来源：http://dali.tian-w.cn/Article/details/gtqqflwfpo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gtfoxaimvq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gtkmoyajty.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guowangkeji.top/Article/details/gtotdlfebe.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xinyue.icu/Article/details/gtijywkflk.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtkognymbe.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj202588.top/Article/details/gtgzxzpbeu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xziqi.cn/Article/details/gthiwopzyb.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gtctjozlcs.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrupcuahh.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtzueemban.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtjjpirbqi.html

Ruby: resp.code.to_i
来源：http://dali.316326.xyz/Article/details/gtrmrncvuw.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gtpnxldktx.html

[L08] 并发请求多个地址
来源：http://dali.hammf.cn/Article/details/gtnwdsgasz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yanxiufei.cn/Article/details/gthtkawami.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtawjaqske.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxvycoxr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gtvyvjqnxw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sweek.top/Article/details/gtgcrkjjxe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.aibaodan.cn/Article/details/gtaudvejbf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtetkyasbd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtyatsmzgb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtjaaosmuw.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gtitgqmani.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbfsbpxvz.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtwibwdije.html

Py:   sys.argv[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtbbjqywbx.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtogeqzozk.html

JS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtshwlyfzs.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtkaoaznve.html

Java: args 数组（main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gtvacpwfek.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtpmldpmji.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gtdcufabag.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtlcecscee.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtnqcbjddq.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gtwlvkgnjh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtnxrboywj.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gtzaidnqdg.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtlfhgotki.html

Java: System.getenv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtytdpmzco.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yongpay.top/Article/details/gtsccitian.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gtwkbbiuat.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gtxsfwdweu.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gtnqfljgwf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gtghpehmhy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtsojzjcpb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gtyrayyiqs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtkekoyffz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtppsldngr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnnyrxza.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtrwdgxrdd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydtfhohm.html

[M04] 获取当前工作目录
来源：http://dali.chenzaomai.com/Article/details/gtcsvsbyjc.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtobnkxoia.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtemyjfxbj.html

JS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtvcgpiuau.html

TS:   process.cwd()
来源：http://dali.havefunace.top/Article/details/gtbvwobboy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtcqhalfgv.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gttaszebeq.html

Ruby: Dir.pwd
来源：http://dali.yanxiufei.cn/Article/details/gtvsukrbcw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtsixwnpup.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtxderhisg.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtodydvejp.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gtptxmocci.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtlvuvalzt.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtupqyuepx.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtfaarnrhw.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtjyxplrct.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfnprvcd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gttcskarjs.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtqfxxxkpe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtcyaptacu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtpwnmzfri.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtzxgepwxk.html

TS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gtnolcnkqj.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtellrjjlw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtviqxvgha.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gtujraylkk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenlongwang.top/Article/details/gtbwcigytm.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtzazjhzal.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtdtgvhzpi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yangfankeji.com/Article/details/gtnyepnquj.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gthgjxqaap.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtoeyjfsyq.html

Java: public static void main(String[] args)
来源：http://dali.jiagoushi.top/Article/details/gtjnhdvpam.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gtynpmadee.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.pengpengdd.cyou/Article/details/gtbtsnozbl.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtuezbmyxk.html

[M08] 获取系统与运行时信息
来源：http://dali.9152youxi.cn/Article/details/gtuhvclold.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtopigzbca.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gtprywvfkx.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtdvfeczcw.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gthsxastlv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhengqikj.top/Article/details/gtvzhcfxrs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvmsuyzi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.smart0.xyz/Article/details/gtvntdnrkw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tianlin.xyz/Article/details/gtonpxhtrx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtitrfztcz.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtshlmatuu.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwjbvdcuu.html

[N01] 二分查找（有序数组）
来源：http://dali.guannengcc.top/Article/details/gtcnlpofkj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtfhhyycvd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtpvlhhiqp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtnewxqizm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gtwdkneqea.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtuovyjolv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtbqzkepvi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtckbclaou.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gthrpphcxb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtfbztddwf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtpeqhrpci.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtelvjjesp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtbbvdzvup.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtzwjaeozu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtoqsmnvci.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtmabsqmfb.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtqxfvmcbl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtgcgyblrn.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtxkvhplfs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtmlxnntfe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtlmxqgyal.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtaqitqmnv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkyfnvzt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gtzlydbehy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiwxfjer.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtnvzlvcnp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtujtztrrx.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtrtrxdznu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gttkvtzvxk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtzmhorixj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtyunwkgjt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtfmhwagxe.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtvrfyejjv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtbenivd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtgaplzdop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtaukyfmte.html

[N05] 最大公约数
来源：http://dali.jqgfzy.top/Article/details/gtkdjlpycn.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtscmupmkj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtltlylsqd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gttujbfgzs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtfedqgusy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gtxztxkxqp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gtmhylnrgd.html

Ruby: a.gcd(b)
来源：http://dali.hysaishi.cn/Article/details/gtzzaibyjp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj202588.top/Article/details/gtielshkmd.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtduxzidck.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gtrcdlgytt.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthtlblcsb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtzsiwkcqk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtampfukqp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ppjwa.cn/Article/details/gtmegcsotb.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtuihmvdma.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gtnbeoqsaw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtndiuqrzz.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gtjotviggz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtcitnbbss.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtorpkeoun.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtxmureaqh.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gtdllrpelu.html

Java: // 手写 HashMap
来源：http://dali.quarkkingdee.top/Article/details/gtkcxwdnpk.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gtkkxhxdmt.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtscbcjvza.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtijvxuhyi.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtxjigpvfu.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gtphgwsinl.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtumppqcsr.html

JS:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtighlybar.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtynsgpsso.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgkmsxas.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtfulexjvr.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtiidmexor.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtpygddtit.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gtbnxogzvy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtzgfwqqme.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtnqcjamhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtxxyvinnx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gtrqhfbzpc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtddikssxf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gtgjmfywly.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtzlmbjlco.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtoyyaatjw.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtmrwooatb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtwdzrllfw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gtfduvrdje.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmpcuaow.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtpojcfdja.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gtezaaqgrd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtkkqhovnt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtofeganyx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtyfbpqver.html

[N11] 二叉树中序遍历
来源：http://dali.c1oappe.top/Article/details/gtziqyappz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nanxuanxn.top/Article/details/gtvfgakzcg.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtkkuiiuxc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtczzrdpwx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtgpfhbnfd.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtyigzxuaq.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtrwimtzoh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtpgtfznsv.html

C#:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtxrcomssd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtrgnbzwyb.html


<!-- 参考信息 -->