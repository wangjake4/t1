代发 wailian999

[K02] JSON 字符串转对象
来源：http://dali.shuidangran.top/Article/details/gtnemdtppv.html

Py:   json.loads(s)
来源：http://dali.zhixingplan.top/Article/details/gtewyeqaqj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zdqjudy.top/Article/details/gtfyejgzcp.html

JS:   JSON.parse(s)
来源：http://dali.jlsjyb.cn/Article/details/gtsvxikcse.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwriuibz.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ehwqpu.com/Article/details/gtjjiunkyr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ehwqpu.com/Article/details/gtncjunhze.html

Ruby: JSON.parse(s)
来源：http://dali.andypj.xyz/Article/details/gtzxsbyqvi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinqigfzy.top/Article/details/gthygelohu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.9152youxi.cn/Article/details/gtejnjxnsl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrnwtcma.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gtqjdzijbs.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtulbmmjgw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtarosvusu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shuidangran.top/Article/details/gtettqhsga.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gtrkgcvxwl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.9152youxi.cn/Article/details/gtakovjpci.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gthndjotje.html

[K04] 读取 JSON 文件
来源：http://dali.zhengqikj.top/Article/details/gtgzmjglai.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtwvslbiph.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.andypj.xyz/Article/details/gthldcdmta.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtfwsyuplz.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gtyckxhnaj.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gtkrmaanfu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtietdnrpy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtkvevjwxq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yj20258.top/Article/details/gtipwfghmm.html

[K05] 深拷贝对象
来源：http://dali.jianghu66.top/Article/details/gtifwrlxhs.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuanzx.com/Article/details/gtfihyyyes.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtwfhzyodo.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtrolumjaz.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtwzhtkmgc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.tianlin.xyz/Article/details/gtadzelisi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtsqyqwqdz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgwscnld.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.havefunace.top/Article/details/gterzkmoha.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gttpjyfjbi.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yuxming.cn/Article/details/gtlmgooxgu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gttqinoito.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.redwolf501.top/Article/details/gtsngqjulc.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtiqexjozs.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gtvbwognah.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtwlqyktsw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gttejrcmha.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gtxuekmxwp.html

[K07] 进制转换
来源：http://dali.guannengcc.top/Article/details/gtplngskgl.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtfhahkjpv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzddbcnxw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hnqzz.top/Article/details/gtcwfohsoi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtrvopqqaj.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gtdtxsmajj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhiwuduotai.top/Article/details/gtuceosyke.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gtzcsstbyu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxavvniqy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtqjiapqmh.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigufen.top/Article/details/gtekvhcsxt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.316326.xyz/Article/details/gtxszlvmqg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsutlduoo.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtgezfffou.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtdjecubif.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoyuggno.html

Ruby: Marshal.dump(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtodrfdjxd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsvnsvdp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtshzakiyy.html

L. 网络请求
来源：http://dali.daxiang520.top/Article/details/gtqhmzdvwq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbyxouhzq.html

[L01] 发送 GET 请求
来源：http://dali.gogol.net.cn/Article/details/gtgxxcpzuo.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gteepvvhtz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.birdmap.top/Article/details/gtuhqvbpfw.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gtiiiprvvv.html

TS:   await fetch(url)
来源：http://dali.yongpay.top/Article/details/gtjgwjsgnf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigufen.top/Article/details/gtxwbcyuvu.html

Go:   resp, err := http.Get(url)
来源：http://dali.zycfv.cn/Article/details/gtuvsdigrf.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cqqwz.cn/Article/details/gtvlogbhkz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gthsltdbal.html

[L02] 发送 POST JSON
来源：http://dali.hammf.cn/Article/details/gttquwbtva.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daxiang520.top/Article/details/gtqiwevkga.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtbmliyzly.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jiagoushi.top/Article/details/gtoxmusfjl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtvteiqaxd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtmlftnktu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gtydwpvelu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhongyouzk.top/Article/details/gtvlbbsdds.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.guannengcc.top/Article/details/gtvaddahrt.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtpkasvwos.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gtzflcbkba.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtcgbmatbz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gthwxsvbsg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtrxwevslh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yvedp.cn/Article/details/gteldcoeou.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtjbutyyoy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgfzy.top/Article/details/gtaqeqrnnh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqjjkppq.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtfwfgbnar.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gteqjsbrth.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gtskmhumoi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtdsolgxwv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtwauyvyen.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gtmjonzbsz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtmvnzsazh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtzrdhdlem.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xziqi.cn/Article/details/gttzkgfwjp.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gthphgglcg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gtvonkpqmp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gtdqweodbi.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtkqtdyvsr.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.0kj1m.cn/Article/details/gtkiwyaxwg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqyirsds.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtrjlgapot.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtjemneuil.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtkrrkhcgi.html

[L06] 解析响应为 JSON
来源：http://dali.jiagoushi.top/Article/details/gtcqhwwoby.html

Py:   resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtqpsmivhn.html

PHP:  json_decode($body, true);
来源：http://dali.yanxiufei.cn/Article/details/gtryfffvep.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtggbijpov.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gthiytvolj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gtqypcvqoy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxejgtspc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gtckdyrste.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.redwolf501.top/Article/details/gtvlqjsquc.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtheblodfn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ppjwa.cn/Article/details/gtzbdpktar.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtrkvibkls.html

JS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtkxeqztfc.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtajdqlvxy.html

Java: resp.statusCode()
来源：http://dali.316326.xyz/Article/details/gtbybwlxfu.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtcictnsnq.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtxhqzwpmq.html

C#:   (int)resp.StatusCode
来源：http://dali.shzxlz.cn/Article/details/gtvoqfxkjv.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gtzuajudlj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuckcujh.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtwnigapce.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtoedubftk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtjyestskf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbmhrrjm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gtbuzwwkki.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmkzmtfr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gtqtextxhf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdnyybpie.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtengbkwon.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtggmvpuyl.html

[M01] 读取命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtwibesxid.html

Py:   sys.argv[1:]
来源：http://dali.ydzc1.top/Article/details/gtnuoqbpan.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gtleonabkp.html

JS:   process.argv.slice(2)
来源：http://dali.cucudq.cn/Article/details/gtwmxwltdr.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtdbryknal.html

Java: args 数组（main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtvyjhnnyy.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gtfggobeac.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtjrztgnrz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtujhsggav.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gthcfjiyyg.html

Py:   os.environ.get("HOME")
来源：http://dali.pycfn.com/Article/details/gtxcxisqct.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gtmfuacoqy.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtyxtpjixe.html

TS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtlvmuvgbu.html

Java: System.getenv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtgoqfywro.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gthxbowoux.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtpzhrdfyt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtpggwdrxh.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gthpitgdtq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gtkkcljsgq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.redwolf501.top/Article/details/gtyrfqwerf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yueranfly.top/Article/details/gtgzmgfkwx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtbsiuqalo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtozyuqzxq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gthxklkxvs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xziqi.cn/Article/details/gtjwzsmbza.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtljusnizi.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gtmvlkhqzr.html

Py:   os.getcwd()
来源：http://dali.9152youxi.cn/Article/details/gtlthymzrl.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtuefenaxz.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtthndmoyd.html

TS:   process.cwd()
来源：http://dali.yj20258888.top/Article/details/gtqjwudqtb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ivvv.top/Article/details/gtjfcznpsq.html

Go:   os.Getwd()
来源：http://dali.zhoulong.xyz/Article/details/gtymeakxoa.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtlopuhqhq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtspgckzux.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gtsdkciyft.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtlocvatts.html

PHP:  exit(1);
来源：http://dali.yuanzhike.top/Article/details/gtzwijsmeb.html

JS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtlkljtfdy.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtoewigriv.html

Java: System.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtujwfsery.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gtxlyohwnf.html

Ruby: exit 1
来源：http://dali.sufxvd.cn/Article/details/gtvpoeqfcy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuanzx.com/Article/details/gtzryczwvw.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtiwbhrdyc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtlncqjnnl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtqyvrkxeu.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtmyhfaznv.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtfdfwpyio.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtyvvloxck.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.mhx1999.top/Article/details/gtrdgzcbjc.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtncdkevuy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.snrcjt.cn/Article/details/gttmbgnlom.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtsdwyaaea.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gtjsrrkmlc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtftfbsebg.html

JS:   require.main === module
来源：http://dali.vqdsnc.cn/Article/details/gtioasslfi.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gttfmvdmsv.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtowhzomso.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtndmwcbva.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fzhhl.top/Article/details/gtjfyjbxib.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtipouazxf.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmswoxhv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtflrmpoes.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigufen.top/Article/details/gtjnmuihvu.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtygwvcozx.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gtiizgoltu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gtbidsufem.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gtjmznalnk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtrarxqqyi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtusrgvaum.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfvnvklbi.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtphrwxqop.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtyhynamwp.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhozmxbo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtdlmkezux.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkzyvxcs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtssuosuxe.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtysruumum.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtauutqouq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gthrxsvfav.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gtiltkoghz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtwywqteef.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtwhanjiif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtxvwyvaly.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtuqtlnfkz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtfpxqefbh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtygkpbbtg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtibicteju.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gttrxszsvl.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtpzgbmkhj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gtbsklixuj.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtvurtmqvu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guowangkeji.top/Article/details/gtdskszzfc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtdowjlrdh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtwnfrdxff.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdwmmbip.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtrvvhaxlv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gtjyhdhmzb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtyoawqoyy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hnxiangtu.top/Article/details/gtmouldbvp.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtfyzjcvhf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmqdmhckk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtnsqxtwrb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtglmzwolq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtbsxectns.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtxcuatzvn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtfuxqnpjy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtszizyccj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gtuebmnluv.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtadypveiz.html

Py:   math.gcd(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtreqhmxbg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtkohrnpso.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtmevrqqyz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtkefhondd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwioxerkl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtnlpmjjqg.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwesabme.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gtpmiqurih.html

[N06] 判断回文字符串
来源：http://dali.316326.xyz/Article/details/gtswvkqrri.html

Py:   s == s[::-1]
来源：http://dali.dianchejie.cn/Article/details/gtyqhztymg.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtuwgaihwe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtnsadbqly.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtztzsldwb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtvbwudghb.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtqlradrhe.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtjtmrsmzi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtflqdimiu.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtextlktac.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gthdobuyoz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gtgqzgnxjm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gtmkbnuwpi.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gttjrjhtao.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gtcsscmpiz.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtzsacxuep.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtjxnhfsbt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtiqheflcg.html

[N08] 生成全排列
来源：http://dali.dashuyun.cn/Article/details/gtkdiaqtpl.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwidonwxo.html

PHP:  // 手写递归交换
来源：http://dali.guowangkeji.top/Article/details/gtxyixwjqn.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtvgbjfkgs.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtktnpdagh.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtteadpppq.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtujueipto.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtzayhcjsp.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtivsazgfp.html

[N09] 栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gttiezczwe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtxqcsnzxj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtonmhhnvp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtjhbjoygq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtihrtbuyl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfasexlj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnygoclns.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gtpdlrorkn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gtytphldor.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtqzwukspz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gttusnvxoi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gtmqtglvia.html


<!-- 参考信息 -->