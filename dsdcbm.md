代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhengqikj.top/Article/details/gtwqnopuun.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.iojbl.cn/Article/details/gtobbvnbnt.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtubspsjwp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtvhasjoeq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtxkxpkycq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtghewxcpo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxblinxli.html

[K05] 深拷贝对象
来源：http://dali.ybcxt.top/Article/details/gtwlfeqxxm.html

Py:   copy.deepcopy(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtewxedesb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dashuyun.cn/Article/details/gtrvlfbkos.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtsymojaqk.html

TS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtgjooksmt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtgvumbisc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shuidangran.top/Article/details/gtexevtpyr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gtukurvpux.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.bjfxy.top/Article/details/gtkiimmyke.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjccncnvj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtvabictcz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ydzc1.top/Article/details/gttprtnqzy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj202588.top/Article/details/gtfboiiihd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yuxming.cn/Article/details/gtiuhzcize.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gogol.net.cn/Article/details/gtltfyyjxu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtmeayqcmw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gtyjicxcmc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtrzetvjtt.html

[K07] 进制转换
来源：http://dali.hongshengwenyu.top/Article/details/gtreejnqqz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtpqkrsnkn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shuidangran.top/Article/details/gtlgxoujjb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtoxjvxzds.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhoulong.xyz/Article/details/gtgkbcdcuy.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtvztzkzzy.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgfzy.top/Article/details/gtlahlxhys.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pycfn.com/Article/details/gtocjluuxc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtxwhzyvaf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.iojbl.cn/Article/details/gtrblwjkla.html

Py:   pickle.dumps(obj)
来源：http://dali.fengsongda.top/Article/details/gttaxnwodt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aizwys.cn/Article/details/gtdfoekkrj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jqgfzy.top/Article/details/gtljxmuguu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtilofmtqu.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtcmcprjiw.html

Go:   encoding/gob
来源：http://dali.shzxlz.cn/Article/details/gtzjhypnvk.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gthmgfltah.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gtjttcfslx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtgikehkbl.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtkstfrhqu.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqnglaexr.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtcgmukndr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jqgufenzy.top/Article/details/gtsnjwlidn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtukfszkhm.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtfafdsvbg.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtrhqpabxq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gtwinaprln.html

Go:   resp, err := http.Get(url)
来源：http://dali.yj20258.top/Article/details/gtvufzetdl.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gtmpqwfllu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtlrufixyj.html

[L02] 发送 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtekbzgzaw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.chenzaomai.com/Article/details/gtmlyagriy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gtasclmati.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtdyrlofsy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangdashe.top/Article/details/gtbfljouga.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxinkj.top/Article/details/gttsodsyzy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtzpeqpldx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtbecigufj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yj20258.top/Article/details/gttmatkcvi.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtmgeufnfk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gttwueeaak.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj202588.top/Article/details/gtyowgvcvu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gtknyzwbqk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtotgsabyj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtwuwtnvob.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.redwolf501.top/Article/details/gttlcqxuky.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gtddmpybmw.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gtwaftfohy.html

[L04] 设置超时
来源：http://dali.jyoumei.cn/Article/details/gtwihbfqqy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.316326.xyz/Article/details/gtsmlnpgmc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gteidruahh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtnwbdwonm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtwvkqjrbr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxuanxn.top/Article/details/gthstzgibh.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nwbrower.top/Article/details/gtjkkjopcm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.pengpengdd.cyou/Article/details/gtxzeyhzoj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jianghu66.top/Article/details/gtteytpgop.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwqsszwk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinghuilouyu.cn/Article/details/gtzykecjzc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.birdmap.top/Article/details/gttgymlbbp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gteipcajrl.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gtowttccza.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.c1oappe.top/Article/details/gtutdihkuu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtilaqegvo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhengqikj.top/Article/details/gtoclifdxg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gteikgouhd.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigufen.top/Article/details/gtnnmoozka.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtqglhmixg.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtqfosajgw.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtovcpnpoh.html

TS:   await resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtzafdzaog.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gtyworlqlq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cucudq.cn/Article/details/gtllorpgax.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tianlin.xyz/Article/details/gtttklxywv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gthubfsnav.html

[L07] 处理 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtswmicnzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtpbvjhpfi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtbpwhwnpj.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtjmxffrgy.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtpxrybbqf.html

Java: resp.statusCode()
来源：http://dali.zhengqikj.top/Article/details/gtovplzaku.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtimcsycfl.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gttsreglgf.html

C#:   (int)resp.StatusCode
来源：http://dali.hywenlv.cn/Article/details/gtrzqkwvil.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtcdufapyx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fzhhl.top/Article/details/gtwgqegwer.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gtjyolitkm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gthnwkuqwt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtvpmivxwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtzkohvepq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtmbydtglj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sweek.top/Article/details/gtbwxkxaci.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yj20258.top/Article/details/gtvcwkqgdq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsjrnoygn.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtkvxpxeuo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjjrejqcr.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtvyadwsrm.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcvbzrvf.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtwgnlikiu.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtbldpmzsb.html

TS:   process.argv.slice(2)
来源：http://dali.fzhhl.top/Article/details/gtkemajazy.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gtyqqpcutv.html

Go:   os.Args[1:]
来源：http://dali.hnqzz.top/Article/details/gtilkiamwg.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtyzunkaal.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtkmwdelbx.html

[M02] 读取环境变量
来源：http://dali.jiagoushi.top/Article/details/gtdhhqswuw.html

Py:   os.environ.get("HOME")
来源：http://dali.havefunace.top/Article/details/gtgfyyfvrv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.birdmap.top/Article/details/gtxmzaduok.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gtsisgwspc.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtsnhjaynq.html

Java: System.getenv("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtnybspyrf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtibwuzfsn.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gttfyqhuue.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtlwryarss.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtisieakoh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yanxiufei.cn/Article/details/gtuozbwgsx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cqqwz.cn/Article/details/gtpjraqino.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnymhovie.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gtmiuazcax.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yueranfly.top/Article/details/gtmpddvuaq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gtyyznrgrn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.mhx1999.top/Article/details/gtuhczctbq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tianlin.xyz/Article/details/gtmjtxjavu.html

[M04] 获取当前工作目录
来源：http://dali.hongshengwenyu.top/Article/details/gtcnjljzxg.html

Py:   os.getcwd()
来源：http://dali.andypj.xyz/Article/details/gtarvapyxr.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtjjpmzrzy.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtxobdpsqq.html

TS:   process.cwd()
来源：http://dali.nwbrower.top/Article/details/gtpxjjzthv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtdqqmnmst.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gtxbviydjk.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtfsaufekv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hysaishi.cn/Article/details/gtoliocpga.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtxrguaxxg.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtqkqeuhkb.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtjidgtfce.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtbuxawqhj.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtgmpqhiqr.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtjlucbgns.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtwgrnuqex.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gtkohiceow.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtopompeme.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsmndfkw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gtsbwadhoq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gtgibnlsqq.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtaixrkztg.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gthwoklicv.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtivmumwcx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtpnwicazg.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtkjdypyvr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtlgwmnglo.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtddvznjhb.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtzyapnboo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cheryme.top/Article/details/gtjdqnrvgb.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkqdzgrl.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyexpxxh.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gthsdnrmqf.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gturcrstvx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtrgsimrue.html

C#:   static void Main(string[] args)
来源：http://dali.cheryme.top/Article/details/gtwpqzqtgj.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gtfzfxthkp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtycooxqzj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gttddigvqt.html

JS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gtrrbkkwuk.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtvcjxltzk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtfbsexyub.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtfuashxzx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gtnwwuquys.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtxlqhsxjq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtxjlojiwd.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtfihmxitf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjwbiipoo.html

[N01] 二分查找（有序数组）
来源：http://dali.havefunace.top/Article/details/gtjyxqafhq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtscaghedk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtratxltzy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtmhfzmyzz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtswdhgeyb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtgsyzmofu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtvfdlfhok.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthajvrmzp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtubkjdmxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.0kj1m.cn/Article/details/gtwfqnewqq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtqprvrijj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtsiuqfhzp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gttgrefiil.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtzdofzokv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yanxiufei.cn/Article/details/gtmtjcdqrv.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtcmlzdhzo.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtzjynvhzt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gtvwflzgsq.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gtvzolwzfi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.smart0.xyz/Article/details/gttqukzgvb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwmagzpx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gttjabgdzi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtgrdkyfgh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtcyyonxdz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cashguo.top/Article/details/gtppkhivra.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtrjwlsiou.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuaqjcmc.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gtkxfolhhe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtfobwkppk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj202588.top/Article/details/gtsjwpyvte.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gthhqwriko.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtlafbymqi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtfnffnlnw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtaayrvdtb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtudkvrmus.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtqtsmntfa.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gtfulennvj.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gttywzdnlb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtapplases.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqknebixx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtukrocasc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtubxazmwm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gtekkhcwfz.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtykgynzwj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtvhyqemew.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gttquylfvb.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtqydbafsg.html

PHP:  $s === strrev($s);
来源：http://dali.hnqzz.top/Article/details/gtsnnawqwc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtgjbiysti.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtwsotxqfk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbaitziin.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtvkraisoy.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gtnjdztrka.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtgopyzinu.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gtspnswran.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtyjaqagha.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtksvmgwyr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtnbcpfsgz.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gtatpnvaum.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtfjvqftnu.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtogrjucnq.html

Ruby: // 手写 Hash
来源：http://dali.yueranfly.top/Article/details/gtgwxumgnf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtfkgnvdjl.html

[N08] 生成全排列
来源：http://dali.yueranfly.top/Article/details/gtvobhiyrj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtvwcccaik.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbrkpjhy.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtjiqafypl.html

TS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtkpqwifpt.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtpygkiayx.html

Go:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtfjicspbc.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gtihwhutlr.html

C#:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtpvxbciea.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtrmnncbsi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtgczndcww.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtsfhjibon.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtcamtzzhu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ydzc1.top/Article/details/gtlefvexpc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtceqghswd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gtorvedozu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtmgxsplrd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtzfuisusq.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtbcooplsy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gtqvesrvdy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvhamvcll.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtlzkqgqbo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gtgoeifsxb.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtuvrqzngj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yongpay.top/Article/details/gtarsqnawm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hammf.cn/Article/details/gtebauxnkn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtssohxoia.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtdoaqfvyq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtapkcubcn.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtxqbpnujz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtzdinxkvn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtqfvggpqu.html

Java: // 手写递归
来源：http://dali.yj202588.top/Article/details/gtbhaohuxk.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gthnzqrcth.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gtmpdmmthb.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtjyvcjurv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gtzuigrslx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtgbzhbqhw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtjragbjru.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gtvquvovwh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohmlqxvk.html


<!-- 参考信息 -->