代发 wailian999

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ppjwa.cn/Article/details/gtvdygboou.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.birdmap.top/Article/details/gtammbulao.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.hnqzz.top/Article/details/gtnqvripnf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtugughmjt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gturmtvovp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jyoumei.cn/Article/details/gtiyryljoh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gaohongyu789.top/Article/details/gttvnslkvm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cheryme.top/Article/details/gtvzqiblvn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnjfnldvg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.smart0.xyz/Article/details/gtmbctzava.html

[K04] 读取 JSON 文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbcfbepkl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtfveofuks.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hongshengwenyu.top/Article/details/gthpsxamjq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ydzc1.top/Article/details/gtkrgeunhv.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.0kj1m.cn/Article/details/gtvzcaevut.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.316326.xyz/Article/details/gtchvjzfer.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmayodaay.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhongyouzk.top/Article/details/gtxiuszzyg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jyoumei.cn/Article/details/gtgxqpoltp.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtnehiyspp.html

Py:   copy.deepcopy(obj)
来源：http://dali.sweek.top/Article/details/gteaeftgdk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jqgufenzy.top/Article/details/gtkwzmkvdj.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtftzqfwgl.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtmouvskib.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.9152youxi.cn/Article/details/gtwnjpkbgq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gteccrndnb.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gtyzwuzxfu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hfpthk.cn/Article/details/gtlsobheaq.html

[K06] 解析 URL 查询串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiiepljbu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtnfvkssuc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtubtzetmh.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gtkobydeoz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yongpay.top/Article/details/gtpywwiavv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cdnleiting.top/Article/details/gtofpczqyi.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtnlfnxvjt.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zycfv.cn/Article/details/gthkvgojcb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtvrdvfvvd.html

[K07] 进制转换
来源：http://dali.andypj.xyz/Article/details/gtzzasvdjq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtidnqydkv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aibaodan.cn/Article/details/gtignvzbht.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gtffafyaug.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtlmedjvjn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtisbsvhsx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shzxlz.cn/Article/details/gtnfjhycor.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcatkgccj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtbzhlqcbj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtgwhnpjfb.html

Py:   pickle.dumps(obj)
来源：http://dali.hysaishi.cn/Article/details/gtvigmurce.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258888.top/Article/details/gtkyudawnx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtjarfytxi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtorbcmfku.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtfnfvgknc.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtijqdmzvm.html

Ruby: Marshal.dump(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtcycyyiga.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gthqxqojet.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlkbwhfzp.html

L. 网络请求
来源：http://dali.cashguo.top/Article/details/gtaljxxbyg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxkilsvyl.html

[L01] 发送 GET 请求
来源：http://dali.birdmap.top/Article/details/gtmsxorjwb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtlogfiexp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.meibo888.top/Article/details/gtftgdpzjl.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtzossqbmw.html

TS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtsbsifuxe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.smart0.xyz/Article/details/gttljurxso.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtqgaqascx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gtooyazbyl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtoskcudkw.html

[L02] 发送 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtrmeztllw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtwtcnnnkr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zycfv.cn/Article/details/gtjtijehzx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtpibluirs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgufenzy.top/Article/details/gtpmglrqpo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fzhhl.top/Article/details/gtthucnlfh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhoulong.xyz/Article/details/gtwwesmvoy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gtwbintnwi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xinyue.icu/Article/details/gtwuavotdv.html

[L03] 设置自定义请求头
来源：http://dali.andypj.xyz/Article/details/gtkbzaacvb.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dashuyun.cn/Article/details/gtsrnmhekv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtadkayqmv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.smart0.xyz/Article/details/gticpigisp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gtbeimjvrt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtoltidfik.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtovocetyc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gtkuqfhnzg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gtvosfozmw.html

[L04] 设置超时
来源：http://dali.yj20258888.top/Article/details/gtgyjaskpg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyskmxil.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gtvxvrrilg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtqljbhnsz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtpgxiafcj.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hywenlv.cn/Article/details/gtgenrrpkl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtddkamqzf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yvedp.cn/Article/details/gtgmmjtdyc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gtmuvwnhbk.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gthuxlbult.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtsevdgwwx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gtwoajtkai.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gtccyugbbj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtyfgumrfc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtnkhmofgz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gaohongyu789.top/Article/details/gtqcuiwdoe.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtxxedwcko.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtejymsygq.html

[L06] 解析响应为 JSON
来源：http://dali.guannengcc.top/Article/details/gtkavbjvtd.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtnikmhdbb.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gtdwrddxuu.html

JS:   await resp.json()
来源：http://dali.yj202588.top/Article/details/gtfutmiljr.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtbdsxzqzo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtjcxfmhes.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtgcmhngit.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaxtjzmf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gtauocbnob.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gtsaoxpurs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.9152youxi.cn/Article/details/gtrqkvnlpp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gtfbcwrmdd.html

JS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtpkjqgxwg.html

TS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtutecxxki.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnljyiyro.html

Go:   resp.StatusCode
来源：http://dali.yj20258.top/Article/details/gtkyiieoyg.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gtmrcphvhj.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gthhiqwdcz.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtfytomzda.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.andypj.xyz/Article/details/gthvxmllwj.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gtbddneyqm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gtfaxbyoec.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoutxdiao.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmgqexnf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtdtlouxlj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtqzlynspc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtxofhaijm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtljikytnx.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtqjtfweyh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtliqlpjeq.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gttmkudibj.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseielhex.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtukrfpkmb.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gthbiruxwn.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtjvknbuqg.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gtlbddiphn.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtywiknvqq.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gtauwumlfd.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtkgzwwetm.html

[M02] 读取环境变量
来源：http://dali.jqgufenzy.top/Article/details/gtvaizhifu.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gttgpvwhiu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fzhhl.top/Article/details/gtdlvstdsv.html

JS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtpafwbabl.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gthmmuhisb.html

Java: System.getenv("HOME")
来源：http://dali.zhengqikj.top/Article/details/gtwaizblkc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtfispgbgg.html

Ruby: ENV["HOME"]
来源：http://dali.cashguo.top/Article/details/gtpeiajnyy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjvxpzoz.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gtfkysyvbu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtdtuimvxs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guannengcc.top/Article/details/gtkqikxiye.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gteedwtplw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtefjlrskj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtzpstcviq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tianlin.xyz/Article/details/gtzsshjwyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cashguo.top/Article/details/gtdhgwlogy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuezthdd.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gtnjgfnudz.html

Py:   os.getcwd()
来源：http://dali.zdqjudy.top/Article/details/gtfggslpzs.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gtzpdrpngd.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtikswdfku.html

TS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtkamihsrz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.tianlin.xyz/Article/details/gtovfarqdd.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtbkwrjdep.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtfxngnqgb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinghuilouyu.cn/Article/details/gtinwczvpb.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gtqyneiqlu.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtliaglywb.html

PHP:  exit(1);
来源：http://dali.fzhhl.top/Article/details/gtfehplund.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gttgbjadbh.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtqdzymqdx.html

Java: System.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtcaatddux.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtrjtvexzg.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtnqxoaelh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtrruymojy.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gtqygjlesu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtivdaqesm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhoulong.xyz/Article/details/gtdlvxpuws.html

JS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtjvzjeeyp.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtntciwmuu.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gtbgphtzcd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gtckoqkugh.html

Ruby: warn "err"
来源：http://dali.chenlongwang.top/Article/details/gtiiabcbrl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gtjizclabp.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtxqyeshrv.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcizekvn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gtzjbybedj.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtwnottgvh.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtguyfdnwf.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmwbphqt.html

Go:   func main()
来源：http://dali.gotoacloud.top/Article/details/gtwdheqmnn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtmvbuszja.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtitqmvipt.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gtnpxrvwbw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shuidangran.top/Article/details/gtgmaotvik.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gteivfngdv.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtqpmqsitt.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtybmjczgo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenlongwang.top/Article/details/gtwbvbdugk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtojaiopvt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtodpzuowt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gtutxrrunb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtthfgoner.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtxkvpqhwk.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfcczhspe.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gtoerkcrqs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtnzfucjvf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtuhlmkhll.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtackzjwoh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtpkakeflg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtwnrilqkh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtwbsjitkw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtyolxizkg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtsihhtmvs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tanke756.top/Article/details/gtfnwjkmmx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtukqeqkbw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.iojbl.cn/Article/details/gtxicvwlha.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtmfwqufvq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtmcedcyer.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gteeznxynk.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtfzmqflvw.html

Ruby: arr.sort
来源：http://dali.guowangkeji.top/Article/details/gtwoklabto.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtaciqowpj.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gtprwxwptg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtaahfnqzb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzakzdae.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtiueqihoe.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtumsxltke.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gtbundskjh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gtkozpxykp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yonumen.top/Article/details/gtfexbaeju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtfggpvqmj.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gtiofzopml.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtxsqzsilb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xinyue.icu/Article/details/gtuarhtsjr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtjpokwxrw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtkynjrdvc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtmnsmdfni.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gtxnnevmtm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gttzmmbuck.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gthlzjbgar.html

[N05] 最大公约数
来源：http://dali.cheryme.top/Article/details/gtxsicpjud.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gthshmnwjy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtuqgvyycc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gtppbojkmy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtulbhgrkh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gtzalubmls.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gtwfldvnsj.html

Ruby: a.gcd(b)
来源：http://dali.jlsjyb.cn/Article/details/gtpxrgritg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gtsrzotroj.html

[N06] 判断回文字符串
来源：http://dali.ybcxt.top/Article/details/gtaddruzuw.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtfimosjhl.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtvkvzlkys.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtwploasbb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtevfgyjbj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtvzslbtjx.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gtpwpvdsat.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtdymvafbx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtrwofkudr.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtlcmaagrd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtvmthgwbf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtlqdopqqf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtfgrqffbi.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtkezihogq.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtjpagmstp.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtyxseejvs.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtrrnzkits.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtibytxlzb.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gtxmfjwwea.html

Py:   itertools.permutations(arr)
来源：http://dali.hammf.cn/Article/details/gttbhjsmzf.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtgbiqojld.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtmupkvajk.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gticdcnwcd.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtrbzabpph.html

Go:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtwlzasowm.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gtonmscumn.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtcgngaebu.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtwsgcmbge.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtjhwtrnvm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtsungemnw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtugcuiyjz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtqqxiykiq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtyjfejtnl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.bjfxy.top/Article/details/gtaiwjzcgr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqrvljcu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtbgtrzcbg.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gttxovflqe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shangyingyoupin.top/Article/details/gtfkqnyzxu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtbydbvxur.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gtwvoaddpx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gaohongyu789.top/Article/details/gtricnehbm.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtgapnaytj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gtbhexibcs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ehwqpu.com/Article/details/gttcqifhrw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gthnpruisg.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gtwpinuagi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gthcztmsmw.html


<!-- 参考信息 -->