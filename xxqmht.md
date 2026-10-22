代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2giodklgd.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.bjfxy.top/Article/details/gt2farpubpu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2isrrjxdt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnxiangtu.top/Article/details/gt2lkjnxxae.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jianghu66.top/Article/details/gt2hrktcgat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gt2kymfirto.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258888.top/Article/details/gt2vqejhdnv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jianghu66.top/Article/details/gt2qdrvgqis.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gt2zcgestzz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gt2bsndodip.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2zpdspuyz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gt2mamcrkkb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gt2rzgrnmcq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdbhprsw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2bgyotkhg.html

[K05] 深拷贝对象
来源：http://dali.cashguo.top/Article/details/gt2jgmobvgj.html

Py:   copy.deepcopy(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2aibrhdxl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgfzy.top/Article/details/gt2kjnoegau.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2yklwnykq.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2xwaphjvm.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shzxlz.cn/Article/details/gt2mdbcavbs.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gt2pvznyqxf.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2sotenmdr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ehwqpu.com/Article/details/gt2betcvcov.html

[K06] 解析 URL 查询串
来源：http://dali.yj202588.top/Article/details/gt2imchzczs.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.daxiang520.top/Article/details/gt2jnrvhpeg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gt2fvfcyjkx.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gt2plkucoxu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gt2armxxlej.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zycfv.cn/Article/details/gt2kzwjzyas.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gt2ddetpvbh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2nthszehq.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2xnkonzhf.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2jysmpqjp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2vfrqycpo.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.nanxinkj.top/Article/details/gt2psnkdive.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2xexutilu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdcwdnfp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2hviehblc.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gt2okwmkarx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangshuangyany.cn/Article/details/gt2owiiuomv.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2glmygwwr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzlmwylt.html

Py:   pickle.dumps(obj)
来源：http://dali.cashguo.top/Article/details/gt2mkiddhzr.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2gffyivvi.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gt2pjqfutwv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2xpzpppqc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj202588.top/Article/details/gt2uedgnfcs.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gt2ncbwbdkp.html

Ruby: Marshal.dump(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2qadphcar.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gt2dffekybs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2xawcaand.html

L. 网络请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vznrbqxf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2tretrdrs.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kbeayxfe.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xuanzx.com/Article/details/gt2hawckxbi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenlongwang.top/Article/details/gt2nofbrlrb.html

JS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gt2jwukvewr.html

TS:   await fetch(url)
来源：http://dali.yj202588.top/Article/details/gt2hmajbocr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuanzx.com/Article/details/gt2zrtawrxc.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mhqrubhw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gt2zkhzaist.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gt2pvekazwh.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gt2umugrclk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj202588.top/Article/details/gt2mtljwexo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gt2tqlefsuh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.andypj.xyz/Article/details/gt2whtyshld.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzirykh.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.havefunace.top/Article/details/gt2smovjewx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gt2nptvvfwo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2crkorlfv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.316326.xyz/Article/details/gt2lsvxxrfr.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gt2sszewgxm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.wangdashe.top/Article/details/gt2myrqpbaz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gt2fhwjbsrr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gt2fqprglzm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gt2nmsmexcv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gt2qjwqlwpj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2ftgcoafl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jiagoushi.top/Article/details/gt2lgvmalxc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xltoanda.html

[L04] 设置超时
来源：http://dali.aizwys.cn/Article/details/gt2zfaetoak.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gt2qygtavey.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.fzhhl.top/Article/details/gt2ulxfrpod.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gt2wmlmpbgz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.meibo888.top/Article/details/gt2rmpjmfzz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gt2dfcvidnn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gt2fnxgqxda.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gt2rzgszhao.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gt2ctmxytnj.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gt2tbnkmygx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aizwys.cn/Article/details/gt2tdxeczih.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gt2joqzhnsv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2qpfiegdb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gt2trsskpfk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigufen.top/Article/details/gt2bpoiazuk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhengqikj.top/Article/details/gt2mpctival.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.redwolf501.top/Article/details/gt2ookxrimf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2kjgrsstt.html

[L06] 解析响应为 JSON
来源：http://dali.316326.xyz/Article/details/gt2ixrgkxnl.html

Py:   resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2wyqxyzlk.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2fqhkibbz.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2tlqwvpwr.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2drssqydd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2affjunpb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gt2mdntaaed.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gt2dphnnshr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2iqcftpeh.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxclifzb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2efyhapwd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2twifvcqn.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gt2ugrbtrev.html

TS:   resp.ok;  resp.status
来源：http://dali.zhixingplan.top/Article/details/gt2rsbraalx.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gt2mgrybwpj.html

Go:   resp.StatusCode
来源：http://dali.smart0.xyz/Article/details/gt2ysoffhcc.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2dherhpmy.html

C#:   (int)resp.StatusCode
来源：http://dali.chenjidiqi.icu/Article/details/gt2agxjgisa.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wafwjrhl.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkftncwo.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gt2bcxyzymq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2igsvgvjf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2obyyldjm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxxmodij.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnwpspln.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2hsqtpotj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yangfankeji.com/Article/details/gt2iipujcxn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2epqdxxrl.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gt2jmpdpmjk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2scnmwlxf.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2qorugrft.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gt2astmrpkr.html

PHP:  $argv;  $argc;
来源：http://dali.ppjwa.cn/Article/details/gt2rxpxemnm.html

JS:   process.argv.slice(2)
来源：http://dali.guannengcc.top/Article/details/gt2yhixpycu.html

TS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xvpzzhsh.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2uiwhtmer.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2vkwzspqc.html

Ruby: ARGV
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrsrfwic.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2mqqblbty.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2vpluqcqo.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcamuqzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cbveqfzm.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gt2fkdqwfvm.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2aotmcufm.html

Java: System.getenv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2qhqvupdi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2nnzclttg.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gt2evhesyix.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2hhzrfvtb.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gt2onmcolls.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vcruvwxj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhongyouzk.top/Article/details/gt2gunmepqn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sweek.top/Article/details/gt2mnibalmq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2xaezkauo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gt2fzmphvqq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjsjoqcv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sysykeji.top/Article/details/gt2mxopigsm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2tioolmqy.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2lzykghcs.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2afnpirxl.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gt2codwaijx.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2djbxroep.html

TS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2xobjvzfk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yongpay.top/Article/details/gt2qwvqwcsp.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2gkxichzy.html

Ruby: Dir.pwd
来源：http://dali.birdmap.top/Article/details/gt2njxxvbab.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gt2hcebzlis.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gt2xhkbqzld.html

Py:   sys.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2iyaqmlqs.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gt2gltdixbp.html

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2lqonnqyp.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrefjzwb.html

Java: System.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2exnumqrq.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gt2eecublnd.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gt2zmaxpvzz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aizwys.cn/Article/details/gt2lzwnarni.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gt2qmdsygij.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2ixogmuzw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gt2ivdxtzwp.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2lkznsryj.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2hjtjaacv.html

Java: System.err.println("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2brmnnghc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ndvgmeie.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gt2owondset.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sxryk.cn/Article/details/gt2twppjxxe.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2rpghomja.html

Py:   if __name__ == "__main__":
来源：http://dali.kuanghao11.cn/Article/details/gt2vrevcayh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2strxmvxz.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2bkgznlgl.html

TS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2twbtvqlc.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2dxbxuxap.html

Go:   func main()
来源：http://dali.zhixingplan.top/Article/details/gt2asqjtauh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gt2ykkdlfvv.html

C#:   static void Main(string[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2dqaszirm.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gt2jgemggxf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gt2stnpptzr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.quarkkingdee.top/Article/details/gt2apvjqgqg.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2ugezsxbt.html

TS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2vblesglt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gt2aseufsmi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gt2nwwxrrru.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xinyue.icu/Article/details/gt2jhsrntrq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2szwvdtkz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fvoywihz.html

N. 数据结构与算法
来源：http://dali.yangfankeji.com/Article/details/gt2zilqbntj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2nrffxyyz.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2uhojcvpw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xrkqdoqd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2vyysktmc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2gerwknkh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2bimlepwj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzuyydhp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2emcipsal.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dyzecwtl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2cedkhywe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2hkulbonz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gt2fxkhlkdb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gt2oqlmislz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2tgvnseoe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2tvxtkegv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2malozcat.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2jeigxmfo.html

Ruby: arr.sort
来源：http://dali.hfpthk.cn/Article/details/gt2jscodrrf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gt2qmfxamon.html

[N03] 快速排序（分治示例）
来源：http://dali.zycfv.cn/Article/details/gt2qvmwiqvb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gt2mmkbowqk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.quarkkingdee.top/Article/details/gt2kskwdsnd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gt2hyfltjwb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2mkekiahn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhengqikj.top/Article/details/gt2tghhendz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gt2vnpatkhe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gt2hgjululr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gt2dhbyzeco.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2tqkvhlun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2zjpzhfgf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvawuukq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yvatxjso.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gt2xuxiboyb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2rizzbmge.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gt2gheqtejb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2vvcxcxog.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2xbjrpdgx.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gt2tbsoqhiy.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2fudzicco.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gt2puaxwglx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2xiynycwe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2kzmqcicx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gt2eitigjhi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gt2yvqblyod.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gt2sogggygq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gt2yvsrtfsk.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gt2tntaopwu.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2cfawolkl.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gt2gtuwsxox.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2kgrwdihr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2ludchdri.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gt2fjxarwrr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxahnwl.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2grfsccgp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gt2oxerxyos.html

[N07] 两数之和（返回下标）
来源：http://dali.zycfv.cn/Article/details/gt2bhxwzniy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gt2dnnsfmlj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2bambricj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2jkymtwwb.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gt2tsfmvfap.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gt2kzoutdbv.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2wahsmvcs.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iizzzpsd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2bztzlqoh.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gt2nirzbmke.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qznwbbis.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gt2enczfnmh.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2rfkmtckp.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2vkzfkucf.html

Java: // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gt2xckfjtdi.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2gvsqwhkr.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gt2cgcxdrjx.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2glrkumex.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2uwplibbv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2hrsxznlx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2crgaxzcm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkdqwdgi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bfkzbgxl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2utdntnef.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mfsnxqww.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2dxsbxoaq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gt2uqkyjzil.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gt2oqtjmjvd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gt2lkgersvv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gt2akbeaeyi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhdciln.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gt2fwprpeue.html

Java: class Node { int v; Node next; }
来源：http://dali.gotoacloud.top/Article/details/gt2vajryxdc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.vqdsnc.cn/Article/details/gt2qhqvflgb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gt2vuyrskxp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2edasyozv.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gt2lcfdhffz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehvbzzlg.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gt2hlabbcnf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gt2vntlihoo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2rksmbmhz.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2uokzfadi.html


<!-- 参考信息 -->