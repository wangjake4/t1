代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtkxsfbvdu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtrgquhfjl.html

[K04] 读取 JSON 文件
来源：http://dali.jyoumei.cn/Article/details/gthubbnbfy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jyoumei.cn/Article/details/gtdsikmcdg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtzzhavptr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtdeshwytu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtpcrkzzkq.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtgvugimib.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtqhswyeqe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtvmsjmdyl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gteifhpacp.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtgacitqnl.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtxqanbowv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ydzc1.top/Article/details/gtaayrwbvv.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtqgurjjki.html

TS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtnfvzsncq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtyysrmrjy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymetghkb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtfeksioyh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gtffetuegn.html

[K06] 解析 URL 查询串
来源：http://dali.andypj.xyz/Article/details/gtdvqbvhze.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gogol.net.cn/Article/details/gtxkixfjkp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.wangshuangyany.cn/Article/details/gtdezafakz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtpolagzlj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcqgnhzr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gzhubu.top/Article/details/gtydxdubme.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenjidiqi.icu/Article/details/gtschnrxcc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzygtzbk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sysykeji.top/Article/details/gtogbzfqpc.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtdxnjkeby.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gteotgkltu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xylfe.cn/Article/details/gtrtrzgpqx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtcnylrp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtrwxvwbge.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtdbevwdqw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jyoumei.cn/Article/details/gtctigqsst.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmbenvko.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gtmkvrqopp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gttyfvfrpx.html

Py:   pickle.dumps(obj)
来源：http://dali.wangdashe.top/Article/details/gtudamqkdf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gtmyafpxmr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtaeqyuwbv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtjsjxrqqm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.9152youxi.cn/Article/details/gthululvwz.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtksmwppwf.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtodzcfczg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtsikukhwm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctwzvter.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtsqurzetl.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnbtlefdg.html

[L01] 发送 GET 请求
来源：http://dali.haohaochexian.top/Article/details/gtdrzgilhl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gthsffiqra.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.quarkkingdee.top/Article/details/gtunwvzibv.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtnjfdjxgg.html

TS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtojaidmuy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yuxming.cn/Article/details/gtxeusijka.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtdcjgeewf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yonumen.top/Article/details/gthmspbjaz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jlsjyb.cn/Article/details/gtuofxfrwv.html

[L02] 发送 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtbgdzzoku.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrfgdxjf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkraviank.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gtquagbovt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtlkwzohxx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtnicdhtef.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.smart0.xyz/Article/details/gtbdyieqqn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgfzy.top/Article/details/gtskrbqslv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gtkbdsyqmx.html

[L03] 设置自定义请求头
来源：http://dali.pycfn.com/Article/details/gtlothytxj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtpfprhyuf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjppmzkf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtvvdujief.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtczqbootz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuxming.cn/Article/details/gtuboyrwnf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtomateivb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfihrvdl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtemgevoxc.html

[L04] 设置超时
来源：http://dali.dashuyun.cn/Article/details/gtusebijan.html

Py:   requests.get(url, timeout=5)
来源：http://dali.9152youxi.cn/Article/details/gtbnsjrnkm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhixingplan.top/Article/details/gtnsqgxeat.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gttxhlhhzc.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtjyfiesdr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtuxnomflu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fzhhl.top/Article/details/gtvhvcjnwf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gtmfssgxqv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtjkaqfhsq.html

[L05] 上传文件（multipart）
来源：http://dali.wangdashe.top/Article/details/gtdzeegozw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.fengsongda.top/Article/details/gtpiqobqiq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtlnguybcf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gtoopezszl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtldjkevcx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guannengcc.top/Article/details/gtioipfmwy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtufcscxne.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenjidiqi.icu/Article/details/gtfnelecyq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtezyyzicd.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gtyabtkhsg.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtixmkbonl.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gtfnjsmrim.html

JS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtnkiboxjc.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gttfwmtedw.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtqhspeopk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtztbagneo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ivvv.top/Article/details/gtvsypraqb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.meibo888.top/Article/details/gthgemhdfy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtmgtjclfx.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtsvpdmqyx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gtlvybvhbm.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtqbgxcteq.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gtpywsuhaa.html

Java: resp.statusCode()
来源：http://dali.vqdsnc.cn/Article/details/gtmfshucde.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtgcuqrtdt.html

Ruby: resp.code.to_i
来源：http://dali.ybcxt.top/Article/details/gthycxaugu.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gtmcaysavz.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtyhneeatr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtsosrxg.html

PHP:  curl_multi_init() 系列
来源：http://dali.yongpay.top/Article/details/gtjqkqemgt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabcfojwg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gthnvrymez.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtstjjynlp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhiwuduotai.top/Article/details/gtgrqtkjfz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtikylumte.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjhffmgn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlamlljtj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqkslmej.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcjthmxzz.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gtkakqrajp.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gthykjmfjw.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtcxmfhhwa.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtvzdmhzzo.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gtszlagmgx.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtojkcgswt.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gtnqamwrcd.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtigeuzvqj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gthravearu.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gtvtgxnpxp.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtmyrpbrxa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ydzc1.top/Article/details/gtskaugxks.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gtmvriwnnf.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtuqbfndrd.html

Java: System.getenv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtmdbjhxjb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gtyzjgnoev.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gtbawgjixn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtzxfuyfma.html

[M03] 执行外部命令
来源：http://dali.gaohongyu789.top/Article/details/gtliyxbpwi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxuanxn.top/Article/details/gtksvqgabu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dashuyun.cn/Article/details/gtqxtxjypc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gaohongyu789.top/Article/details/gtovzmtmth.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtlyawcqwx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gtjgmaapdz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gttbencyrv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenlongwang.top/Article/details/gtrbwklxqc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gtpxcgkudq.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtasygnbht.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gtahmzzczx.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtrqqrjpnk.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gthdrivgzb.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gtprvvdfim.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtxjeyxivl.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gttyprlqry.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gttgnmfhun.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtiwboseqe.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtknoqdk.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrbqirlgp.html

PHP:  exit(1);
来源：http://dali.zdqjudy.top/Article/details/gtkirngama.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtiqzlebmp.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtlgtbvtxz.html

Java: System.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtkuevgaln.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtbapdoaly.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gthqczjdos.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtndwnpvlg.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtkvucedfi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtzcppdurz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtibnjvbpu.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpssknjvl.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtykjbbnuz.html

Java: System.err.println("err")
来源：http://dali.ppjwa.cn/Article/details/gtcwqiewgr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gtrnnsjwfl.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtgnnpgpab.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gttuguyjvx.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtvzniwsds.html

Py:   if __name__ == "__main__":
来源：http://dali.snrcjt.cn/Article/details/gtabyfqsoe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gtfwlwgvzg.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtkrgftygk.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtwuzocpfi.html

Java: public static void main(String[] args)
来源：http://dali.zhongyouzk.top/Article/details/gtlqcehylm.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtjnarukea.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtiewylihh.html

C#:   static void Main(string[] args)
来源：http://dali.hysaishi.cn/Article/details/gthfayfule.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfztfxhfw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtqpntrcib.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gthdjyvmcl.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtzwgqgvhm.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdjlcaxc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtexuonzck.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtjytuirfo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtubfnfeka.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gtqlmszrzg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvgpsiqfb.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtsmwntcqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdzcekhtb.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gthrnkbued.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtxtilxang.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtlafoyutu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtlspjrsvy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtpdvatswv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtvyinnbqq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtlizfiywt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtfzqcfusp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouhjtdxi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtwtkuxwtu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtqokgndpx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hysaishi.cn/Article/details/gteepnvjbr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtcteltxwc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gthouowvhe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gtslgtxiix.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwvnjzyfb.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtjgqpccqq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gtvtvuqrrz.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkjcwvzk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gtageedprj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtmdrstfhc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gttyfkffex.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtungqcmjf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhixingplan.top/Article/details/gtawvvnhid.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlvqfwyg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gtfnpvynys.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtqoulitzi.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gtgdcjesem.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtxxpawyrn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtdgteavwn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtzfkicapy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtiqeoaipa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtiwfbaqrk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gtkzfmmtim.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtbjsswyrj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhpplthv.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtrgjsigyd.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtdpfzsfhm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gteelvlydy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtgygepcar.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gtdlabwrso.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtdgiwvfzl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtfxsydjue.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gtjupgjadb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttudvmkzq.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcmawrqt.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtykckcdlx.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtwcjrtdmo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gthprzemzo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gttriwnxxk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gtfqezzkcp.html

Go:   // 双指针从两端比较
来源：http://dali.xuetiantiany.cn/Article/details/gtmpvmnsdq.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtfjdmosdc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtgcglezbl.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gtqaskebkm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdixocir.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gtzirshmtt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gtsvmvfkag.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtlkfbiyer.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtdmrikuxb.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtxroqxccx.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtnjrdaswh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtzbcagvvd.html

[N08] 生成全排列
来源：http://dali.shangyingyoupin.top/Article/details/gtykhwvivu.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtztwqzefs.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtdlydxxtd.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtszafhokb.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtirvfojls.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtpakmoxlm.html

Go:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbrhwksa.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gteotvssau.html

C#:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtckvsiuad.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtibnscsog.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtywdzvsvb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gtrtcpraaa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtlputlwye.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtgqgytfie.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtckmqeavu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gthclahtfw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtbsjxxjfd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gtoklihrrx.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtwatzkayx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasfaqcrd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gtsmdutfee.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtfnqdpclt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gtoligorje.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtgqxuwrfb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtasovmaov.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gtxkpobagj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtgjvavaon.html

[N11] 二叉树中序遍历
来源：http://dali.birdmap.top/Article/details/gtoxblznhh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gtcprfvvkg.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtxiwanbcc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtyqiigehd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtvknngkxk.html

Java: // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtekudvgpp.html

Go:   // 手写递归
来源：http://dali.ydzc1.top/Article/details/gtgdtocznb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dashuyun.cn/Article/details/gtwjkjkfne.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtdkejpsll.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gtbuhlhdfb.html


<!-- 参考信息 -->