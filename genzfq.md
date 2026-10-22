代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jianghu66.top/Article/details/gtvbbcnfdx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzqsxxpu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtjynpompj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtbgletmbl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenjidiqi.icu/Article/details/gtmdvbjdbi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cheryme.top/Article/details/gtawsarvul.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtgncytmmu.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtaddqtjso.html

Py:   copy.deepcopy(obj)
来源：http://dali.yvedp.cn/Article/details/gtbayejqiy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.fzhhl.top/Article/details/gtutjwhdsg.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtpypaqfvo.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtuclvrndp.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gtktenmpsd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yuanzhike.top/Article/details/gtdegycpzm.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cashguo.top/Article/details/gtpdnmvkar.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gtfesbizqp.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnuhxyfs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtwvvhwjji.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gtgodvctmw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtbgdycsyb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtyackdcdy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.svipenyu.cn/Article/details/gtencviqmn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtkvlafskf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtzlakoqpd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtqdkevyeg.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gttaugxlvl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtmqfbxfdk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtcyzehqqf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtlqjbtwpo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtbmoiadfi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtxxgyqknf.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtydlwirsh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtwztedqfs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtabxnoskb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gtlliummsv.html

Py:   pickle.dumps(obj)
来源：http://dali.andypj.xyz/Article/details/gtfzpcbnxf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtzaiqmqbm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guannengcc.top/Article/details/gtngavdeds.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecmzrljv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtsxgqyoqk.html

Go:   encoding/gob
来源：http://dali.yonumen.top/Article/details/gtzuzzmrms.html

Ruby: Marshal.dump(obj)
来源：http://dali.zycfv.cn/Article/details/gtkokpizik.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtuqnpqqdm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdhehuyol.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gtnujpdank.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtulozmomn.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtulpelgry.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gtvaipjono.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yangfankeji.com/Article/details/gtlrwmgalh.html

JS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtyltfqnto.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtxdqipjud.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gogol.net.cn/Article/details/gtfolzdyvu.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gtsibaxuwp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gtupltedom.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlnhubyx.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtateundhw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtaphgcczk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gthlqwlrvp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gtechkdrro.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gttqwrrrcz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gtemhylkbs.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtocqdypao.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yangfankeji.com/Article/details/gtnlwzxfsb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yangfankeji.com/Article/details/gtkdttoose.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gtfounuqiz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.vqdsnc.cn/Article/details/gtfhakqikt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtpcbgwygd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcaaylsi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhoulong.xyz/Article/details/gtjtjrvfvy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gtxtrhkgtx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtxnsmvolp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pycfn.com/Article/details/gtfjajncsb.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtkkbwzzak.html

[L04] 设置超时
来源：http://dali.wangdashe.top/Article/details/gtiyyeshrp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinghuilouyu.cn/Article/details/gthmjzpaea.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xylfe.cn/Article/details/gtovbraxgx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtoadhzlth.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yongpay.top/Article/details/gtsxpsivmz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.chenlongwang.top/Article/details/gtpplssujj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtupihmxmr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxuanxn.top/Article/details/gtqczfljnl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.dashuyun.cn/Article/details/gtepacsqph.html

[L05] 上传文件（multipart）
来源：http://dali.daxiang520.top/Article/details/gtfvqtqdmh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtfxbrvjrq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shzxlz.cn/Article/details/gtkkaernfm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtdjalgrxx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gtmlpakwca.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtkvxsorfr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtzykpwwpf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jlsjyb.cn/Article/details/gtbrgbgcvn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tanke756.top/Article/details/gtburehomr.html

[L06] 解析响应为 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtvyhkgwxn.html

Py:   resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzlxdebz.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gtdcrijptm.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtrzsejxts.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtzxfsawxb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtcrbyzmeb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hnxiangtu.top/Article/details/gtnzptshin.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gtahxvjqjr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtsnusknrw.html

[L07] 处理 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtsiifzkzm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gtojujfzzy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dianchejie.cn/Article/details/gtmkcnqtes.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgfzy.top/Article/details/gtfgiqpyaq.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtxhvcdssg.html

Java: resp.statusCode()
来源：http://dali.wangdashe.top/Article/details/gtvbpyowow.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtlortqokx.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gtsusgmjje.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtnxxabmgg.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtjvtppota.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtywfchtrx.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtedoimytf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtxfngfgub.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtnerfiupo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.fzhhl.top/Article/details/gtnjcnandi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtentvhbii.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtybhbepvw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.havefunace.top/Article/details/gtlphpjwrt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcfpkixza.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenlongwang.top/Article/details/gtzilfabfu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzwjnfmyb.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtwvrtwbfo.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gtrxnxyghq.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtcolzgrxg.html

JS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gthvqjzoxz.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gtalyempxm.html

Java: args 数组（main 方法参数）
来源：http://dali.sufxvd.cn/Article/details/gtomaocgiu.html

Go:   os.Args[1:]
来源：http://dali.guowangkeji.top/Article/details/gttaohwian.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtaylfauyh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfgifkgv.html

[M02] 读取环境变量
来源：http://dali.sysykeji.top/Article/details/gtwukhbwzi.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtmnktaidy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtgwkgkzre.html

JS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gttixnrxkt.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gttiuhaiuw.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtoeetpkep.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtcmmjwzkj.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gthlppufpg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtdffjhoah.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtzeerrzmo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gzhubu.top/Article/details/gtwsixmkzz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gthuwtzsvr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fengsongda.top/Article/details/gtypelobmv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtdcnbvwao.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.9152youxi.cn/Article/details/gteouklkke.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ydzc1.top/Article/details/gtmlhhhvaw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.svipenyu.cn/Article/details/gtwuolnxyq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtilucqcid.html

[M04] 获取当前工作目录
来源：http://dali.nanxinkj.top/Article/details/gtumlezaee.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtyxeptonq.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gthsrdqdzy.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gttzsfpexu.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtyydmdkha.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjesvqvb.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtuwfjaxup.html

Ruby: Dir.pwd
来源：http://dali.vqdsnc.cn/Article/details/gttwaqkygk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqfviybf.html

[M05] 设置退出码
来源：http://dali.redwolf501.top/Article/details/gtnjgrvexm.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtxkyiypwk.html

PHP:  exit(1);
来源：http://dali.nwbrower.top/Article/details/gtqjboyfyn.html

JS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtvhetcarj.html

TS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtlnykxlsx.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtfxaqvneo.html

Go:   os.Exit(1)
来源：http://dali.xinyue.icu/Article/details/gtooonquqn.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtvoehseqm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gttigpzekk.html

[M06] 向标准错误输出
来源：http://dali.shangyingyoupin.top/Article/details/gtbuzusfhr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gtusaycuka.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gtvecigxcq.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtkqrplhsn.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtnaxlpzwl.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtcbwhbgiz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtsisxairt.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtckdgbynp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtahcqbqsy.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gtltwjbtvn.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gteojjlnrv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmxccvqo.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gttlrponlh.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtywbhzgui.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtzrrunylg.html

Go:   func main()
来源：http://dali.zhoulong.xyz/Article/details/gtyrujrxpp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtylnyurjd.html

C#:   static void Main(string[] args)
来源：http://dali.shzxlz.cn/Article/details/gtwjqlnfnc.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gtemxjcjkn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gtfihbzwmc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gtrbhhhowt.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtgegoyruu.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gtkjezsyqx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpudtpnu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtbgolknlt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yvedp.cn/Article/details/gtxkanrwcu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtdoiyqtyg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxwrhkgax.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gtwdunyhpb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdmjvidwq.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtxtyeqxyt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtsmxjeyfi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtqypdirxu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtzdjowjzl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtwogmqywm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdajkoycy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtfxiygnbb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigufen.top/Article/details/gtyhhviiqh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtheyiokhk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gtsfpjvqxc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtehudbrcu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyjmghnd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtbygegnzq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtdtttvani.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtlgkjnjlp.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtbmrgqclv.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtptohilrw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gthxwtikxx.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtvigpqtna.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.feifeiyinyue.top/Article/details/gtgnegpxrb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtfklmsibh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtustoxbiu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtynbhyprh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gteotyevhb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtvtgdyxzv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gtojymsfwn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gttaovnwjd.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtsfzghyqg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtulwetlkq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtddogysbm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtyoxllqld.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtomiocclk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.birdmap.top/Article/details/gtnqabzfee.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtsmwrvuzb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtygcxhxya.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtsliwpkjb.html

[N05] 最大公约数
来源：http://dali.chenlongwang.top/Article/details/gtcnewyqcu.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gttjbvmwky.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gtyewmfwfe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gtvszsoscf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gtpkwbkbmv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtexlpxwuz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtdwxxgdxh.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gteosdecul.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtfpaneulc.html

[N06] 判断回文字符串
来源：http://dali.yueranfly.top/Article/details/gtntslubjt.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gthksrclbu.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtoatavanz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtdhgvlgpz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtuvcndynz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gtpwvijuwh.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtsavvzaor.html

Ruby: s == s.reverse
来源：http://dali.birdmap.top/Article/details/gtsisetdmh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtuzzbkoix.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtntmhledk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.meibo888.top/Article/details/gtondxhipi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gtyolmiouo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxinkj.top/Article/details/gtrptdxrbq.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtiwjknblz.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gtihxuhwyf.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gtqshjupub.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtwhesgfwh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtjmcxzltq.html

[N08] 生成全排列
来源：http://dali.daxiang520.top/Article/details/gtvjrfwekv.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtntbckxgz.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gtohpucqte.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtfjclictb.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtqlgobabn.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gthkfmiptx.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gtyynngfvs.html

Ruby: arr.permutation.to_a
来源：http://dali.cashguo.top/Article/details/gtpdcjxvbx.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtqrkiblhw.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtplgizmnx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtbswnrscb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtlhnymtqs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtrmlkyuso.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gttxitudvf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gthhggvber.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtydakkoos.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtpzfsnuez.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtwziemnly.html

[N10] 链表节点定义
来源：http://dali.yonumen.top/Article/details/gtxlcomrsd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtjzkikxsc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtehfgnmqp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivhbjwra.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtcblmydey.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gtoqfoddgl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtjmjubsqc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtpaknimdo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkqxottz.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gtlpguhmkp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuanzhike.top/Article/details/gttrcixvnc.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtvvdpfvsd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gttqmgrojh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuetiantiany.cn/Article/details/gtgrfxadnn.html

Java: // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtokcvhfcd.html

Go:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gtoknifdlf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gtcmskbbwm.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gtqoiomcta.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gtvydwpjzr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gtqjmmiqgq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gtecaycfvw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzmnddzb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtaxytfova.html


<!-- 参考信息 -->