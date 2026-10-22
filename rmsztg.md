代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gthcdknndb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gtibkiqunl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtufattryf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.quarkkingdee.top/Article/details/gtejlmdnbf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtolgwilwl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxadiluce.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gtgtkdkblc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ehwqpu.com/Article/details/gtuyujrylk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gticwqnfsh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtcgglkxeh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudicdpxv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gticjcbylz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtlgjwfeit.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvyeuplv.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtdsrcvmpx.html

[K05] 深拷贝对象
来源：http://dali.yueranfly.top/Article/details/gtwkwrkckn.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtjicdnyxb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cheryme.top/Article/details/gtlngchhxc.html

JS:   structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtjwwlfabf.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtdozpcvtb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gtvawpfany.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgfzy.top/Article/details/gtvublqjfq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtgiqmyckf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gthddefcbx.html

[K06] 解析 URL 查询串
来源：http://dali.gzhubu.top/Article/details/gtfgqmzaxb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yongpay.top/Article/details/gttaoywudu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtmgieeydp.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gtdctrkvki.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtonxdzwzw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.snrcjt.cn/Article/details/gtgahrbwlu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtthgukfus.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtmaisoaac.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtgwumtnib.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtgxvfjfdq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtslantwqf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.daxiang520.top/Article/details/gthmgxezur.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtlxkdmxaz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gtyqjzbfar.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtvfqboyjj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtvdisnxti.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.tian-w.cn/Article/details/gtjotozess.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtisoximdo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtmjuirjac.html

Py:   pickle.dumps(obj)
来源：http://dali.tanke756.top/Article/details/gtbqnlqnse.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hnqzz.top/Article/details/gtbwblpuap.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daxiang520.top/Article/details/gthtkpiaft.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gttcglnxun.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtzhjwzbiv.html

Go:   encoding/gob
来源：http://dali.guannengcc.top/Article/details/gtsgvwgxig.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrnmbjgi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtyxoiktjc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmwpmxffz.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gtbyixmzqa.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgojfujvl.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gtykmjizwd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cheryme.top/Article/details/gtdshtamps.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtdakgrwhe.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtxzdlncjg.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtcebbpizt.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xziqi.cn/Article/details/gtoobiyzak.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiynlwlzt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yvedp.cn/Article/details/gtfrfauymy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zdqjudy.top/Article/details/gtnnqmiywq.html

[L02] 发送 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtqacyvoql.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtqcwtzekm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gtopjiysgm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gtuckljncz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtqumdqqms.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtgupalioe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pengpengdd.cyou/Article/details/gtepohuvmd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj202588.top/Article/details/gtusrfgjci.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtsdrdyirx.html

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtvohzstes.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gttspzxogc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtlfozdzej.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gtddnhnoqn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtutyxxihz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.birdmap.top/Article/details/gtwqkawrzz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gtfqvqacwy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gtoomuptlv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtuynmxymv.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gtrtvzqixd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gtuchgjufn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gtbknbaatr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtuzdfudjm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtbfuuvbtp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhengqikj.top/Article/details/gtlzampuau.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gtpwlicvew.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtymcuqoaz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gthwnemcne.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gtekdcdxpp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.redwolf501.top/Article/details/gtqudpmvru.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwmbefio.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrjvuiof.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtspvareqb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gtdulyqmfg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jianghu66.top/Article/details/gtfllvtlbo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yueranfly.top/Article/details/gtreqijcsi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixypnsgy.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gtydnrrqoh.html

Py:   resp.json()
来源：http://dali.yvedp.cn/Article/details/gtxvvlgsbp.html

PHP:  json_decode($body, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtcnujwggo.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtazymizah.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtpkecgbdn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gtsaedomgh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gtetcmgvxx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjislgwbx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj202588.top/Article/details/gtuwuvjacr.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtexfhwjin.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtfumgfbdw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtfiutsejd.html

JS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtnrztklyn.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gttsatjkqe.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtknjjucxc.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gthdojnxfk.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtbfpasysr.html

C#:   (int)resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtldljikwe.html

[L08] 并发请求多个地址
来源：http://dali.svipenyu.cn/Article/details/gtpnpvlmtr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtheyldarj.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtxxouttlq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtdtjuiidx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gtlzcqyejh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gtfqaehgxv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gtxmyxgpyv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gtuxsxqhqj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtxdolzulj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtafovhdnl.html

M. 命令行 / 进程 / 环境
来源：http://dali.cucudq.cn/Article/details/gtpwvlhyij.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarxfoqfu.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtkaeibdby.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gtsnrpxhqj.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gtcalxbeku.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gtsyqdsxgt.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujehzotm.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtowvinyqw.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtrqyxicfp.html

Ruby: ARGV
来源：http://dali.yj20258888.top/Article/details/gtowovetds.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtfijlxapm.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtnwgaxoyr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtqpfspelv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtzjqldupj.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsunahqkj.html

TS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtshbrhevy.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gtwqezzsmo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gtyfpgdwdh.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gtjaovqewj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtkixslasz.html

[M03] 执行外部命令
来源：http://dali.chenlongwang.top/Article/details/gtdatsegsi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gthaafpnps.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtyxlbhttv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gtgcvhymnx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtxhegfgot.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtnzxunvrk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gttwvfihtu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtdgqvjbtp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.meibo888.top/Article/details/gtfmgfprxo.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtqqyyxgeq.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtlwudroas.html

PHP:  getcwd();
来源：http://dali.vqdsnc.cn/Article/details/gtlgrnouxh.html

JS:   process.cwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtaorbphmo.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtjfiwedxg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtclicutty.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gtjlunkahn.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gtwynfkccj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtytpwoaqy.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtpviizawu.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtgzozbsxq.html

PHP:  exit(1);
来源：http://dali.xylfe.cn/Article/details/gtbsvgjxkq.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtguerwepy.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtqjtfcxhk.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtewlfwquv.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtricvhgje.html

Ruby: exit 1
来源：http://dali.chenlongwang.top/Article/details/gtgbyutfyj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtoeilqtci.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtvoymnmfa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtutpruekx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtafsvoktj.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtiburvvba.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gthavhdbch.html

Java: System.err.println("err")
来源：http://dali.hfpthk.cn/Article/details/gtzbjtrzvy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtfcfajktk.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtvuxijmnu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpzwicpf.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntmgowej.html

Py:   if __name__ == "__main__":
来源：http://dali.mhx1999.top/Article/details/gtmqedomuw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gtuwammaec.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtutlghrko.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtmqljlhxk.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtuwbwssri.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gtiungecbe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gtmjemxhmi.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtbccghgpu.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gttxnfamyb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aizwys.cn/Article/details/gtwdlktmqv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhjlfnvi.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtwbljcijx.html

TS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtqgqmvlau.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtiplghulf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtglxemgtn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hongshengwenyu.top/Article/details/gtwtugqjea.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gtexbplnoc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlmllqewn.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gtigxpbewx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtojgkijgi.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtzwresgev.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtneclruew.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gttbjeangd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtcwgxrcnj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnenjptms.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtmtfahqyp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtbthotket.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gthcpxmlap.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtmrtixuix.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gtnixlpmkc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnctfmrq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtivuryejn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtunkwelwa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtzkkebvel.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtdyzowubq.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtoscdsqaq.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddjssqnm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtwxzxiuqs.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtbqjyxcmj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gtbwsukurs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hammf.cn/Article/details/gtvwgvddhl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaoduvbz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gtsnlqtjwm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtxrgpowgb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtjgweyhqh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gttfzpcenw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gtszfsuoka.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtwjujyaar.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtsilglkzy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtbzfdfuxp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtefhryhkf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdlzzvov.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtgkbdgyui.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtscjqrqqp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtooavdkkb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtxpixgtcr.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gtycybtzce.html

Py:   math.gcd(a, b)
来源：http://dali.yueranfly.top/Article/details/gtljabsnes.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtcjmiocnt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtwxvyvrdc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gthwmhqphd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtidyqqxpd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sxryk.cn/Article/details/gtaidcposl.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsmyrzbx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtnhsbwomq.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtlvnteurl.html

Py:   s == s[::-1]
来源：http://dali.gaohongyu789.top/Article/details/gtceqkjioo.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gtbxfqdtgd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtzeemponi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtwqwmwdin.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gtlvokfbbn.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtqmindxvk.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtwmyuvhnn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtfamdwabh.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtcamvzcwu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gtkoegvvqt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gttdjjcfcv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hywenlv.cn/Article/details/gtvzovpryw.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gtwiiwhcnp.html

Java: // 手写 HashMap
来源：http://dali.nanxinkj.top/Article/details/gtkvymspco.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtppdswlwv.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gtmxjbvwbo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtcyzgggpx.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtjgeqafug.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtmgajkpix.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gthkhvaels.html

JS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtkicxrbqq.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtdplzlovv.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtwxcwgshr.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtruqqrkmr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gtxzbgucgm.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtuqzauwah.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtvrhwrtsw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtjgeiofmr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtbrfdxkes.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtvtnikbmi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtibgvknul.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtdiifmfny.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtayjpcmwc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtbdagnozf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gtgjnmdmyr.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gtwduukzba.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtfaxqhsbc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtwbktsbtj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jiagoushi.top/Article/details/gtqkecwind.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gtjevxoikg.html

Java: class Node { int v; Node next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmhvluogt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtdrrkmnem.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangdashe.top/Article/details/gtscqyifha.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtoyxlkizu.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtndbsykrz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtvwqmrtpy.html

PHP:  // 手写递归函数
来源：http://dali.xuanzx.com/Article/details/gtaenxfhnw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtmpmstchx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtqgnmqznw.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtwgxjgobg.html


<!-- 参考信息 -->