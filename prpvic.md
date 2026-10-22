代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2lisozved.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2afqlsurj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2ubhkcjed.html

Ruby: JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gt2mvzagsxe.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gt2wobhkrzj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gt2rpxsoqnn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gt2pirhrtei.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gt2tbsulaqw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2nqnelhwr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rkhbdycs.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.chenlongwang.top/Article/details/gt2wucrwlbx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ydzc1.top/Article/details/gt2kzlcfcrp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gt2blyoxnhw.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ybcxt.top/Article/details/gt2xtybekqt.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gt2mubkleuc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2vaudkuni.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrperslo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gt2fftsnbgl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gt2elxojduv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2ysrxgedh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.tian-w.cn/Article/details/gt2dhcrxwcv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2hepfrvje.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jqgufenzy.top/Article/details/gt2htowfyng.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gt2ksymtqyh.html

Py:   copy.deepcopy(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2qvuiuswd.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2xfbogjnc.html

JS:   structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gt2ptlkcbwn.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2zgriwesf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gt2zwwvxxwm.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gzhubu.top/Article/details/gt2oeieqtdr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gt2foeuowyi.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhixingplan.top/Article/details/gt2wzwhpgxq.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqojsfp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieddckbm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj20258888.top/Article/details/gt2uvruqbqy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guannengcc.top/Article/details/gt2rqrayhvy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shuidangran.top/Article/details/gt2vosknrtt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2rcgtmneu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2eiocmphy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gt2tlmpflkx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tian-w.cn/Article/details/gt2ugbagpnf.html

[K07] 进制转换
来源：http://dali.meibo888.top/Article/details/gt2nqlahhvi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fdcxdwlj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnqzz.top/Article/details/gt2aifwufrk.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2vxwsqzee.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2xpkkhkqp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2svulprgr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.mhx1999.top/Article/details/gt2jrqjccux.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akbkocji.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gt2qqjkzujo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqftekfb.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2swcnujpg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jyoumei.cn/Article/details/gt2zrpdwzdz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gt2ephvajhu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gt2dgcjskus.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tanke756.top/Article/details/gt2wjwjlozy.html

Go:   encoding/gob
来源：http://dali.fengsongda.top/Article/details/gt2bkqlbcny.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2nkkoncjr.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2jcdtmsac.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2puiltcaw.html

L. 网络请求
来源：http://dali.yvedp.cn/Article/details/gt2ruuwpswe.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2mqmtmeru.html

[L01] 发送 GET 请求
来源：http://dali.nanxinkj.top/Article/details/gt2ryenwsqr.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sysykeji.top/Article/details/gt2lpymokoj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjfgohdk.html

JS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gt2uoruzbxx.html

TS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mdbmnljh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guannengcc.top/Article/details/gt2ormbnzrs.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhixingplan.top/Article/details/gt2rinjkjal.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yongpay.top/Article/details/gt2fihtqqwg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangdashe.top/Article/details/gt2qfwzblch.html

[L02] 发送 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gt2btyyczuj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yueranfly.top/Article/details/gt2mkjmqxvf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2vocrrply.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2plsiqlel.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hfpthk.cn/Article/details/gt2tqkjgxas.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ybcxt.top/Article/details/gt2ejvgfnny.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zdqjudy.top/Article/details/gt2tyijsexo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gt2ozhniecf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2jlbgjpko.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfdrstjm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxuanxn.top/Article/details/gt2aruclufa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gt2xxfpemht.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2hitynbdi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.mhx1999.top/Article/details/gt2grtgslnl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2gpkufkst.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gt2gyxclpmo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhrudost.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinqigfzy.top/Article/details/gt2rnaiytbt.html

[L04] 设置超时
来源：http://dali.gogol.net.cn/Article/details/gt2gdtgzmxw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gt2kwxdzsgp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2aschncgm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gt2dmmvoefd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gt2zvojspnn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shzxlz.cn/Article/details/gt2jsejdpdy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yuxming.cn/Article/details/gt2shkuioww.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gt2lxqtmwmk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlechupu.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gt2jftdtmun.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2dczowiwv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.fengsongda.top/Article/details/gt2sfybsuln.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zdqjudy.top/Article/details/gt2shpouvpv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ybcxt.top/Article/details/gt2fsdooqei.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gt2kcwbhsgj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2czumnogt.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gt2nghqelcf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2pnpptzkn.html

[L06] 解析响应为 JSON
来源：http://dali.birdmap.top/Article/details/gt2nmgjmucg.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2xfqirehc.html

PHP:  json_decode($body, true);
来源：http://dali.smart0.xyz/Article/details/gt2dbtjbtis.html

JS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gt2vojiynjy.html

TS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2ioanknfy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xziqi.cn/Article/details/gt2tvtloxoz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2afxflcuj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.9152youxi.cn/Article/details/gt2fgjicniq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gt2vthyizsq.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gt2qrhwuhxq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.bjfxy.top/Article/details/gt2iwrqdmzl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zycfv.cn/Article/details/gt2dpkavbwe.html

JS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gt2ckyefofy.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2navsyuer.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gt2rgwlxuoo.html

Go:   resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2cniyebzc.html

Ruby: resp.code.to_i
来源：http://dali.chenlongwang.top/Article/details/gt2wsrzttcw.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gt2wumxovgf.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdzvlya.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gt2twmnuppy.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gt2mpfwkvxu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2jbjsrnfj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2pbdjvlcv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2ulnvsxke.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gt2aketgcwa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tanke756.top/Article/details/gt2deievuao.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pycfn.com/Article/details/gt2cgeetkog.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2rnbdsjnr.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gt2jhnpqvmz.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2pogwdeie.html

[M01] 读取命令行参数
来源：http://dali.tian-w.cn/Article/details/gt2ivkyzlbj.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2qhimnhsm.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2nikphaav.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gt2phziuzpf.html

TS:   process.argv.slice(2)
来源：http://dali.hnqzz.top/Article/details/gt2rzzwbfhc.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2rehgrixj.html

Go:   os.Args[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2hlfdeacb.html

Ruby: ARGV
来源：http://dali.jyoumei.cn/Article/details/gt2rhlmkjzl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2ngatmwup.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2fseuzwfi.html

Py:   os.environ.get("HOME")
来源：http://dali.jianghu66.top/Article/details/gt2qofbwfrl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gt2ircxubag.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2zehrqpvn.html

TS:   process.env.HOME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znxshode.html

Java: System.getenv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2iknbfzzw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2yjlgbdnk.html

Ruby: ENV["HOME"]
来源：http://dali.svipenyu.cn/Article/details/gt2nqztxhqe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2plejegkd.html

[M03] 执行外部命令
来源：http://dali.hfpthk.cn/Article/details/gt2wwcbafsl.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gt2wmdzqwgi.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.c1oappe.top/Article/details/gt2wdyjacmv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybslmymx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yonumen.top/Article/details/gt2nbfxznbs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhigromc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2esvncgai.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258.top/Article/details/gt2alzkvjfm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2uikiqjag.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gt2ttknzfnl.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2drxjytjn.html

PHP:  getcwd();
来源：http://dali.fzhhl.top/Article/details/gt2okmmkxmf.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2krujmybe.html

TS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2kltnuuew.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2rhouljgi.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2ogmcncjy.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gt2deynmdjf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gt2jzvbnfef.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gt2ihtnsmiv.html

Py:   sys.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2hzrrzavl.html

PHP:  exit(1);
来源：http://dali.chenlongwang.top/Article/details/gt2gzrldrlx.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2vutwekkr.html

TS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gt2jfgswnzj.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnpcwnb.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2atplorew.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2cilsmfyi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gt2vfpzfwse.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqupipoe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2jfgzlauu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gt2hxibyxnm.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2pargzekz.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gt2souqqhic.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2rhivjwce.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gt2glojrvsn.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gt2lusfguxj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2vftvrxbc.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gt2keidgrqe.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gt2imhjwole.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdacxlab.html

JS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2kxculydz.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gt2ezixtjuh.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2hwfdjnkp.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gt2cghfxrow.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gt2rcjcgtdr.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gt2xtghxxte.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2eaiamjfs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cucudq.cn/Article/details/gt2nohwfbca.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gt2qaqeygto.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2eerikemf.html

TS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2nlixxhed.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emapongi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2imvghpna.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gt2cluzpgna.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gt2jkxqyxhj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2pbhrztmv.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gt2ualgsoyz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2xdhnoque.html

[N01] 二分查找（有序数组）
来源：http://dali.yuanzhike.top/Article/details/gt2sydrjcwf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2bkrwlrze.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2iqrnwkga.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sxryk.cn/Article/details/gt2uuvmlgpa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2ettzfhjs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2nwlnvkov.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msbdfdlb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gt2ssqglgby.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2csubrgna.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gt2gwngkume.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2meyyfohe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtcstgfe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2czuejojq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2lwsivqoa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2mypqhghl.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2dbebeigf.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2hbpzkdpg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gt2jxwjeuco.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gt2plsrzzno.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwrcahyf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gt2gzbumvrn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gt2hqzjvywj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigufen.top/Article/details/gt2ucbvvymv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gt2qxlkgraz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gt2ryvogbaj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gt2vmeqdurp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gt2vzbbahrv.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2atrplbmw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gt2ibfzrhyw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvteuxec.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2omckfobe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2ygrpical.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2cwrehron.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gt2mgpxnfzb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gt2edinsvfq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2bjkxulgi.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2pdxadhoh.html

Py:   math.gcd(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gt2jskdidrb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2fbvtysaq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2xvmvoqvc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2tdhpqjze.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gt2bsgynesk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gt2kmcohect.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gt2misoewcd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gt2dhgcyire.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dsovghlk.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gt2sdmynlma.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2zcvasghl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yoxamfus.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2dopopvwp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gt2vfbiflrm.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gt2zzkavpof.html

Ruby: s == s.reverse
来源：http://dali.cucudq.cn/Article/details/gt2zmenkvdg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2tpektuct.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gt2dprypthu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2zvqkzcxs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gt2wrasahhn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gt2karviurr.html

TS:   // 手写 Map<string, number>
来源：http://dali.hfpthk.cn/Article/details/gt2udekfvbd.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gt2azntvtxz.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gt2wznptejm.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gt2ppibflei.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuxming.cn/Article/details/gt2yusgetkv.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2cwvnyvcm.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2nsxfszgv.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gt2gyptevye.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2obqgxxfn.html

TS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gt2smrxifkl.html

Java: // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gt2fvsrrvhv.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2iupcxdqb.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2umxrryrr.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gt2dfrlfkud.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2ijdhejal.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rlpuxnns.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gt2oqtuzjvk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drfiekfz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gt2hsjnjsiw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.andypj.xyz/Article/details/gt2jyslocmq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uswvuxpc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2zzheuujl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2zxexvwxe.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gt2oghoyiea.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihjvzwsw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gt2dxexhvhs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gt2vabwfqxh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gt2xmnzcycp.html

Java: class Node { int v; Node next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uvtgjxwi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gt2unoirhpe.html


<!-- 参考信息 -->