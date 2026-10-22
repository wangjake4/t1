代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cheryme.top/Article/details/gt2nohvbwxv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2uqjzsusz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gt2mlufnwfh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gt2rljtaogh.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gt2cjzrqvvq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gt2eagajnln.html

[K04] 读取 JSON 文件
来源：http://dali.zhoulong.xyz/Article/details/gt2yrhvgdtr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yj202588.top/Article/details/gt2jauvtgrb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.ivvv.top/Article/details/gt2szfpmlvv.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tanke756.top/Article/details/gt2xzgneqiw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2fsxpmnnh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2jygvigln.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gt2bwnyolxc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2xllirjoq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ybcxt.top/Article/details/gt2zxmzshdi.html

[K05] 深拷贝对象
来源：http://dali.yanxiufei.cn/Article/details/gt2jboyqvlb.html

Py:   copy.deepcopy(obj)
来源：http://dali.smart0.xyz/Article/details/gt2hziazelf.html

PHP:  unserialize(serialize($obj));
来源：http://dali.daria6918.cn/Article/details/gt2cfzsmlwj.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2mxhlyqnn.html

TS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gt2onbxhzfu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gt2mzohadow.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gt2ttyqvcjo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gt2wxpxpmdb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gt2obhwprxd.html

[K06] 解析 URL 查询串
来源：http://dali.daxiang520.top/Article/details/gt2ypisxmjq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gt2mvkupwca.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.tanke756.top/Article/details/gt2yqvweego.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2cvkkohht.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gt2ddkizvnj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2txcflera.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2kfdgiref.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2hxnezuld.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2fsyaxhxb.html

[K07] 进制转换
来源：http://dali.xuanzx.com/Article/details/gt2kjwxpsak.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2risqttgm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sxryk.cn/Article/details/gt2szdlmgzs.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gt2izsrcikj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gt2jycdctyd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2cjofahbc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hgnzepgc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2uajihmje.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2myytsiyq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hywenlv.cn/Article/details/gt2dczuvirp.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2frkcbbax.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2ogucuwhd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gt2enugzieu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2oawsujfl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezrbbkcx.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2czqxdxtc.html

Ruby: Marshal.dump(obj)
来源：http://dali.jianghu66.top/Article/details/gt2gfbyfnlm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yongpay.top/Article/details/gt2wldyfswz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2yqqgrsmk.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gt2gcqyinwv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqpjovyk.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvlwvvpt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangdashe.top/Article/details/gt2kxdxqxsu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gt2yezzarki.html

JS:   await fetch(url)
来源：http://dali.dashuyun.cn/Article/details/gt2omjgeikg.html

TS:   await fetch(url)
来源：http://dali.cucudq.cn/Article/details/gt2evqkgros.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gt2fkeglwbw.html

Go:   resp, err := http.Get(url)
来源：http://dali.yangfankeji.com/Article/details/gt2clisjeoc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgufenzy.top/Article/details/gt2ihzfwwsr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2yjasyyhi.html

[L02] 发送 POST JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2nvelmbnn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2pwxbwfhk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gt2ibanptdg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2rczpchag.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gt2mstrixhg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gt2zklthzwx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gt2korxtvak.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.snrcjt.cn/Article/details/gt2adxmdmdi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gt2vvgghayf.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gt2souhkmnf.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gt2vceqhfcm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yueranfly.top/Article/details/gt2azheyayk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2ptgpidbs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.316326.xyz/Article/details/gt2hgbonlhy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2xachetzs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2vlxtblwt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gt2ecvmtgio.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yueranfly.top/Article/details/gt2eawmszah.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfpgegl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2dccbfmwo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gt2bmsdorux.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2uacdthwn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2dcfxafzn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptptwglb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hammf.cn/Article/details/gt2uqipbroo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gogol.net.cn/Article/details/gt2jjdjncka.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gogol.net.cn/Article/details/gt2ivpmluki.html

[L05] 上传文件（multipart）
来源：http://dali.cashguo.top/Article/details/gt2kylocpej.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenzaomai.com/Article/details/gt2eubqolyp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emzwleyp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hibugssu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ajmtckzu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fzhhl.top/Article/details/gt2unoocjga.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.c1oappe.top/Article/details/gt2oulopkbx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2iitjwdbj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2thdpgnph.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gt2rrqfupma.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2trnoqmkg.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2splpbeur.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2kqscifaj.html

TS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2ppkijnwu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxmvqewy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gt2gqtovfll.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gt2vphgchqw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sysykeji.top/Article/details/gt2cinsjjxu.html

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2qgorycvc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yvedp.cn/Article/details/gt2zsecjanh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2gznhwktr.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gt2mndzxuty.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gt2tndsamyq.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gt2kbbjyurf.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gt2xqacsyfc.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gt2gbarpglr.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2mdaqnlna.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2plxaamqn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yymxhqpb.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gt2euaqpeac.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxhfzqrd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gt2aqtkktpe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.316326.xyz/Article/details/gt2czmnjhwe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gotoacloud.top/Article/details/gt2enfwurrs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2evtmkkqk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2tpfcidfd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2lzwlzzkv.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2bgatkujg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jrjkukty.html

[M01] 读取命令行参数
来源：http://dali.chenlongwang.top/Article/details/gt2ikclpcgs.html

Py:   sys.argv[1:]
来源：http://dali.cheryme.top/Article/details/gt2bbjnlmzj.html

PHP:  $argv;  $argc;
来源：http://dali.jqgfzy.top/Article/details/gt2nfrherju.html

JS:   process.argv.slice(2)
来源：http://dali.jianghu66.top/Article/details/gt2qmfabvht.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2aijeweaa.html

Java: args 数组（main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gt2spqqtqhr.html

Go:   os.Args[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2ihaksekm.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhyutgcz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xylfe.cn/Article/details/gt2gvbldwes.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2szwaxjxk.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2btumzlmv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiivipn.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gt2akebsfco.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebwsknrw.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zidntayc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2iigvnnqq.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gt2cjwgsunj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2ntteoaxf.html

[M03] 执行外部命令
来源：http://dali.tanke756.top/Article/details/gt2yuizfhkc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gt2lvsfeoyi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2jmhlsnlc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2hgbpiwxe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2qwohmvoo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2rhhbwlol.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gt2vhtfgoui.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdigfrji.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2anyscglf.html

[M04] 获取当前工作目录
来源：http://dali.daria6918.cn/Article/details/gt2xpvizxtx.html

Py:   os.getcwd()
来源：http://dali.meibo888.top/Article/details/gt2eyhcwsyi.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gt2fzhcyncp.html

JS:   process.cwd()
来源：http://dali.jiagoushi.top/Article/details/gt2tljgvvry.html

TS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gt2jqqbqbmp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gt2jocnigcj.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2dlbitptk.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gt2gciufduw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2rvwozazd.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gt2jzafmprw.html

Py:   sys.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2dfcfepxd.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2xniqpmjf.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2xzfhdqdj.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugsnqtwp.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2snvgetir.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2javqvzci.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gt2ewotkflj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gt2etjfztlp.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gt2rucbkawt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2yksckujh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gt2zlpqlkgn.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gt2hixkxidy.html

TS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2hvuxheoh.html

Java: System.err.println("err")
来源：http://dali.yangfankeji.com/Article/details/gt2ukrsatkw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2wfqbrjuq.html

Ruby: warn "err"
来源：http://dali.zhongyouzk.top/Article/details/gt2iujaxhcu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gt2qwnvpjet.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gt2pavrhsio.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2wevjbdyy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gt2rfjmbmci.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gt2wkkhdfox.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gt2sfjrvbgh.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2icfjhwcf.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gt2fsxwaacl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2lkqebwlj.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2ielgcugu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gt2qznvzzpr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oybulwxg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yonumen.top/Article/details/gt2cvhfoapv.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gt2kllvzxwi.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2xzwofykv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gt2alzjosip.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gt2lmorghzn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gt2lstpgtxm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xylfe.cn/Article/details/gt2bpbgtydb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2kywxozde.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gt2qjhtidsr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ogqerjbg.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gt2tnwvasao.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2ycklvieq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2ahnculey.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2vktaevzv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijoqxnoy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2zmroyfsu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2vbkgannm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmqeqoxy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ideovuip.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gt2uptrsgii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gt2oekynokz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gt2kgouqlyg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2rosbrfff.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2harlpwij.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gt2dfdsnfsq.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2dhdynrgq.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gt2givifbnj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gt2otubcgwa.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gt2hndngplj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2upygztdw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gt2sddwxdei.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2fmymdpvm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sweek.top/Article/details/gt2hnoltdrk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.c1oappe.top/Article/details/gt2vasbnndg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cucudq.cn/Article/details/gt2yugafnrr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2pljdxqgi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tcwebbhu.html

[N04] 斐波那契数列
来源：http://dali.svipenyu.cn/Article/details/gt2dlwizzsv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2idtsashj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2udbclsog.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2jgziihxf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2cllycmhm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2vtalcyia.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gt2nlyugapm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sschmfvx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2rhvdkfgl.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gt2aictvydu.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gt2lztuicws.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avfzbwku.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yptfygue.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2etzrfvsz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gt2gfxuneow.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gt2zuujlutk.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gt2lgdvqgvd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gt2ywizoydb.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2qjsarirs.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzidwowg.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2jjovpmig.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2zajejmha.html

TS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gt2unibykjd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvuorsih.html

Go:   // 双指针从两端比较
来源：http://dali.shuidangran.top/Article/details/gt2xtbycbvc.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gt2ninscsne.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2vdcnjfha.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gt2evnwiwnk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gt2bfhsxlue.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eskebmzm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gt2uwavzjan.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gt2bcdrwqij.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gt2apytcrxt.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gt2wpghrrny.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2twkfdqbe.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gt2qancxywq.html

[N08] 生成全排列
来源：http://dali.nwbrower.top/Article/details/gt2tjembbfx.html

Py:   itertools.permutations(arr)
来源：http://dali.yvedp.cn/Article/details/gt2fmbeennl.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gt2mfytfqek.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2hdyardmf.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2gigldljp.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2ggrbzktj.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2rzpjerkm.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gt2swidlgcn.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2tvhxoqhv.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gt2qejnzsjw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gt2rbnfobcd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2sgrbxjhm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2fnoxcwhu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2xmmyrmeg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2dkduogxy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgpltalp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2nkqnywnx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gt2rjjfdrxv.html

[N10] 链表节点定义
来源：http://dali.316326.xyz/Article/details/gt2xnddxiqv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khvjwgka.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gt2xzjiwsuu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gotoacloud.top/Article/details/gt2dnkegtyl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2honxqaqe.html

Java: class Node { int v; Node next; }
来源：http://dali.316326.xyz/Article/details/gt2qftkorsn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axcsppgp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gt2jrpablxf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iklmyjoq.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gt2wxtmbtvw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gt2zobwweog.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gt2hunluzjz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2igjiwddw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2hrjbogsq.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2mhniovrb.html


<!-- 参考信息 -->