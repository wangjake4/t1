代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gteliwgpcg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gogol.net.cn/Article/details/gttxaqddfh.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtmtsvulsj.html

Ruby: JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gtmxrzmsoz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtyxqrqmna.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtwhehirxd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aizwys.cn/Article/details/gttokfnzul.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jiagoushi.top/Article/details/gtmmrzeelt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.316326.xyz/Article/details/gtrvhuwsit.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtnqzzamyl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.nanxinkj.top/Article/details/gtieveqsue.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtxnbzvnqx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guannengcc.top/Article/details/gtjmpbtzve.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxgakcnw.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gtbhsajccv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gtuqkzdvyx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cdnleiting.top/Article/details/gtsvjixhrx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtuiwlrqiz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gthjlmmdhp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pycfn.com/Article/details/gtycdbjpis.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtwpcrgzoi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtokmmopep.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnxiangtu.top/Article/details/gtfmhqzhgy.html

[K05] 深拷贝对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjbcyvfq.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtpboyvlak.html

PHP:  unserialize(serialize($obj));
来源：http://dali.nwbrower.top/Article/details/gtcdbykdot.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtkjfevsog.html

TS:   structuredClone(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmaafojrn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvblrawl.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj20258888.top/Article/details/gtmyzvxral.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtyfmrrfiu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtykswudqo.html

[K06] 解析 URL 查询串
来源：http://dali.haohaochexian.top/Article/details/gtaqgefluy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtudxbpapc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gtzpxraxdo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gtluzlkkjw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hysaishi.cn/Article/details/gtdwxsqczc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.daria6918.cn/Article/details/gtkfdzstux.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gthxusqfbm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtannbzodb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtuxqoipzr.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtwgsusxph.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtsgvdwazx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtqwrmmllu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtlksdvkjp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtgebkwtml.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtthnqmdfq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ehwqpu.com/Article/details/gtvpdjraxa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dashuyun.cn/Article/details/gtrrttfuxj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtyxcwlxuw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hfpthk.cn/Article/details/gtpcyzdmiw.html

Py:   pickle.dumps(obj)
来源：http://dali.vqdsnc.cn/Article/details/gteuttnrwh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtwaopykmn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gturhznwrc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtejeikehs.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtkhjpteca.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtguogkxhx.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcprjhirz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtsxflbzxb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthlcebocp.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtthlyojbj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtskgttdws.html

[L01] 发送 GET 请求
来源：http://dali.jianghu66.top/Article/details/gtfuacrlns.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xylfe.cn/Article/details/gtgwprukds.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gtwritvlgm.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtyjfyukvd.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtxyrluuli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sysykeji.top/Article/details/gtapgrevmt.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gtuamijprf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.fzhhl.top/Article/details/gtwskoolpi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtytgtfsfc.html

[L02] 发送 POST JSON
来源：http://dali.yj20258.top/Article/details/gtgqjnwzmi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtexdravlz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cashguo.top/Article/details/gteomjvelb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gtpyelxsgo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtvscadwsr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtufjaopxf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gtqtlioukd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ybcxt.top/Article/details/gtpsqdhhjm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtcidltyfz.html

[L03] 设置自定义请求头
来源：http://dali.sufxvd.cn/Article/details/gtsfcalvdz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cqqwz.cn/Article/details/gtagvfzhic.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhoulong.xyz/Article/details/gtpfooqtei.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daria6918.cn/Article/details/gtxfosewon.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtamlpccdl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.havefunace.top/Article/details/gtlptirhik.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtoiyvankz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtbaiupyru.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jianghu66.top/Article/details/gtupvuzlhe.html

[L04] 设置超时
来源：http://dali.9152youxi.cn/Article/details/gtwsnhpbal.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtbhpqpkfk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxccwejy.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtzxzgmojm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtouwxavii.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gteiutctny.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.vqdsnc.cn/Article/details/gtlonmtylv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sufxvd.cn/Article/details/gtmqpimjuk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gzhubu.top/Article/details/gtdhuyviil.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gtekivprgk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ehwqpu.com/Article/details/gtubyloexp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtiufuawcr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.redwolf501.top/Article/details/gtrcfmbjtz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtjymnkyni.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtusmhlwvv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedlepwrq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtihagxpdw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsautqcap.html

[L06] 解析响应为 JSON
来源：http://dali.kuanghao11.cn/Article/details/gtexpuiqvj.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtsmtrofcx.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtxqfbqvzk.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtslurhkkx.html

TS:   await resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtrflnrkih.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sweek.top/Article/details/gtobuqhyzl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtmtcnnjgf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtarbpegac.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtwlsiqvyr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtrahdapzp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuauzdnmg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtsshsfgyp.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gteowsbiqi.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtiaahcovl.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gtcudfbmwc.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtbaiquzey.html

Ruby: resp.code.to_i
来源：http://dali.hammf.cn/Article/details/gtmiczwcib.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvujwxdd.html

[L08] 并发请求多个地址
来源：http://dali.gzhubu.top/Article/details/gttxwzehzc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cdnleiting.top/Article/details/gtwbvyyata.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gtufujjclm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtrtyhfbst.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtdfqkwqrv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xylfe.cn/Article/details/gtumgckjhw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.feifeiyinyue.top/Article/details/gtgajveflh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtvakrbljm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtikbjyngy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkivxtfam.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gtvcbgpcxs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdpohhtit.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gtjpgccxtg.html

Py:   sys.argv[1:]
来源：http://dali.ehwqpu.com/Article/details/gtgvfdgriw.html

PHP:  $argv;  $argc;
来源：http://dali.316326.xyz/Article/details/gteqmvfmos.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtpixavnhl.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gtjbljtfof.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtcoazutdq.html

Go:   os.Args[1:]
来源：http://dali.ybcxt.top/Article/details/gtgpyksqbg.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gtelvmggti.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fengsongda.top/Article/details/gtyrvadliy.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtvkgenysm.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtmgywapno.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtswrjsdbu.html

JS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtjhhmgojk.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gteifbovqw.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtficxnatm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtiigryeuk.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtrzqsxnhh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gtsjtslgdp.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtqylmiote.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gthctxwnkx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gtmlvnncth.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtlytfuxar.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwgahhll.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtbuttzrdi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dianchejie.cn/Article/details/gtvvjnerwk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtacoekhtv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtzitonxvr.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtgdnljgxj.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtwwnyqham.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gthecemyin.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gthupnuvah.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gtembwpmlg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuxming.cn/Article/details/gtxupbsulb.html

Go:   os.Getwd()
来源：http://dali.ydzc1.top/Article/details/gthgiebjek.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtupdduhdz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtlyxwumwa.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtexwxwezh.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtlcdgrcho.html

PHP:  exit(1);
来源：http://dali.yj202588.top/Article/details/gtdpkoqsbs.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtyzocyjus.html

TS:   process.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtjyqoifbc.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtneietuay.html

Go:   os.Exit(1)
来源：http://dali.wangdashe.top/Article/details/gtymlfwgri.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtudaytnxm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guannengcc.top/Article/details/gtojmutqab.html

[M06] 向标准错误输出
来源：http://dali.c1oappe.top/Article/details/gtjwtahiuy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtndfvsrvv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtxprgwllx.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtrbhhsznh.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtfvxaetkb.html

Java: System.err.println("err")
来源：http://dali.sxryk.cn/Article/details/gtzdmuyujc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtphfpafqh.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gtelrkluoz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtaiwcftdp.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtptewnowo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtqycjsacj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtdgxkkxav.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gtdvztxppu.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gteonkdyxc.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gtcxjsrqyq.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gtiyyezmfa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gtdacqnonm.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtcrwsmpqx.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gtlfkkypxq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstdnfehu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtvbtpxtwl.html

JS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gtgrilombq.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtndnalrfe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtozxephjq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gtmbxnpibk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gtrjnuxbne.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.dianchejie.cn/Article/details/gtwpffnzgc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gteenwgwyf.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtbkezqnpm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvndturwk.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gtofpofzhb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gthztszsgc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtnerkusrp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtbnedqqcx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtgksovlhr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtuzodwufj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtlttpcnnf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtokdkiccn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrjzoves.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gthcxlcxpt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtqftrkknr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gtgsqdmdgb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtafimimix.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtyquwkdwu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ydzc1.top/Article/details/gtlozuuxfc.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtvgiryoaz.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtxoyegtcy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzalxczbi.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtkbexhvzg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtpiggnoxm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtynrcmgkl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtdoqujihq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrruuxvwy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gtpyjawjxl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtnbkjvpxm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtlluqfeos.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtzcohiwvq.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtpsfiryku.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gtpzmvxcwx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtfcqczthr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtdhggmkhy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gteebxbtba.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtaasunwca.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtyrvttfdq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtgxebjwei.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtzfcsdcho.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gtjwgpkkra.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gttqqlpanc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gtdgykhhxu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtsbhqoick.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzlvwpnm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtehvvxprf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtealoyzhh.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gtszptsbgm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtmmuxoigw.html

[N06] 判断回文字符串
来源：http://dali.0kj1m.cn/Article/details/gtmokqmrog.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtvirlyvyb.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gttioqgxag.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtgzulxijy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtgjnstizo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtqffoyqux.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetlcsufn.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtlglkzrgu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtvkbslcdo.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtghhhjouz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtxkjnwfdi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtanqsrpbb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsmflipy.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangdashe.top/Article/details/gttmnzbdvp.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gthokxjvaj.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtlrkmwpxh.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtkzploebt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.kuanghao11.cn/Article/details/gtdmfbdcwk.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtvqvkwlnk.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gttojisqys.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gtlccndusw.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtuxcpbahm.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtnoxxmrit.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtlzelfpax.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtvwwadtnj.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gtosmbathk.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljqrzwat.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gtgfzvncpl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gtbuydfjwo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtgrmlhlzg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtduonxgwp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gtbetbxduh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gteqeqkbyx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gttritrqme.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gtjurbwoub.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtleqayfwd.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gtmishjpbx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtoixeejzb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtqzuhplgg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuanzhike.top/Article/details/gtfgmkzxyh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtxucllrlz.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtpirwcqpz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtwuljtjfp.html


<!-- 参考信息 -->