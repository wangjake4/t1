代发 wailian999

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gtndljqmki.html

Go:   json.Marshal(obj)
来源：http://dali.jianghu66.top/Article/details/gtttsrihjd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.gogol.net.cn/Article/details/gtqozwniiv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtzjehwcjc.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtcgohuiye.html

Py:   json.loads(s)
来源：http://dali.svipenyu.cn/Article/details/gtqnjfyoks.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtqhhqzvoe.html

JS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuxnvhho.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtggtdzben.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxuanxn.top/Article/details/gtbwythayv.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ydzc1.top/Article/details/gtskyrnlvf.html

Ruby: JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtrqgjsvhq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxinkj.top/Article/details/gtouucmoxq.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ppjwa.cn/Article/details/gtewlfdndg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgufenzy.top/Article/details/gtpoxlaour.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gttjrlzgcf.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.guannengcc.top/Article/details/gtjppgzaml.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aizwys.cn/Article/details/gtbiqiaeig.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtcfamgost.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ybcxt.top/Article/details/gtotepecdp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtqnbzzyrt.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenlongwang.top/Article/details/gtgafgecxg.html

[K04] 读取 JSON 文件
来源：http://dali.wangshuangyany.cn/Article/details/gtnkcnixsr.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yueranfly.top/Article/details/gtmmfdkwmh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtqxxgbtgl.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtgrfkgilj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aizwys.cn/Article/details/gtofrwbjmo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyutdgii.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.0kj1m.cn/Article/details/gtgpmyctxi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtxbbrimaw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtoejfoyht.html

[K05] 深拷贝对象
来源：http://dali.smart0.xyz/Article/details/gtjrcatsid.html

Py:   copy.deepcopy(obj)
来源：http://dali.bjfxy.top/Article/details/gtisueyxxa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyruefytz.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtcpspahpv.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtnhuxsitv.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gthfgyeaxw.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sysykeji.top/Article/details/gtmukncngk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.316326.xyz/Article/details/gtwphzvhzy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yueranfly.top/Article/details/gtdlfvrhlk.html

[K06] 解析 URL 查询串
来源：http://dali.yanxiufei.cn/Article/details/gtadjuemxj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhoulong.xyz/Article/details/gttcvllmjh.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gotoacloud.top/Article/details/gtarwlqjtm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xziqi.cn/Article/details/gtbundqcwv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtymrxjhgi.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sysykeji.top/Article/details/gtlwmzvtes.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtgvilasma.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtzxsaaera.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtggwsbwjl.html

[K07] 进制转换
来源：http://dali.bjfxy.top/Article/details/gttvamondd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtovzvhvvq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtcdpqhrfg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtzbdrqkeo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtczewjrwm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtjbxilywm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.fengsongda.top/Article/details/gtpytqavdi.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gtnnvtlcbp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtbrcehtvo.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gttjjgecfr.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gtwlkthfsq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nanxinkj.top/Article/details/gtsrpzsqdp.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gttudhtnrh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtjpyhrzki.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdyobxsa.html

Go:   encoding/gob
来源：http://dali.sufxvd.cn/Article/details/gtcslxiuwd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuanzhike.top/Article/details/gtvtovzdqm.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtmqqvipjx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbfadxeyc.html

L. 网络请求
来源：http://dali.fzhhl.top/Article/details/gteplszram.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gttjjftief.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtrjslzsls.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gthiniskgd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtapnbvuqs.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtpxuubtra.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtbmybremg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj202588.top/Article/details/gtfpqaijcc.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtaoqjdvnb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtmsempcsc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ybcxt.top/Article/details/gtkctzueop.html

[L02] 发送 POST JSON
来源：http://dali.yueranfly.top/Article/details/gtyhcmmvzm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.guowangkeji.top/Article/details/gteiancbtw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangdashe.top/Article/details/gtjlqvyfkv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtzsdivabd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtekbvsqlb.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.smart0.xyz/Article/details/gtmriupncn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.iojbl.cn/Article/details/gtpgicbfkv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbaebucwj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtykfmljpt.html

[L03] 设置自定义请求头
来源：http://dali.dashuyun.cn/Article/details/gtgozqagij.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yanxiufei.cn/Article/details/gttkdspbzp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhslkkce.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtubxdiwqt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cqqwz.cn/Article/details/gtghchgong.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtgoqufqvh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtotaqlysf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gotoacloud.top/Article/details/gtkrstjwug.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtetrpammc.html

[L04] 设置超时
来源：http://dali.xinyue.icu/Article/details/gtgdcmdcka.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yanxiufei.cn/Article/details/gtvybwyzkd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dashuyun.cn/Article/details/gtlbczxlfu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtlyufxgka.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtyxrdcpov.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtwhnlauhm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gthwyvqjzw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrhpbgcm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtzecggath.html

[L05] 上传文件（multipart）
来源：http://dali.chenlongwang.top/Article/details/gtxoyopmos.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gtowjjzwxb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtkrectozy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gthaewbljb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtrjgemlcv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gtvommrxnw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zdqjudy.top/Article/details/gtbhbzwaka.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.aizwys.cn/Article/details/gtuafmzxcs.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gtpxzdfpud.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gthquheyfe.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtqevsuprf.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gtwyihafdf.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtnaeftisa.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtsiyyyugh.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlctfcnhh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.nanxinkj.top/Article/details/gtaosjnsav.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gtvmgtttuc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gtalvnzebg.html

[L07] 处理 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtlvlehayu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hywenlv.cn/Article/details/gtovatswel.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yangfankeji.com/Article/details/gttibiaaca.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntdvalfs.html

TS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtfqwmlysg.html

Java: resp.statusCode()
来源：http://dali.gzhubu.top/Article/details/gtwqwnmzan.html

Go:   resp.StatusCode
来源：http://dali.zhiwuduotai.top/Article/details/gtelhwkcew.html

Ruby: resp.code.to_i
来源：http://dali.vqdsnc.cn/Article/details/gtwljcnyab.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtkjihjinj.html

[L08] 并发请求多个地址
来源：http://dali.nanxinkj.top/Article/details/gtesyfqjin.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dianchejie.cn/Article/details/gtzmvizwgw.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtsguwvwvi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtpzemnofc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gtuliqoeot.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gtyqnydkei.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gtniozfucj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtfagjaaem.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xinyue.icu/Article/details/gtcyfzxcdd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzkvvwsx.html

M. 命令行 / 进程 / 环境
来源：http://dali.feifeiyinyue.top/Article/details/gtfsusccrv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwqcyyqzd.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gtrpzekiyi.html

Py:   sys.argv[1:]
来源：http://dali.ivvv.top/Article/details/gttesnzdco.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtveghtosr.html

JS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtymxicilh.html

TS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gtbxjlwhqg.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtebwjsrnc.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfitactwa.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gtgztfjzfe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtsfknumut.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gtqzbhxekm.html

Py:   os.environ.get("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtyauqniap.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtdjtffiei.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtwwblkhnp.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtdtscszyb.html

Java: System.getenv("HOME")
来源：http://dali.nwbrower.top/Article/details/gtmgxdzxav.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtlqldskod.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtmxuwfvzu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtvruyqwsv.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtpoxemkpi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtnsyeahir.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gtczwcjmht.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gtafnbtnsi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtaiwxvmjv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtecvzpjxy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tanke756.top/Article/details/gtektlfhbp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtngzbijyl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtadfbmtdd.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtnzawzjzb.html

Py:   os.getcwd()
来源：http://dali.smart0.xyz/Article/details/gtvwhevwhb.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtnohtttvl.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gtnnmxanwp.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtmqqpbdoa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtojbajnfr.html

Go:   os.Getwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtyrhpjhua.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtqxdznfgl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.snrcjt.cn/Article/details/gtazzlsahr.html

[M05] 设置退出码
来源：http://dali.pengpengdd.cyou/Article/details/gtajmyzkly.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gthjndsfnj.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtyvfibpux.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbevsbrsr.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtqdtbepjm.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtwjoikudk.html

Go:   os.Exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtccqekkok.html

Ruby: exit 1
来源：http://dali.xinyue.icu/Article/details/gtgpwoxkmd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtrqmuybti.html

[M06] 向标准错误输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtojkvyasg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtqcvwhemz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopgvrvvq.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtzvetuoto.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtosqfzdeu.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtcvttmryz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gtlymjagov.html

Ruby: warn "err"
来源：http://dali.svipenyu.cn/Article/details/gtgewkkusv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtfmurcyxj.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtesfbsghy.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gtbelisngn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gthabgppia.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtjocevcuc.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcgasloq.html

Java: public static void main(String[] args)
来源：http://dali.sufxvd.cn/Article/details/gtljiyafwx.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtldsndlqq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtqxmnwhle.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtrliwvyic.html

[M08] 获取系统与运行时信息
来源：http://dali.redwolf501.top/Article/details/gtnculordf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gtvnlcohey.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gtevcpxtcb.html

JS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtqwxjfebm.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtdjeiyqws.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtkrfpvliu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xinyue.icu/Article/details/gtklcuunji.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtgyfmomzp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtnplalflf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtptsyncbx.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gtdcddvgbf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkgkhpjvm.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtvmaqriaw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmrfpfcx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtmfddtjjp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtgcgekkpe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gthdtmbzsb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjryvsrdg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtiyjnesfh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gtrladdism.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtnxbqfkvv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xylfe.cn/Article/details/gtnabpyqcr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtdonfjhzg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtvomzbjqr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gthkamviqy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedjfzlpi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtxkpcurjz.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtestnvolh.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtpcqdbeid.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gtkusfcelk.html

[N03] 快速排序（分治示例）
来源：http://dali.nwbrower.top/Article/details/gtxmpgicev.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtthtcknmt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtamhjgbhm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fengsongda.top/Article/details/gtosodxekw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtnpgydvkn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtwukjbrmq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cdnleiting.top/Article/details/gtlpfmmfnu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.andypj.xyz/Article/details/gtnlvnxixf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtqpxzzhse.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtobxtqbln.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtqzczumqf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtjuocuczz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gttiffabjp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtxubratny.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gtngvvdkds.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxoikbcg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gteojcejtj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtuuopeazz.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gtntgzpsvx.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtjltufwkm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtyiezkruw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtamysbelm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtqeffikms.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtxerfvnkb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtdpnzdtui.html

Ruby: a.gcd(b)
来源：http://dali.yangfankeji.com/Article/details/gtwqugwadn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlgcyfvda.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtuqrrcwmg.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtrakwsmqt.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gtyxbxyyid.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtnyoekysf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtrjaktrjj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtfxzzpnmo.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtdnelzhje.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtfvhdelfi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtltvsdlus.html

[N07] 两数之和（返回下标）
来源：http://dali.ydzc1.top/Article/details/gtaylmqwlm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtmdwvmail.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cdnleiting.top/Article/details/gtsxwfydlh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjohnuqkc.html

TS:   // 手写 Map<string, number>
来源：http://dali.tianlin.xyz/Article/details/gtjvphskvb.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gtbwqvowxf.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtslvsxpec.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gtantdnfqx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmltwdntr.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtajojcttx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gtjpknhhvl.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtpeizeftn.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtiquecjdo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gteyxchuvs.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtwtismvld.html

Go:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtyucuimek.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtqdfcubnu.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtavrultsv.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gtetjvaqgz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtghoeaexa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtbjsvxpob.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtztwisbgv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gteaejxhyy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtphmrxcic.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtjngyktml.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtrzatlhws.html


<!-- 参考信息 -->