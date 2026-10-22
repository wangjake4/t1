代发 wailian999

TS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gt2iefiiblz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2idsusquv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gt2cptiiaqw.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gt2qdceujxg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tskuthmu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.316326.xyz/Article/details/gt2bmpnemfp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztmobjmo.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2geiwznrw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ftffrdbz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2yourbvjn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gt2zrfhhgmo.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gt2kigpbjcv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gt2yunulthl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.nanxinkj.top/Article/details/gt2cbcyntho.html

[K04] 读取 JSON 文件
来源：http://dali.yuxming.cn/Article/details/gt2rwfbwksw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2noycufyo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.0kj1m.cn/Article/details/gt2xrpjwrrr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2xcdifmhs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2gfqwcuqz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2qnqqruvo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hammf.cn/Article/details/gt2jqrqimsx.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wsmmmgos.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2fqssippz.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gt2bqpeeega.html

Py:   copy.deepcopy(obj)
来源：http://dali.tian-w.cn/Article/details/gt2rpihflsh.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhoulong.xyz/Article/details/gt2gktixnkd.html

JS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gt2emdaljcp.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2iyjbpnpn.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2eyyyvhhr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnskdvnm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gt2vzkutuzu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gt2eevoxekg.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcodygru.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.tanke756.top/Article/details/gt2jwawqbfd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhoulong.xyz/Article/details/gt2akdyplim.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gt2tzllodue.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jianghu66.top/Article/details/gt2cldbsjpb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gt2ldedqqnq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2kcvmlgnh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwrmcdrz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gt2zasbsbiw.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gt2ptajqzjf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2iwcxrybm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nwbrower.top/Article/details/gt2qnpefina.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2crxpnjlu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gt2jveovray.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2tpgiybjv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gt2dkdxgqgc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2prydmihj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2hiicbupl.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gt2ksjjrfeo.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2bthfjpvs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gt2rqjwazlp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2mywmggtq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hywenlv.cn/Article/details/gt2zbitjgme.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.tianlin.xyz/Article/details/gt2qlrvvbau.html

Go:   encoding/gob
来源：http://dali.cdnleiting.top/Article/details/gt2utuzjiec.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2smrchopg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gt2rvmlxxco.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2saiehmif.html

L. 网络请求
来源：http://dali.ybcxt.top/Article/details/gt2usvzdfhq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waayhdbf.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gt2qeiyplwn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gt2knnlqtok.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gt2cvdayyjl.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2uglvcnwi.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2colklrib.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258.top/Article/details/gt2riazangj.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gt2gmskafet.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nerdoiia.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.bjfxy.top/Article/details/gt2dhaiavae.html

[L02] 发送 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gt2xlqfjflf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gt2jextuupo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.feifeiyinyue.top/Article/details/gt2mxkfzoat.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenlongwang.top/Article/details/gt2izpoekzt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2yplbuacm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258.top/Article/details/gt2dlargbeb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gt2qxfkfybt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ehwqpu.com/Article/details/gt2wyernleu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xylfe.cn/Article/details/gt2xzfqxerc.html

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2kzknepzb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2hmnuuqpe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gt2hlpphlym.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2dlcokafc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gt2cvjkzlny.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sweek.top/Article/details/gt2bvdxetwi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gt2ovyxcwzr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guannengcc.top/Article/details/gt2xwkjefjf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gt2pgpbzvib.html

[L04] 设置超时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwddecri.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gt2pqphedex.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gt2tkgljwtk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2upkglhge.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gt2xsitnlhg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2ubiurukj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gt2mgovdalx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gt2zyotyhqf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gt2jzzkzvnt.html

[L05] 上传文件（multipart）
来源：http://dali.gzhubu.top/Article/details/gt2fqdlpqcq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.snrcjt.cn/Article/details/gt2unvyxqtc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2odurvzjc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2mlfjkeww.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2vialozea.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gt2qnalpmjy.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gt2eiywgqrw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2fpsfyary.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2qoetbqbp.html

[L06] 解析响应为 JSON
来源：http://dali.xylfe.cn/Article/details/gt2yogzcjwu.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2fvyjpayj.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gt2ypocscsc.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2umupagui.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2yhfzgwqb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2fzchpxkw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sweek.top/Article/details/gt2hnyjxcrc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gt2oloxfknm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gt2bbzosohn.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2eimueabs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncoprpht.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gt2qiepxznf.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gt2svsjumvi.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2cxfjmtrs.html

Java: resp.statusCode()
来源：http://dali.guowangkeji.top/Article/details/gt2qbpfzszc.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2vfgsopvt.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2tuqzhqjo.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2tydufziq.html

[L08] 并发请求多个地址
来源：http://dali.tanke756.top/Article/details/gt2ygepndgj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gaohongyu789.top/Article/details/gt2dbxrheyy.html

PHP:  curl_multi_init() 系列
来源：http://dali.gaohongyu789.top/Article/details/gt2brybbtxn.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gt2fkixjlpi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2pdvhqvam.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.birdmap.top/Article/details/gt2mdowzptc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gt2cmtipups.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2buvqhmdy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2wkvoluxp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2femcnaic.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gt2urydmzgr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rlditynz.html

[M01] 读取命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2mrzwdrbe.html

Py:   sys.argv[1:]
来源：http://dali.yj202588.top/Article/details/gt2gezlstdw.html

PHP:  $argv;  $argc;
来源：http://dali.shzxlz.cn/Article/details/gt2qymyrycz.html

JS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2zvxwowtr.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gt2vdeooofz.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gt2ernhemtn.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gt2ejedanje.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gt2ivcelapb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymacxbwy.html

[M02] 读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2jdvltetd.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2lmdyktyc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fsbrmaxm.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2udoomgul.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2uvtxebca.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2oebyvfbh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2qmmvimxf.html

Ruby: ENV["HOME"]
来源：http://dali.nanxinkj.top/Article/details/gt2xgslfepb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2ggutarld.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gt2zzszwnav.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.havefunace.top/Article/details/gt2ktylokku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.birdmap.top/Article/details/gt2yblcwcvo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxpwjteq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2beuxrrex.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.iojbl.cn/Article/details/gt2wdyjtpjg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2zbbzpgde.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hammf.cn/Article/details/gt2yjifpqhr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gt2rmoqhosk.html

[M04] 获取当前工作目录
来源：http://dali.shuidangran.top/Article/details/gt2deavlaae.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gt2ogdinhij.html

PHP:  getcwd();
来源：http://dali.shuidangran.top/Article/details/gt2qujyltrc.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gt2iknywtlh.html

TS:   process.cwd()
来源：http://dali.cdnleiting.top/Article/details/gt2frbvwuke.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ixegavmv.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2vliklmcc.html

Ruby: Dir.pwd
来源：http://dali.chenjidiqi.icu/Article/details/gt2pirveygy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gt2bayhlhng.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2upribpyt.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2qkatrgkw.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucbspzbn.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2ilwdizpv.html

TS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2fdsrddai.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2ercsqfmc.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2rplmcwnb.html

Ruby: exit 1
来源：http://dali.316326.xyz/Article/details/gt2ujomzcpy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpmeglww.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2mnuvkydo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gt2ljwuecxz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gt2zkzjrmap.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2qafuembq.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2jforakoj.html

Java: System.err.println("err")
来源：http://dali.ybcxt.top/Article/details/gt2oyvymkdq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gt2dmaujoem.html

Ruby: warn "err"
来源：http://dali.yuxming.cn/Article/details/gt2qgzaukwt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qazhwfbc.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gt2nlmhbdgp.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2iugztnja.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gt2sfmhtcsh.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymxhddzf.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2birsoltc.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2idoikqat.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gt2arkdhfua.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2mycqbqep.html

C#:   static void Main(string[] args)
来源：http://dali.sweek.top/Article/details/gt2nnvnomwn.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gt2jkjoyyye.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2mrsqszqy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gt2pkiflpvt.html

JS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2ffojjojx.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2sulsqahi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gt2haxnqenq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gt2xezwpdhq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.9152youxi.cn/Article/details/gt2vqvrldyl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2hegeghaz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2bjkdzglk.html

N. 数据结构与算法
来源：http://dali.andypj.xyz/Article/details/gt2jqpwvyxk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2ebbeiuhk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhongyouzk.top/Article/details/gt2zjkqudnh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2bjjubina.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2elvqkjtz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2sonssbre.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2hivgewrb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdymizwj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2ibgorsdv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2ribieylh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2hwjfunps.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cheryme.top/Article/details/gt2cxdfoyxq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gt2saaeghff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2hjqgjtgo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2gaugmzha.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2enwnqzjy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gt2attjdjtl.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2uvasiywg.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2lsgqvrzx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gt2hbrwnjno.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2izuydfek.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gt2fjxfejhk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2xgtyllmv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2kksjyjhi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gt2oyvamgag.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2yqbllayq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2esoksxlr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gt2ipbtggbn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gt2tzqimvre.html

[N04] 斐波那契数列
来源：http://dali.meibo888.top/Article/details/gt2jaxygtre.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gt2shusihsg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gt2mmumgtcf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2fcflwyzd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2gbmizmui.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2kkqfjmji.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gt2gxwuzzzs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2ywkurczs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2pqrwhins.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gt2nmfesvrw.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2vfvoksvr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2lkjlmszs.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjmpklrd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2pwmzyoga.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gt2toaqczwa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2encbcdck.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gt2ckyyokmj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efcuoniy.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gt2uepadndh.html

Py:   s == s[::-1]
来源：http://dali.wangdashe.top/Article/details/gt2zsqxbned.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2zfcqojtr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdbvunvc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2uinrempk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gt2dykzqskd.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2zlhnlybp.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2ionqafsh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2mdpsktjc.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2eupeuoxy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gt2zvgjatek.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2hbmjeibk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ognqzavg.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gt2sdqqrgim.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gt2aqibsxln.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gt2qctafork.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gt2gsmucfil.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgyqrwop.html

[N08] 生成全排列
来源：http://dali.yuanzhike.top/Article/details/gt2dymrghsf.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gt2iggkgvwv.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2yrymtdcf.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gt2hyhioskh.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2geohloqu.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2tiyaxzlz.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2ouvzpmiy.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gt2bmchizqw.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2exwcryze.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gt2ezwvlver.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2fvtxaydx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2dduzjosk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiynresx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gt2orpawyva.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gt2asvlszha.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gt2agvfclpz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2jncqddlf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuobplbh.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjzniamx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gt2jbdeckjb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pycfn.com/Article/details/gt2rqfpxyqn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.havefunace.top/Article/details/gt2ozvvmybd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gt2qmczvgvm.html

Java: class Node { int v; Node next; }
来源：http://dali.yongpay.top/Article/details/gt2ebwixqhs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2fptkvhuv.html


<!-- 参考信息 -->