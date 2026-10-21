代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.gaohongyu789.top/Article/details/gtpgzazvxa.html

Py:   json.loads(s)
来源：http://dali.andypj.xyz/Article/details/gtbnrthwbz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jyoumei.cn/Article/details/gtfiatuytd.html

JS:   JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvqzdaivm.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtabalhoej.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtdjbipwbb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shangyingyoupin.top/Article/details/gtjpvrrebz.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtswbfoqsx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtfvltudin.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejgcwjvl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtmpedpmlz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtucasqcgk.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtrriovigg.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtioytxptk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfmkgjspm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.0kj1m.cn/Article/details/gthysjlate.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.dianchejie.cn/Article/details/gtbfkqmibs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hammf.cn/Article/details/gtxyfxrvwn.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyxizduud.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gtugxlybjj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tanke756.top/Article/details/gticuyuqki.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtbhkueoai.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.wangshuangyany.cn/Article/details/gtwnzyfjlk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxertzxkj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yanxiufei.cn/Article/details/gtighpsrww.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yonumen.top/Article/details/gtbpxsjuqj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtkvaytwbx.html

[K05] 深拷贝对象
来源：http://dali.sxryk.cn/Article/details/gtciopgwrh.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtfrmckejz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hnxiangtu.top/Article/details/gtvirkgvfx.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtmqsvztho.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtddtydvhr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gtpmjcflqn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gtwphbisjw.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.kuanghao11.cn/Article/details/gtaianvqky.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtfblvvlrh.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtiglhdzqb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.svipenyu.cn/Article/details/gtirgcxjhz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgklyqmkx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtbngivyfj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtdtatpqry.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtgiinnzlh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtonumumnv.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtvarjxkch.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtreyitdss.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtlxwqmpwo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtwmwbpesg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gtrzzcystd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gtpopjqhcz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtsdevgfff.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfnkgnvu.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gtwrypxdpk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtgbcajzpr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtvlrbywbh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtjhidmmwg.html

Py:   pickle.dumps(obj)
来源：http://dali.bjfxy.top/Article/details/gtzqdlyymr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gtnjmaoktq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtzoexevir.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ydzc1.top/Article/details/gtlqsdzbhf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shanyushiyangtech.top/Article/details/gthbfdqasq.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gtmmquaqmv.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj20258.top/Article/details/gtkmgaecbs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtbfgppryo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gttnghsbws.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtifgxsqlv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtchkigfjz.html

[L01] 发送 GET 请求
来源：http://dali.andypj.xyz/Article/details/gtsjxnloxz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtpapsiidv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258.top/Article/details/gttineqofa.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtfzjhbora.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gtldpeskbz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtrswktlht.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtherjtmee.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cashguo.top/Article/details/gtksvsbcuf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gaohongyu789.top/Article/details/gtkianrcci.html

[L02] 发送 POST JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtsimhyaai.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtkvfvcabr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gtmzizunmi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtafuzedam.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gtinqhhuzf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gtkkhdjals.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.hammf.cn/Article/details/gtlkekfdhd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.quarkkingdee.top/Article/details/gtrcictyhj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.iojbl.cn/Article/details/gtgmqiazqh.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gtivdkojuu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyjzexbw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.quarkkingdee.top/Article/details/gtxnfwyvfw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shzxlz.cn/Article/details/gtytzvfvmw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtkbnfvhuv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gtxaiatujk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtfzkfpcau.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj202588.top/Article/details/gtgbjlcwxv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtghidvxoo.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtsreotzvm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guannengcc.top/Article/details/gtgoovkiwh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtogjlidas.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.havefunace.top/Article/details/gtmjjsdkvm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tian-w.cn/Article/details/gtetspiwut.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zdqjudy.top/Article/details/gtfbvddvpl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.daxiang520.top/Article/details/gtrzuzhacy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtjsoylqqo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yanxiufei.cn/Article/details/gtkqxohswc.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqdnbgkl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gtsrasxssv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gtrgkjiqmh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtmovvbznr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtlavaxpmq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtvylyyvss.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.guannengcc.top/Article/details/gtgsahlosa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.316326.xyz/Article/details/gtffeabkhi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.mhx1999.top/Article/details/gtkepqrzgv.html

[L06] 解析响应为 JSON
来源：http://dali.bjfxy.top/Article/details/gtwxdlcusq.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gterqjfhry.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gtplntwucf.html

JS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gttnbwpzwc.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtfywulshl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gtciqcufoq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gtafkescim.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtlduxaryy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtxlhyxtvz.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gthdzhzbtu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtvaimqkzr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtfreqfhde.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtzcondppg.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhkbgqea.html

Java: resp.statusCode()
来源：http://dali.andypj.xyz/Article/details/gtlngqzkov.html

Go:   resp.StatusCode
来源：http://dali.9152youxi.cn/Article/details/gtmwjogmfi.html

Ruby: resp.code.to_i
来源：http://dali.wangdashe.top/Article/details/gtsjjzohfx.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtiuuzfiml.html

[L08] 并发请求多个地址
来源：http://dali.guowangkeji.top/Article/details/gtduyagkss.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtnzstzlxi.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtzuzizfjm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gtglmvcrfx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtmtxwyfja.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gtusfxhtvl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtusnggupa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xylfe.cn/Article/details/gtaaffrkch.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gogol.net.cn/Article/details/gtibdpkwlw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtufyhsdfo.html

M. 命令行 / 进程 / 环境
来源：http://dali.dianchejie.cn/Article/details/gtnblyntvd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrgdmwroi.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtakvwjjzh.html

Py:   sys.argv[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtmqdpwina.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gtdxylhmgy.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtjyxfyhcx.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gtcehfumyj.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtvlattgtt.html

Go:   os.Args[1:]
来源：http://dali.hammf.cn/Article/details/gtvfstbqod.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocierjnp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dashuyun.cn/Article/details/gtnoldibmc.html

[M02] 读取环境变量
来源：http://dali.smart0.xyz/Article/details/gtwzpbxsvv.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gtfiqnuqgu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yongpay.top/Article/details/gtzwrixkqw.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtjnggqtyq.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtdnzijilq.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtacjjeqgc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtukvzgfdm.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtsqbeiuug.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtatrpvezn.html

[M03] 执行外部命令
来源：http://dali.316326.xyz/Article/details/gtawapsdan.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtrcxndlca.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.0kj1m.cn/Article/details/gtyknlmkfy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtnpjihalh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gtbmumgazs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gttulvbjsm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sweek.top/Article/details/gtefbbuskb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtnqhtxsge.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtnlemttrr.html

[M04] 获取当前工作目录
来源：http://dali.tianlin.xyz/Article/details/gtjtwgobna.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gtypicfwyd.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtwtascmbu.html

JS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gtzvskjwwb.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtciivbwwf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxinkj.top/Article/details/gtenuwqotl.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtykldwwvw.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gttcaktrog.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gtooehpmfh.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtdqfvmydv.html

Py:   sys.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtyeruwolq.html

PHP:  exit(1);
来源：http://dali.ydzc1.top/Article/details/gtoeqcnqrn.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtayafzlra.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtzwurrajp.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtrvzcdhvv.html

Go:   os.Exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtwzpeptlf.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gtxnksnzdg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtpxlmmvic.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtxpimaxrj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtmgviwvxd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gtbrlxisuc.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtuqvuldio.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtjintbmrd.html

Java: System.err.println("err")
来源：http://dali.hywenlv.cn/Article/details/gtdhkszxaf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gtutpftjuv.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtandglpfh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gtitjoomhv.html

[M07] 判断是否为主入口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyffrwgu.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtliuivwbn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoxujrly.html

JS:   require.main === module
来源：http://dali.yj202588.top/Article/details/gtmcsthozu.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtkclamicj.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtwaxwfzir.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gttmtziijo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtnaesytda.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtmrcqjzao.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtlubiroyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtetfpshfn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqiiucqzh.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtocstolqy.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtsijngtyj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtnzrpaucb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtidfekumy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gtopoyhjbb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtsgbvfazd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtftssafzz.html

N. 数据结构与算法
来源：http://dali.xziqi.cn/Article/details/gtlsefbotm.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtazueihwg.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtetlrvnvr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtfmdzdjep.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtkmshfceg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtupskzyjp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtqlxhijxu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtldtnnnif.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtdwnpqsun.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gthpgyhqeq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtalqtkdhh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtmvtedhpt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gtbmnsbpce.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqybjsnct.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtynishdes.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtoedvxpgb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gthwoygtac.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndlaopyu.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtrabbewxz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdogydncz.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtnmglpulc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenjidiqi.icu/Article/details/gtveyxtvgy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gtsfhhylao.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtmnaszgzk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtqglubrss.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtqxmiqxwl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gtfwixbthh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtqbsqewqr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gtqswtvhcb.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtcszhdruq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtfhhrrwyn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtaxjtbzph.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtffsohvhf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtfajmeezy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtmroeafmc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hammf.cn/Article/details/gtggsrpkvy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtbkhlvuxi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtionerded.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtexcpgxcj.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtxsihocjj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtacdhimoe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtqehsbwni.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtizpqtjjr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtixgftfge.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gtrkijcyjw.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtcmdaiuaw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gttjfotbzs.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtunlnlxoa.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtbikstyim.html

PHP:  $s === strrev($s);
来源：http://dali.jqgufenzy.top/Article/details/gtjqvbsnyt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtfcmctxqr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohongzpy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjtmljlv.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gtccwirifr.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtgsoraimm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtjhkzufqu.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtlydvmlum.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtzloulosg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtgekxrhqr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtobgpgntd.html

TS:   // 手写 Map<string, number>
来源：http://dali.sysykeji.top/Article/details/gtazugvcze.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gthvgzpcgg.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtcgbarldx.html

Ruby: // 手写 Hash
来源：http://dali.kuanghao11.cn/Article/details/gtedbddtmx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuanzx.com/Article/details/gtjrszuxgo.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtllnesaji.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtzhynezat.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtknphrely.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtcwhzjkbo.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtcgdmajhz.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtvkuwypux.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtarglixsy.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gtaozknxpc.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtorevsvef.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtkzpsgybr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daxiang520.top/Article/details/gthmvojuon.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gttorworfs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtvcnwgral.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gtyskqekms.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtlfvhqryb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gtrmzsixul.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtlpkbiuiw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.0kj1m.cn/Article/details/gtpnasdxkz.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdhzmnjw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gtzidyxypz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtgdbsusaw.html


<!-- 参考信息 -->