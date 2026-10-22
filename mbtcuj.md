代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.cashguo.top/Article/details/gt2xbdogbjb.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gt2qmxnwkim.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.nwbrower.top/Article/details/gt2wiuxboyn.html

JS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2rehijnxb.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2pnsmbcqm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gt2fbjpjhie.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqvkkjru.html

Ruby: JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2uzdkahhd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ondiynve.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenzaomai.com/Article/details/gt2aifbsvfy.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2dxqxasrq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2ugeztzih.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2tukiddsx.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.iojbl.cn/Article/details/gt2cxzqvzxe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tian-w.cn/Article/details/gt2fwizckcg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zycfv.cn/Article/details/gt2qsairpyn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ukucniyj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gt2jrwyyrnh.html

[K04] 读取 JSON 文件
来源：http://dali.meibo888.top/Article/details/gt2bncwdzll.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2yelmkcma.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gt2wcqbkfdl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gt2lelyslab.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlfnmjwh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2kscfyqqp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.wangdashe.top/Article/details/gt2gsyzmsqt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xylfe.cn/Article/details/gt2piohmyyn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gt2tiuiurcp.html

[K05] 深拷贝对象
来源：http://dali.jqgfzy.top/Article/details/gt2ofyqsrzt.html

Py:   copy.deepcopy(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2fzenadtn.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gt2ciasylxt.html

JS:   structuredClone(obj)
来源：http://dali.andypj.xyz/Article/details/gt2gsaarbuc.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2wzoiahtj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenlongwang.top/Article/details/gt2zplwjgqz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gt2epdjlfty.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yonumen.top/Article/details/gt2wrhrvzcp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gaohongyu789.top/Article/details/gt2gcyzgyoh.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgzfqngo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gt2uqxwbjcr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ialhrbuz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cdnleiting.top/Article/details/gt2uoeyapba.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gt2ykptvupl.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gt2szpbfvdw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2oyzfmbta.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gotoacloud.top/Article/details/gt2nytnnedb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.quarkkingdee.top/Article/details/gt2csjbfjqz.html

[K07] 进制转换
来源：http://dali.xziqi.cn/Article/details/gt2fkssfntf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2hactxoqa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhoulong.xyz/Article/details/gt2uzcnzqcx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2sjfkbqux.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gt2jtrfithe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2gmmippqi.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.iojbl.cn/Article/details/gt2fckyirzo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hysaishi.cn/Article/details/gt2yrjnqbqa.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gt2fbzzjyoj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gt2nsyjoirx.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gt2yzrehugt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gt2kexdgwzl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2czkdjyni.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxinkj.top/Article/details/gt2soejfeqj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2fqnaqrax.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gt2myppwwvo.html

Ruby: Marshal.dump(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2rcclddgf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gt2crpypkkp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2zuxcaglg.html

L. 网络请求
来源：http://dali.aizwys.cn/Article/details/gt2yqmgtkry.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2qjkpvfia.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gt2nwdqsctl.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gt2ujnlmkuh.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuetiantiany.cn/Article/details/gt2khndulji.html

JS:   await fetch(url)
来源：http://dali.9152youxi.cn/Article/details/gt2maacpwzs.html

TS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gt2uvkqlxna.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.daria6918.cn/Article/details/gt2kdvfbjgp.html

Go:   resp, err := http.Get(url)
来源：http://dali.dashuyun.cn/Article/details/gt2hksueacs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhoulong.xyz/Article/details/gt2olqfukzx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aizwys.cn/Article/details/gt2anyarelj.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crwufwan.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shzxlz.cn/Article/details/gt2jrkzjdib.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wuxtqjts.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gt2odrsmjzz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.aibaodan.cn/Article/details/gt2iiacnwdy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2vugyhead.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2nilhnqhn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yongpay.top/Article/details/gt2cicyjfrp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2houweaqm.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2hwidblmn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjexztga.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gt2rorexmsw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gt2kkgrrkfx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gt2hejbqkzy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jupzkbjf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gt2xwhhbiez.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.havefunace.top/Article/details/gt2xejnsbrl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2vjotelvs.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gt2ebrhtqtr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2atrhyeto.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gt2jomcvxlj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gt2ldcibfdk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ehwqpu.com/Article/details/gt2kngqqese.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gt2kpvljtmg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cdnleiting.top/Article/details/gt2yeketvbr.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2piyajdyr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gt2laezzlsd.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2pvpaefmr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2azntrsob.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsvupzun.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gt2rsjahaiw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2nowaerjw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangdashe.top/Article/details/gt2rnahvdxg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fengsongda.top/Article/details/gt2dfpxpvaq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.meibo888.top/Article/details/gt2freyfxub.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2uftgzvtw.html

[L06] 解析响应为 JSON
来源：http://dali.zhixingplan.top/Article/details/gt2xrhyzpfu.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2rjaxjvzq.html

PHP:  json_decode($body, true);
来源：http://dali.nwbrower.top/Article/details/gt2cqqeyfmu.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gt2rziwsazz.html

TS:   await resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2laaadgtr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2ulqgyctv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.haohaochexian.top/Article/details/gt2ycaaibms.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gt2qtyjvnhs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gt2flpifgoj.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2wextksvj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gt2ajqmbksn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gt2rozoemkq.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gt2vwacrtgu.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2rqwzsyne.html

Java: resp.statusCode()
来源：http://dali.cucudq.cn/Article/details/gt2clxtmihu.html

Go:   resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2dqosyrcm.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2elthwkdn.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2pnbddvfu.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2ojszfjyb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gt2diiwnrwp.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gt2xycfvrjb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2luepwvdv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2ihneublh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj20258888.top/Article/details/gt2wnkreelc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gt2bckwbzkx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zdqjudy.top/Article/details/gt2oolzkurt.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinqigfzy.top/Article/details/gt2hldbycqf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ltlujjdy.html

M. 命令行 / 进程 / 环境
来源：http://dali.tianlin.xyz/Article/details/gt2ujdkuere.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2kmypttes.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2gvfmzyss.html

Py:   sys.argv[1:]
来源：http://dali.chenzaomai.com/Article/details/gt2zerdcmcf.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2zhejahmi.html

JS:   process.argv.slice(2)
来源：http://dali.tian-w.cn/Article/details/gt2sbzbprqb.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2dbcfukjn.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2goyllpmp.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2pqgdousj.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2zhczvchd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gt2pawoxcvc.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gt2mdykirfy.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2zwaujaeh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigufen.top/Article/details/gt2imxocivq.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2yirdxccp.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2iusxlgjj.html

Java: System.getenv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2rwnegepq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2wzczgwec.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gt2vcavxlwu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2seobnfio.html

[M03] 执行外部命令
来源：http://dali.guowangkeji.top/Article/details/gt2bihgvjvq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2qgkzhnum.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gt2hqlgnsdz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gt2ldhgxdrb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzkkbtav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gt2ihtvenps.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gt2ihxpzycx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sufxvd.cn/Article/details/gt2oetfoyvp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gt2hzccfbaz.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2zshzolfw.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gt2wkwozxjc.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gt2yvfsnudd.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2wnqzuotf.html

TS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2qbuyddux.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gt2fstxydfn.html

Go:   os.Getwd()
来源：http://dali.chenzaomai.com/Article/details/gt2mxrpkjjb.html

Ruby: Dir.pwd
来源：http://dali.dianchejie.cn/Article/details/gt2wtlzlyhn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gt2heuhhxps.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gt2ribdyabc.html

Py:   sys.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2pwbhymtw.html

PHP:  exit(1);
来源：http://dali.svipenyu.cn/Article/details/gt2ndueijgk.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2qiixwlyc.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2yhpluvtu.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2hndigcov.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2akwozhim.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gt2kjlxcpqt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ydzc1.top/Article/details/gt2ypygbqry.html

[M06] 向标准错误输出
来源：http://dali.daxiang520.top/Article/details/gt2iwlpydzd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gt2sufjewyb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2lyvnhjhv.html

JS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gt2jtzirqmy.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2bmivijfv.html

Java: System.err.println("err")
来源：http://dali.smart0.xyz/Article/details/gt2yvakpwoo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gt2qfuxjgot.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gt2hnzjnnmk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gt2fjbjleyd.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gt2tdsmhflg.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gt2jsfznoxg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gotoacloud.top/Article/details/gt2uabghkwb.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2usmvwmul.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2rfnojzyu.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gt2kdigmbqj.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2awsjtlyh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.c1oappe.top/Article/details/gt2kldrsmys.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gt2cuodpwvl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gt2qbzwretx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gt2wziqwlhg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gt2dsihgjhv.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcguztge.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhctcbpe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gt2nrdynmnd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yanxiufei.cn/Article/details/gt2qczstoye.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsuseyhs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gt2eksmrikr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2axetcqzf.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gt2mtodihly.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zbxqaipk.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gt2hgvhavvx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2icvcuguz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gt2dhfxuthx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2vqudapqe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2isfggljo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvyjzwqi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibciyuod.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gt2txdyzvnp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2crrjbzok.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxuanxn.top/Article/details/gt2eldrxrxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2auldsgkv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gt2pcbsgiqp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gt2dunrgaah.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2cuuamdoo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gt2rikcqmzq.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2uejylrpu.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gt2kofzqlnt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2chdnodra.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qntnzbne.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2zmafiqsp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gt2aysdhair.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2gkpkmjzv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2sqhhtsiv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2bystrmkq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gt2axlkbwfl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gt2bsonbtii.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iubdvgkr.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gt2dboxacpi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gt2wohuqhpz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gt2dfcasfvo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2ehjkdwnd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2fcslsjoa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gt2fzutldjm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2fuderqhy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftmdkyad.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2nlhokvvy.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gt2olswkwii.html

Py:   math.gcd(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2tyezegxw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gt2pzwxmrzy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gt2tqwksjle.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gt2gxdlasqn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgyipbup.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gt2neuweyxv.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2mwwaxwqq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gt2feybrpea.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gt2mxlglcmm.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gt2ysqzuxvv.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2zvxtshwq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2zcfydstp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2yiqoawqc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gt2zeknuqug.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gt2vbqrchou.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gt2vpnrvzen.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2bhftxvje.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gt2yxcptgkn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gt2azrzivcq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gt2wxrnpvxi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tian-w.cn/Article/details/gt2gbantiyv.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2vfdicwxv.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2wbybnpzy.html

Go:   // 手写 map[int]int
来源：http://dali.iojbl.cn/Article/details/gt2cqfbzsby.html

Ruby: // 手写 Hash
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyniybun.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2lhmnjmeh.html

[N08] 生成全排列
来源：http://dali.aibaodan.cn/Article/details/gt2ezmobmdm.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2stjmogug.html

PHP:  // 手写递归交换
来源：http://dali.iojbl.cn/Article/details/gt2xmpgouos.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhphijdw.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmwqeyqu.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2csyhjxfh.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2invpwfuw.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvnqhtwc.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2vtvkwstj.html

[N09] 栈与队列
来源：http://dali.hywenlv.cn/Article/details/gt2asahtbyt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmebfrmw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2xjokuugi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2idljkqxl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fengsongda.top/Article/details/gt2idxhsnwt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gt2yazlxmgf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gt2ghucwuol.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2hlfeyhdd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2egclblsg.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2ujorjybf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dianchejie.cn/Article/details/gt2mouuwwxi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvmvpxiw.html


<!-- 参考信息 -->