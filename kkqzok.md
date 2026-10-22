代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtoycmlwnx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.snrcjt.cn/Article/details/gtqhmkkzsn.html

[K04] 读取 JSON 文件
来源：http://dali.nanxuanxn.top/Article/details/gtlzmarzbz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtcazajeol.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gthapuyksv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtkbblibcy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfqjihdu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtogegjiea.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gteqpemcwi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gttoczfjuu.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gtxyymjdld.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gtinhzhgbz.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtnzqzsolx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtngvptakc.html

JS:   structuredClone(obj)
来源：http://dali.fzhhl.top/Article/details/gtllqcrzyl.html

TS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtuueraayd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hfpthk.cn/Article/details/gtbazyypob.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gtdhnhfezr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yuanzhike.top/Article/details/gtfgxdugnm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gttabkylcw.html

[K06] 解析 URL 查询串
来源：http://dali.tian-w.cn/Article/details/gtpzgfwlzu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtwwzhhbew.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hfpthk.cn/Article/details/gtntalczqv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fengsongda.top/Article/details/gtcfavklwf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtsibjynaa.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtouswydzx.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.meibo888.top/Article/details/gtuamcdsdo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gtuijjhldt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtxfoqpbvl.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gtudfjqumk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtsjyutpze.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jyoumei.cn/Article/details/gteerpqvlg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtoupalhcv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gttrgmkxga.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gtpmbmvnsq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtyxuqvfsm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtysernbvb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtxsbcfgfr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fzhhl.top/Article/details/gtzjykhjpn.html

Py:   pickle.dumps(obj)
来源：http://dali.hammf.cn/Article/details/gtozjzvcey.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhoulong.xyz/Article/details/gtvilvrgsi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtjqywkmsr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.havefunace.top/Article/details/gthfesybyb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.fengsongda.top/Article/details/gtggsezjsn.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtbjqjmzbw.html

Ruby: Marshal.dump(obj)
来源：http://dali.guannengcc.top/Article/details/gtsghsxdzg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtknvohajm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmkderoqi.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtefliqgbc.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtijkqovzw.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gtjnasfwsf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.pengpengdd.cyou/Article/details/gteaectuhv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuicezbar.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gtngxsvxbh.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtqjnzyusq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gtwsifirrq.html

Go:   resp, err := http.Get(url)
来源：http://dali.9152youxi.cn/Article/details/gtudzbwzxf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ybcxt.top/Article/details/gtpllhkert.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzmltaui.html

[L02] 发送 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtddihnznm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hywenlv.cn/Article/details/gtsogbqlmf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.fengsongda.top/Article/details/gtxgzgancw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtlfmyjtpb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtrymdynhj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cashguo.top/Article/details/gthlggtodx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zycfv.cn/Article/details/gtyptzhflm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shzxlz.cn/Article/details/gtqbfhmelu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbwjujum.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtbtfdqntx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.tian-w.cn/Article/details/gtmqwrngsf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtrreznamx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gogol.net.cn/Article/details/gthdjnilec.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtqcggzfvf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtpgtisdso.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gthtkafchr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrmxurbk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gtlgfbwxar.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gteevgjlar.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtysjfwjjp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtmlrsftsi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtkucxezja.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gtoyfofksv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtzkejcpdi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gtkchurous.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtrvoxofye.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gtmlqsqhfj.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtvcynxnmi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xuetiantiany.cn/Article/details/gtlmvfccjz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtilfilljb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gtynfvnurt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gtoasrjlsv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtlxrlmdle.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtwqppibgp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtlunkkpif.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtxtwsqukw.html

[L06] 解析响应为 JSON
来源：http://dali.hysaishi.cn/Article/details/gtyukivpth.html

Py:   resp.json()
来源：http://dali.xinyue.icu/Article/details/gtqomeskft.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigfzy.top/Article/details/gtavodzcrb.html

JS:   await resp.json()
来源：http://dali.cashguo.top/Article/details/gtbxxlteiv.html

TS:   await resp.json()
来源：http://dali.kuanghao11.cn/Article/details/gtdwvrawnt.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gtgjwxrkxr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuanzx.com/Article/details/gtljemmaaw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj202588.top/Article/details/gtphashltr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gzhubu.top/Article/details/gthetlnovv.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtvjdqtpfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sufxvd.cn/Article/details/gtyyptxyqt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gtwfcstytl.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtpvenskhb.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gtnykmhjqe.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtbaurxfbw.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtvqflctcw.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtjgqguxhe.html

C#:   (int)resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtnqyxzrkr.html

[L08] 并发请求多个地址
来源：http://dali.shzxlz.cn/Article/details/gtgnzkfxir.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gzhubu.top/Article/details/gthueazxen.html

PHP:  curl_multi_init() 系列
来源：http://dali.jqgfzy.top/Article/details/gtbopfcudt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtarpozqqi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtxiegkjqz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtxwqclrup.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gtehkdhrvq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtelmbrqce.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gthurjeeak.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdkahglbn.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gthpzvjyhs.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzsbdbuk.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtzlpimpgb.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gtnjfktety.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gtjjrfdyfb.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtnqrtjgqz.html

TS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtgzczfbre.html

Java: args 数组（main 方法参数）
来源：http://dali.chenjidiqi.icu/Article/details/gtuontadeb.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gtznzmhgdt.html

Ruby: ARGV
来源：http://dali.cucudq.cn/Article/details/gtfuqflhfp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtlgjmbrvv.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtlsbnyhkc.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtciqisnrp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtqyrbjdnf.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gthlywzkpn.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtzbcfqswq.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtdheesmot.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtfzbhddhc.html

Ruby: ENV["HOME"]
来源：http://dali.snrcjt.cn/Article/details/gtshxqxckd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtkliufvav.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gtbranjcyk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cheryme.top/Article/details/gtjoqwuepx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtekqrwdfd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtgksmaoup.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtfxyqgsai.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtfbupugwb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtgpcxegcs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gteyvwpexx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtgztkhgii.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtobqhwdun.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtmnhlrrgu.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtcawiqaxs.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gteqyaerbr.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gtjygbnyog.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.vqdsnc.cn/Article/details/gtnvnihtrr.html

Go:   os.Getwd()
来源：http://dali.aizwys.cn/Article/details/gtfcaffrub.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtgqcnflem.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtilmcbvpz.html

[M05] 设置退出码
来源：http://dali.jinqigfzy.top/Article/details/gtufrdbmij.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gthtzttxga.html

PHP:  exit(1);
来源：http://dali.shuidangran.top/Article/details/gtvjcmbhyv.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtdjsrvqyl.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtjqksjypb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzmvknazo.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtyigqgoli.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gtmvsmyvdg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtafqzhphi.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtfullxjbp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gtgewxyxjj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtmzcyracw.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtcfkvdpjy.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtatlrpuna.html

Java: System.err.println("err")
来源：http://dali.pycfn.com/Article/details/gtaxtvfrxu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtchjokzpo.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtpmlapjsh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtgxocmopx.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtmwelrqot.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gtmvimjvxt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtmspxalfm.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtbevntotk.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtjlsmrwnp.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtomjksowi.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtjoxlxjuc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtisytpdlv.html

C#:   static void Main(string[] args)
来源：http://dali.yj202588.top/Article/details/gtlpdyguuk.html

[M08] 获取系统与运行时信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrodhldw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtmznbcbqk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtalvizyaa.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtgrgwqyqx.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gtpvgrsjmt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtsyjehwck.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gthwjcqxlx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtrwraegzq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtdnowxzgn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtjhqeruvu.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtgslrcowd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtufiirpub.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gtscgukbjv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtiefgjewj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtpexbqafg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtcomqibhm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtvoefaxtq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtvengtnav.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtzmezjylr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtrutpplbm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtiibqbwic.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ivvv.top/Article/details/gtxjjtowwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtxxxmugmu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.redwolf501.top/Article/details/gtcfcnugob.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtvhojacii.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtmslyeiev.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtzbiokamc.html

Go:   slices.Sort(arr)
来源：http://dali.xylfe.cn/Article/details/gtqdcphcfa.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtqeckztgk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj202588.top/Article/details/gthkobfeeu.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gtjrayvowt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtqobflrdw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtlsehafck.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtohyeqrus.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtcclyxdrb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrcniglm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gtbdsalrgf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtyhhvwxga.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtsytagncw.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtxiuetyto.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmutgarsh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtaojjoydg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtcmxblrhv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtkbejsqst.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtccbnghwr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtixwopdmh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtnqshrtqy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtwarcrvvg.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtnjlswwpa.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzlmnvof.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtvuhttqgw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtucptzhwp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gtowxhntnb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gtsjwyovlx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtsueqarxx.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtgwtnngqi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gtwxaivmrk.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtalxucgeq.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtezziefne.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtvjulvtkj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtuucesurv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtaranyaje.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajitqsfd.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gtvducgzah.html

Ruby: s == s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtpyewnquh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtshbyuprp.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gtxzncxndx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gtomoykgjn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gtwikbltfa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gttgrzmrzy.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gthvaehewj.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gtjkknewdp.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtabjikaxc.html

Ruby: // 手写 Hash
来源：http://dali.yvedp.cn/Article/details/gtirpfwsjo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtdujivapy.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gtopawporq.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtryiihrjy.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gtnmgcplaf.html

JS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtvfknwyks.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtcrjrkklf.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtfhthsnru.html

Go:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gtvszcxnkm.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtippuslcg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtnbnpqhks.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gttnwagbak.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hammf.cn/Article/details/gtpsrzqdht.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtcohwevcc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtizczlkbs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtrhcxboif.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtxnjemrpw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gtevkdrswi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtxxgjqvfn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gtgvfbrrns.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalwfxbhr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenlongwang.top/Article/details/gtukfmdtmn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtrvyeukug.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.birdmap.top/Article/details/gtqdpvokzy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gthkdtjjyl.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gtimowjjor.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtafntwbyn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gtzrggcunu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtbvyeqsdf.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gtdjmiwqyh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtoyafvfta.html

PHP:  // 手写递归函数
来源：http://dali.tianlin.xyz/Article/details/gtombypbwe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsxhvxoo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gthgfijvuh.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtqdnlfuhc.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtezimjfor.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtvyrnuvcp.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtmijwysht.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gtxkahctpc.html


<!-- 参考信息 -->