代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2dlzalqoz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2azmnwhum.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2glnpyuup.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gt2xrxemdae.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.birdmap.top/Article/details/gt2stjbozfm.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gt2fqndcyco.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gt2urkgjqps.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gt2kvwvbpxj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yangfankeji.com/Article/details/gt2uspbnscw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daxiang520.top/Article/details/gt2rwxfgqmj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.9152youxi.cn/Article/details/gt2opzfpamv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gt2vxdbzevw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xvrazpkv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2yelikjkj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2uovhadps.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lueclquc.html

Py:   copy.deepcopy(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2mlzwjalu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.guannengcc.top/Article/details/gt2pfmxmsxx.html

JS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2judsxjbn.html

TS:   structuredClone(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqaprfkl.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daxiang520.top/Article/details/gt2ctnzxwmy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fyckkycr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cqqwz.cn/Article/details/gt2yrkqvgya.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gt2nmfzrrhg.html

[K06] 解析 URL 查询串
来源：http://dali.fengsongda.top/Article/details/gt2qzhmetai.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.mhx1999.top/Article/details/gt2xyoyyvgc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jlsjyb.cn/Article/details/gt2obarnbbi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yvedp.cn/Article/details/gt2fhrwujkb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gt2rginejrj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cqqwz.cn/Article/details/gt2xfpiwqmt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gt2joxkurrs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gt2qpspmalr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2cyllxxoo.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2qxkzdijz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gt2xsdgttou.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gt2rwtybono.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gt2lsyhxoqe.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2sklsrkrz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2eomvjooo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ivvv.top/Article/details/gt2zimaclwa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hfpthk.cn/Article/details/gt2akruoloc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gt2qiflgeag.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gt2mcqajmyn.html

Py:   pickle.dumps(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2dmqoinhp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.smart0.xyz/Article/details/gt2xynseliq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gt2eqcmsazt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2jgbivciw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhijiandao.cn/Article/details/gt2orallyhx.html

Go:   encoding/gob
来源：http://dali.tanke756.top/Article/details/gt2bccgosby.html

Ruby: Marshal.dump(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2scvrstwn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2tcrdcqgi.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nljctxhr.html

L. 网络请求
来源：http://dali.9152youxi.cn/Article/details/gt2ljberauw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2pyfbaltc.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gt2xwnvegiy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hnqzz.top/Article/details/gt2ykklgcab.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.bjfxy.top/Article/details/gt2opproxkv.html

JS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gt2pblvfsub.html

TS:   await fetch(url)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifdnwtmg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.snrcjt.cn/Article/details/gt2waduomnr.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2wfwnelxw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.mhx1999.top/Article/details/gt2khejbcdn.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xylfe.cn/Article/details/gt2jjszdoqf.html

[L02] 发送 POST JSON
来源：http://dali.fengsongda.top/Article/details/gt2vbfleuvk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2iyioyrfw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yueranfly.top/Article/details/gt2rtksbyiy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gt2fbxxasde.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tianlin.xyz/Article/details/gt2wxmdjuki.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gt2bubexefr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gt2rhdipaky.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gt2wnegtkqz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gt2bhmqygkp.html

[L03] 设置自定义请求头
来源：http://dali.hywenlv.cn/Article/details/gt2oghbvpjk.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.nanxinkj.top/Article/details/gt2uslkjeoi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2aofmwcet.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2htpntoqf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gt2wgxozmer.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gt2xaslrsnc.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gt2xhmjvjyf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2kidzerej.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2ttexmlfq.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gt2utfawqcl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwjxssrs.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2azhwwjol.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2tanjffmq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2awijdhvi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2ldeqdnuu.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gt2wcuqapkt.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gt2wxfenjdo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ydzc1.top/Article/details/gt2ywgclyai.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigfzy.top/Article/details/gt2cjzqeqdb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nkljcbys.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2oanobnho.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gt2ldochllk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2iciysihi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gt2myjrryis.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gogol.net.cn/Article/details/gt2qdwzvkuv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yangfankeji.com/Article/details/gt2kflxvyty.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2kktolubs.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2mqutxngk.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gt2cjazjfpy.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gt2luwqqmnw.html

JS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2wbmpjkly.html

TS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2bgptmnet.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sctdkujy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.havefunace.top/Article/details/gt2lxxibmrq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gt2xcjvehvt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fzhhl.top/Article/details/gt2ccpqfewf.html

[L07] 处理 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gt2leruldjq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2vxkhwvud.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.quarkkingdee.top/Article/details/gt2vvvehtal.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gt2ousebyro.html

TS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjufjkkg.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2siirsjlq.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2idojhsdm.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dbtzknfb.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2pmepjrjm.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2mwambwof.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2jhxfatxv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gt2ewxnzcpo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2cxizstql.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2ygzmhohb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cashguo.top/Article/details/gt2jymxecne.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ydzc1.top/Article/details/gt2vqnrtjli.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2ukttrzmc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2opgtifiu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuqvmgyn.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gt2uyucauds.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dtumowgh.html

[M01] 读取命令行参数
来源：http://dali.gotoacloud.top/Article/details/gt2taatfrqq.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2nzbnhvoj.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkhrwqsh.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2gyfchwdo.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2qdaldvqr.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gt2ggxdlgzb.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gt2hvlvrmxg.html

Ruby: ARGV
来源：http://dali.sysykeji.top/Article/details/gt2qwrgpula.html

C#:   args 数组（Main 方法参数）
来源：http://dali.gzhubu.top/Article/details/gt2ljvpkwva.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2nhljmuoj.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tudarrhq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gt2wmjckmce.html

JS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkaowstd.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2xnjucmho.html

Java: System.getenv("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2czhwxofb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2rwsgwoyp.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gt2xwngqjky.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2pjqrcpva.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gt2gknyyrkn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gt2kjrdeqnr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gt2stcaajoq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iolmbrjn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gt2clpmoxhf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.andypj.xyz/Article/details/gt2lqdotwkr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2twnadtcr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guannengcc.top/Article/details/gt2ldyxqrrb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2wyjrltis.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2iqxppevx.html

Py:   os.getcwd()
来源：http://dali.316326.xyz/Article/details/gt2fywvetnk.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gt2wirxexrf.html

JS:   process.cwd()
来源：http://dali.haohaochexian.top/Article/details/gt2gtvkpjhs.html

TS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2lazneccn.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yueranfly.top/Article/details/gt2illjoabx.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gt2xtaoucxw.html

Ruby: Dir.pwd
来源：http://dali.tianlin.xyz/Article/details/gt2xrgnjdjk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2fuxozfyz.html

[M05] 设置退出码
来源：http://dali.tianlin.xyz/Article/details/gt2qptjoyul.html

Py:   sys.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2klyawvci.html

PHP:  exit(1);
来源：http://dali.0kj1m.cn/Article/details/gt2zpwomhke.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kkiaiyax.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2emyathbp.html

Java: System.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2thsnypgc.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvmgylzh.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gt2uyabfwxm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gt2vsnbsoga.html

[M06] 向标准错误输出
来源：http://dali.smart0.xyz/Article/details/gt2psitwmoy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2kqgtdyaa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gt2iqmaqboi.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2yucerapo.html

TS:   console.error("err")
来源：http://dali.haohaochexian.top/Article/details/gt2krtmpptx.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2bnzjtjoc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2wczhlvrc.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2esydlqpk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2djbldmly.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gt2fubbqelb.html

Py:   if __name__ == "__main__":
来源：http://dali.shangyingyoupin.top/Article/details/gt2vefurlte.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xylfe.cn/Article/details/gt2eavzyicx.html

JS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pocumpmj.html

TS:   require.main === module
来源：http://dali.tian-w.cn/Article/details/gt2daxfbygr.html

Java: public static void main(String[] args)
来源：http://dali.yvedp.cn/Article/details/gt2zgurxadd.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2huhbnjuz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2bofvzgka.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oatgvuqx.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2ruboitzd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuwdsti.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gt2cpssudxr.html

JS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2bcjqcrgg.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuxufbzr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gt2dctovrtd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sweek.top/Article/details/gt2lzpmkykm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gt2vsijojpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gt2necnslgl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2hvwhkmpg.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztipccvt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2kzlcxpco.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2eqkpuecf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2hzmervsc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aibaodan.cn/Article/details/gt2vezlbyjr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gt2ntceatxd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2bgkkkrkt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2mpeeqymp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2myiqnsmr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gt2uxcuuuzx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2rskqptii.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2utfbmxfx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gt2quqpiuvu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gt2apfrjept.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2chesexhk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2jhbsbvgj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gt2etmwngtk.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2vhokejvs.html

Ruby: arr.sort
来源：http://dali.tianlin.xyz/Article/details/gt2ardpgtnj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feycclbl.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258.top/Article/details/gt2xdriwjsw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2ythecuoa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gt2hsoeqxfz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2aovpcbtj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2kqjwiytz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sweek.top/Article/details/gt2xbxfvdew.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gt2drnaxdcf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gt2rxihfpaw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2qevqbwzl.html

[N04] 斐波那契数列
来源：http://dali.pycfn.com/Article/details/gt2rhqkkgjh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2duufehcx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2bmfuanws.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2cfobveux.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2vulwhhry.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gt2ezxfhrkm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gt2vtommmvt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2hehflgms.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2aaxoqflh.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gt2bpgmsoon.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2ywhlinlu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gt2jnzcxsav.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2sqfpxtna.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jbggztit.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gt2phvnnsjq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gt2cgxtdmfs.html

Ruby: a.gcd(b)
来源：http://dali.hammf.cn/Article/details/gt2wgbuugha.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2wwvsnozk.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gt2opqgxxde.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2xwrgelgo.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258.top/Article/details/gt2wxjbabuw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2tbkhokre.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btyrambo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gt2gwoyvudw.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2stbfyfcj.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2gwbuvszf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2ezoeeslo.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvgvymgj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gt2uifbfscp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gt2kaegeapm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daxiang520.top/Article/details/gt2wczrgftb.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2rpuafgwl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdufpyc.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2qaalwcen.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2djlllupa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbsfwvn.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gt2mfpnkuqm.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2pxizzqki.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gt2rnapmiux.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2bhkjzjwl.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2zdvxlmvi.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2fhfdtinx.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2rnwvlhbk.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gt2matcuwel.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2hevpjdlk.html

[N09] 栈与队列
来源：http://dali.cashguo.top/Article/details/gt2ismoptot.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gt2elvdmaoy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2ckxtxciw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2wirdmrzz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2clanhuls.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gt2lsrfpbnc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2nypoqplq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2nzyaxwid.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvwbhuiq.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gt2nudpashr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qaibbjvc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yanxiufei.cn/Article/details/gt2scgcatfi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gt2jffpbhul.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2lzxqpuyf.html

Java: class Node { int v; Node next; }
来源：http://dali.kuanghao11.cn/Article/details/gt2nupbxyty.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gt2zabrappv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sweek.top/Article/details/gt2lxtpaaox.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gt2gaegaook.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2kfsifros.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.iojbl.cn/Article/details/gt2hojdvcpe.html

PHP:  // 手写递归函数
来源：http://dali.nanxuanxn.top/Article/details/gt2jshlxqhs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gt2rrhsydcx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2lzcbaeee.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2pokniaew.html


<!-- 参考信息 -->