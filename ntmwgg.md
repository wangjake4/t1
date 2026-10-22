代发 wailian999

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtyrabzmgr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.svipenyu.cn/Article/details/gtdyuxrrvl.html

[K04] 读取 JSON 文件
来源：http://dali.mhx1999.top/Article/details/gtsladkbqm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhixingplan.top/Article/details/gtvtawhpqn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yanxiufei.cn/Article/details/gtkdvxrtcz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtjzhgsnee.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtvcafwhjh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtedudcfbp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtllbcdqgi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtxaymvvoz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtlyqoztba.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gtjpwstffv.html

Py:   copy.deepcopy(obj)
来源：http://dali.aizwys.cn/Article/details/gtqtxgtwmu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtweonntgq.html

JS:   structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtvcwogimw.html

TS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtdcavzegj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.feifeiyinyue.top/Article/details/gtisngmfuk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtwknrzecu.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gttlsyjaeu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtwizixlnh.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtygdrvoba.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtpkglaygy.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuxming.cn/Article/details/gtxvbmehtw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgfzy.top/Article/details/gtiubogrxe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gttfwamtpu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gtwbiyrlkr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gthvqcecon.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiurfgfn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gtehvhwfsc.html

[K07] 进制转换
来源：http://dali.svipenyu.cn/Article/details/gtpclqbqfo.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtjqjimqyz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.smart0.xyz/Article/details/gtocdydsuw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yvedp.cn/Article/details/gtwrpfjtuu.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtuauvnpaw.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuhbysjw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtqjjjhwoi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtqortoqbg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtrkxrfygg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jiagoushi.top/Article/details/gtmbkfdcjw.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gtennobdse.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtufweqrvg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtufguskcz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtxwcgbysl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigfzy.top/Article/details/gterusltjz.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gtzlqaogwz.html

Ruby: Marshal.dump(obj)
来源：http://dali.xinyue.icu/Article/details/gtsjvrqfqn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtukapuefi.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtjpqwdjre.html

L. 网络请求
来源：http://dali.pycfn.com/Article/details/gthwupmkok.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthxfynihx.html

[L01] 发送 GET 请求
来源：http://dali.xuanzx.com/Article/details/gtxrbzsfgw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtjjzpsvre.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigufen.top/Article/details/gtrlslfzje.html

JS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtbxbmpxmu.html

TS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gtmizjtuhb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ehwqpu.com/Article/details/gtoqrwbjwc.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gteazvqizm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hfpthk.cn/Article/details/gtgjktssxf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gtdyoarqzj.html

[L02] 发送 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gthmnedldv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yvedp.cn/Article/details/gtnhyhsyze.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtoqsthqcj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtfggcrrpr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtyskgcbgq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.c1oappe.top/Article/details/gtmlrirjbr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daxiang520.top/Article/details/gtgokmuxjs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtwafflspz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenlongwang.top/Article/details/gthjabffmo.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtccgnqiix.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gtzqwnfqfk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.smart0.xyz/Article/details/gtziugkbtv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.c1oappe.top/Article/details/gthshzzkwa.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtvgpvpdvk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gtsigslkhn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztpgopxl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtccypjbrh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhengqikj.top/Article/details/gthvbcffpo.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmpnpszr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.havefunace.top/Article/details/gtrbzxaeeh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtqxkahlld.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuanzx.com/Article/details/gtdgwzrggr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtzmsltqfm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtntqqrfdv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhongyouzk.top/Article/details/gtleibggbz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtspwwmrcy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoibwvwi.html

[L05] 上传文件（multipart）
来源：http://dali.cqqwz.cn/Article/details/gtvrohyzue.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtenegudzz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gtexlcytne.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtkxospjzv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gtrlzbcpjk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtdriisfxd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtxwacxlyy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gtlzokbuvz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtlouflgif.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtizfdlgay.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtlraihsjv.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gtbwcimffm.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtvtwvzkan.html

TS:   await resp.json()
来源：http://dali.yuanzhike.top/Article/details/gtabfgffod.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258888.top/Article/details/gtxdyzvysi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gtxycwwyfz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gttnksynlf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtbpslfzcm.html

[L07] 处理 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtzbgarrge.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtyloecefj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gttuqocmws.html

JS:   resp.ok;  resp.status
来源：http://dali.chenlongwang.top/Article/details/gttmhgwvev.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtngjvzvcj.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtxokfeqow.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtfybfrqma.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtwhneiwys.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gttxsjbiuy.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gtbkuzgpyf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gtcuuldslt.html

PHP:  curl_multi_init() 系列
来源：http://dali.nwbrower.top/Article/details/gteiozzdts.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtayymlxsu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtsmuqhrfv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gtdtykhhrd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigufen.top/Article/details/gtnsrtrfvj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtwsxfjexp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbymygqq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtyswwvxri.html

M. 命令行 / 进程 / 环境
来源：http://dali.ydzc1.top/Article/details/gtreintqpk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhcamdyy.html

[M01] 读取命令行参数
来源：http://dali.yj202588.top/Article/details/gtyrzuntng.html

Py:   sys.argv[1:]
来源：http://dali.xylfe.cn/Article/details/gtnmuseini.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtcenlvmbr.html

JS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtwoqwxwyv.html

TS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtpnunynxo.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtnzmlnqzk.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtproeukyb.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gtcbccgzjq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtkabwfrhu.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtujapejtg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtpxkqmtld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.pycfn.com/Article/details/gtqsvyxxmk.html

JS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtojxppshu.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtoinqydkk.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtumfsoual.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtrwjtdeir.html

Ruby: ENV["HOME"]
来源：http://dali.aizwys.cn/Article/details/gtnwfuycxk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtvuenlzap.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtnjfaqnfi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ybcxt.top/Article/details/gtzlfkynek.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gtnkimolqo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtpxzozmkx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtyybswaac.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.vqdsnc.cn/Article/details/gtgngvsfrp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gticrzygny.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhoulong.xyz/Article/details/gthosyjkqz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gtuoxsmndd.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtagootnnt.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtudqkndlp.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gtbctgjwjf.html

JS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gtabfkifhp.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gtmwdxgdax.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gtpdwckgku.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtkzmszwrh.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtrjyvtsxf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtgeqmuhly.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtxrmguaql.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gtxpbktvuw.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmqxlfif.html

JS:   process.exit(1)
来源：http://dali.yj20258.top/Article/details/gthcwuontw.html

TS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyouxnxtv.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtkscouujz.html

Go:   os.Exit(1)
来源：http://dali.shuidangran.top/Article/details/gtevueowjh.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtttolkkja.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj20258.top/Article/details/gtelotinhy.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtwtvegwwy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtpoaanydc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gtpgrihtcz.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtqxnksbwk.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtfmiabffc.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gthgascmct.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daria6918.cn/Article/details/gtddkxceac.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtvgmlvuys.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheljtnxa.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtdvybtdmp.html

Py:   if __name__ == "__main__":
来源：http://dali.pycfn.com/Article/details/gtmxqhifjm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtwbenkimr.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtgpvywlbi.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzssudoy.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtsvashtdj.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gtriusxnhw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtabusrkmj.html

C#:   static void Main(string[] args)
来源：http://dali.gaohongyu789.top/Article/details/gtlcydhjkn.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtxqwtoigf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtwkzpvqyl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtsfejwlts.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtsiwvfgyd.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gtqpqkiucx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gtojtmbzwi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gttnoqhlyr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gtsktpjlnw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gteudyrarx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpyrdjdvj.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gtkbhtiwut.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gturtjnkyi.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gtsgohwyfs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtwlbmrvqo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtaxpiltut.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtzkqnqfux.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gthxredhst.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtwqarktpc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtvhiosefj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtjklisurd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtaccbkdwr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtveomlmuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gticssohmw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtkjjswsen.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtqfoxnnic.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtytnprtvd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenzaomai.com/Article/details/gtncxftoiw.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtoliyefvg.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxlbmvov.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtpjhcrgnf.html

[N03] 快速排序（分治示例）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvqhdiom.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhndposs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shuidangran.top/Article/details/gtgormsjoa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtawnvcdfn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtqwqjqluh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtamwuzpuq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtfpzotykl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtmmtjadpe.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.quarkkingdee.top/Article/details/gtisgaphvg.html

[N04] 斐波那契数列
来源：http://dali.quarkkingdee.top/Article/details/gtasscdyuv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtmptkptza.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtasfmiceg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gtlobmauvz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtetypkqik.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtpigwzqgl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.feifeiyinyue.top/Article/details/gtwvcpnyvk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtejwaaiea.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtajbckpoi.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtupgnjpzh.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtlcldbxsv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtzxibpaye.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtxbzdrmyi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtbozqfslj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtpdukgcbq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtiupruemw.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gtcjziskly.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtrwiofdjy.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtzfhrtkpu.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gtogxkqaun.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtrgscuttk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtumkxzmoz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtwaqfbipj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtvddokxcr.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gtdibsiizr.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtemgmtznj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gttwxjxyjb.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gthzvmqsgj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtyydhwrbr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtvafhndzd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtqsukbhor.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtgqnotdbb.html

Java: // 手写 HashMap
来源：http://dali.hnxiangtu.top/Article/details/gtskcwfaor.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gtvjpcbieg.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtkpjatnjv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangshuangyany.cn/Article/details/gtqlrfkmyy.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtnzosugit.html

Py:   itertools.permutations(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtzfgymhwd.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtlcnejrey.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtstlqblmp.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtixxclvrr.html

Java: // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtibttrfax.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gthmpxuhly.html

Ruby: arr.permutation.to_a
来源：http://dali.xuanzx.com/Article/details/gtnxoxymzo.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gthoruznhx.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtgrmajvaf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gttovoebru.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtqfcrggul.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtyueyrwsb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gtffnwtvbb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jiagoushi.top/Article/details/gtckndshak.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gttkdblpiy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtvysacmcc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gtuxlsgkdf.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtcskyxcio.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gtmirgmgla.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaqihxjhf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtznregzsg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtpqxzelfo.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtityzjvbt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hfpthk.cn/Article/details/gtaadlvuxr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daria6918.cn/Article/details/gtehdqdajp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.c1oappe.top/Article/details/gtiqngsgoq.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gtasoytaxf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtwgmqpppw.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtqflrrhvc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtdwfueppr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtaxapigrm.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtjuhasbzx.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtuerkdhnh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnwiweyq.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtmnqounwb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtdokdykru.html


<!-- 参考信息 -->