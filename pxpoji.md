代发 wailian999

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtwjnnmcto.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.mhx1999.top/Article/details/gtibukxmye.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.andypj.xyz/Article/details/gtezvrsetz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gtkwbgbgmw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtsdyvjwmg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gtjsgalash.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gtrrwbgmog.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.kuanghao11.cn/Article/details/gtukmrcupp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.9152youxi.cn/Article/details/gtamrtgemk.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hongshengwenyu.top/Article/details/gtdaqdsxxs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gthqhqpygu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtnamiwkhf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtrwdkdbho.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtccwyregy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwzqycjc.html

[K05] 深拷贝对象
来源：http://dali.xuanzx.com/Article/details/gtcekmston.html

Py:   copy.deepcopy(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtnzfsfmau.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtmrnkbati.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtqauscooq.html

TS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtcynlfppz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xinyue.icu/Article/details/gtujlxcfvz.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghpippih.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jianghu66.top/Article/details/gtwhgewpbb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvuqtrrr.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhfzwgkh.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtfghqcldj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.guannengcc.top/Article/details/gtdejpuhck.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtxdbawrhx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqdixfnu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cheryme.top/Article/details/gtnuhoknft.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtdohrvtrf.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtoyqhhvfs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gtkflfbcgh.html

[K07] 进制转换
来源：http://dali.dashuyun.cn/Article/details/gtucjtkydw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtfmtyjkgu.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gthurgdoly.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrggfycvw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hammf.cn/Article/details/gthcmnrsfi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.guowangkeji.top/Article/details/gtlrhldpmn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenzaomai.com/Article/details/gtltoalpgf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.bjfxy.top/Article/details/gteecdyofk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtkoklpxne.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dianchejie.cn/Article/details/gthldoprgu.html

Py:   pickle.dumps(obj)
来源：http://dali.ehwqpu.com/Article/details/gtkhqrriiq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cqqwz.cn/Article/details/gtnowhitpm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fzhhl.top/Article/details/gtrqqpelky.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shuidangran.top/Article/details/gtsxvudvgd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gtvqtyxyfi.html

Go:   encoding/gob
来源：http://dali.xuanzx.com/Article/details/gtcvicamnx.html

Ruby: Marshal.dump(obj)
来源：http://dali.iojbl.cn/Article/details/gthdbvyeat.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtsomtmlwp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxmdfzgbm.html

L. 网络请求
来源：http://dali.ydzc1.top/Article/details/gtyoyyeasj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtozggwmvd.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtabccjmys.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gtwgdlnchv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tianlin.xyz/Article/details/gtupmzhjgb.html

JS:   await fetch(url)
来源：http://dali.snrcjt.cn/Article/details/gtqrunuflq.html

TS:   await fetch(url)
来源：http://dali.cqqwz.cn/Article/details/gtcxhhivhk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yongpay.top/Article/details/gtyfxbfjhu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gtnoqlspbv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ydzc1.top/Article/details/gtinlktewa.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gtceciewmb.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxnrduaj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtlafzcjck.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebrqeuhl.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtrummhiqo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gttkztrazd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtfqlbodjz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gtbwfatvmx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuanzx.com/Article/details/gtdweprhvs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtyziibslp.html

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtqejpwqfy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gtuqzlsywd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.aizwys.cn/Article/details/gtyaziglvw.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtposujtqm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gtcdcmjooq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gtaxgjbeie.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtwbrdyqcs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gtghlombgy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtsulzgfhz.html

[L04] 设置超时
来源：http://dali.birdmap.top/Article/details/gtsuoaqntx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zdqjudy.top/Article/details/gtnumvuakl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gtgnavmrcl.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.daria6918.cn/Article/details/gtrfppxgzg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtysoqrclg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gtwxkxnlgq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtxhhbkize.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtahrfacdc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtpzlwwgel.html

[L05] 上传文件（multipart）
来源：http://dali.hfpthk.cn/Article/details/gtpqsnmopm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gtbezctvkd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gteftniexh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtfllzhwim.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtpfocckil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gtxdzwshqo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nanxinkj.top/Article/details/gtuotegsro.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gttzqkrwaw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtujmxbikx.html

[L06] 解析响应为 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtjucmlygj.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gtbramofwg.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gttntkxmss.html

JS:   await resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinteoajv.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtkykrdhep.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtvsadahaq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigufen.top/Article/details/gtwsjtcdtw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvkxlxvu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gtrsuilefq.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtydesdvjg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohpxzswd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yueranfly.top/Article/details/gtiiubowsn.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gtgabiqrwj.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtvwccnivu.html

Java: resp.statusCode()
来源：http://dali.yueranfly.top/Article/details/gtkltrxqmp.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtxnkqksvl.html

Ruby: resp.code.to_i
来源：http://dali.hongshengwenyu.top/Article/details/gtiyicpagx.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbrsdrby.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtxqupshdh.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gtcgszfspf.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gthazlgcfq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtfunhnhfx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtwhosvvqv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtlmmbnmes.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gtpjzodpvp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtsayaehtx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gtlwtqdffh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtnsflsvnc.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gtowcyxvbe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbyruqoxl.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbskjcswz.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjllcdea.html

PHP:  $argv;  $argc;
来源：http://dali.cheryme.top/Article/details/gtmliputjm.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gthunvgbcf.html

TS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtbvorhgbd.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiestwoef.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtozdiycuz.html

Ruby: ARGV
来源：http://dali.chenlongwang.top/Article/details/gtbatuupes.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gtmgnbqwqj.html

[M02] 读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtvopruwih.html

Py:   os.environ.get("HOME")
来源：http://dali.birdmap.top/Article/details/gtvdhgppkf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtoraovjjc.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqpgbntc.html

TS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtywkgcssc.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtynxibbyx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtfohklspc.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gtcojjxrsa.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtmrhbqgwq.html

[M03] 执行外部命令
来源：http://dali.yvedp.cn/Article/details/gtzlppmhjg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zdqjudy.top/Article/details/gtregodidc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtvominmqg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tanke756.top/Article/details/gtjwvtcxuq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gteehhapaa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtwsabiwvg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cucudq.cn/Article/details/gtbmwohnpv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtkbdnvzuj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gthmxwneem.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtoyzrwtzl.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtosviqmsf.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtbzjzfjjb.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gtljuceqkk.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gthawmgiyt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gttskhgkhb.html

Go:   os.Getwd()
来源：http://dali.guowangkeji.top/Article/details/gtehizhfbn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtbgnpsutx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gtidggbzis.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtfbuibpin.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtmcpufokj.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gtpsmebvrp.html

JS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtpnpykwfu.html

TS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtfoihsops.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtcqsngbjc.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtcxgorvvx.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtzbdhiktq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinqigfzy.top/Article/details/gtmoumikma.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtbbumtsnx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtrzhhepow.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtrqbjhrom.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtkuxgitoj.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtxhevuniu.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtxavxiajv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtgtcdsuqm.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gtbjmnyxyw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuanzx.com/Article/details/gtwqfhgsbt.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtduggmlwn.html

Py:   if __name__ == "__main__":
来源：http://dali.vqdsnc.cn/Article/details/gtefekawpj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtogtowpad.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gttbvoecvm.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtysktshqf.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtlbbotgrn.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gtyuxxhofs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtpcoclilj.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gtorzamexk.html

[M08] 获取系统与运行时信息
来源：http://dali.jyoumei.cn/Article/details/gtvazlailw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.0kj1m.cn/Article/details/gtmdvydtcg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtsxmbbjzf.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtgxmzhaui.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxmyyzct.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtohxiigej.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gtkcitaxdu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cqqwz.cn/Article/details/gtmaipngxg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtxrhgmbyr.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnrknanrj.html

N. 数据结构与算法
来源：http://dali.zdqjudy.top/Article/details/gtyrfqzcxg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwmhxooxf.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtmujggzho.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtkywtcbco.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gttyizsrhk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtprokdtqq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtydmhefyy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtlxpnqfhx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtkqakefbg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gteydvrfja.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtmawpxzii.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtqgnisysy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gtrgvcupyi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.andypj.xyz/Article/details/gtmnkkvsfv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsehbyjjw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtpnfdnnqg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtylzdfoyw.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtfowlkxto.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtpyieolts.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gtfjrneyxu.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtvjdgqyfb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gtrspzlfhk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gtuiwiblhe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtjjdgsjfu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtajpbhlzk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtvxbponyy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtdopojabr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtjthfsair.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtrrwwekqn.html

[N04] 斐波那契数列
来源：http://dali.yuanzhike.top/Article/details/gtwmmiibea.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtnttkbomh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.iojbl.cn/Article/details/gtioufghee.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtprlcuumw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtvxsjkumf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gthqitygmm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtdnzkiqln.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtojsenzjx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtbgvhxipp.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtmwxodikv.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtxwlqwoau.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtdpuecrax.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtkwwfjflw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtdoqtutxj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtgegpftsn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtabbkpmfo.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbwblwve.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gtnvcszzvd.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtblqtznoh.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuxwxzen.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtwzjlarru.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtvtiiqwql.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtbwukcrje.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gtqnneqejw.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtowpqkhku.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtseuhdtih.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtakcqlwrn.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtqwyixlyu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtivafsoqj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtqpmunefm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtqbwxttrz.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtlqsphaxt.html

Java: // 手写 HashMap
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwxvipci.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtbyuucyob.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gtufhihbre.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtggjmlttm.html

[N08] 生成全排列
来源：http://dali.jinqigufen.top/Article/details/gtzfrcowgl.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gtewlpvtny.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gtgirirphl.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtnkkhupqt.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtiyeejnfe.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtvqkkqfli.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtciueqfhq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzztazjl.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtmdovytzw.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtyxkchanj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtuuzajpvu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtgkyaqnbx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtoquvslua.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gtkfwunuzx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nwbrower.top/Article/details/gtpfkaucvb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jyoumei.cn/Article/details/gtpntllzij.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtlyxjbfir.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtiboxqwhv.html

[N10] 链表节点定义
来源：http://dali.dashuyun.cn/Article/details/gtcnmgljud.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gtfqinsagz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjaeqkbht.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ybcxt.top/Article/details/gtnrjkrdpn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtxcltfklt.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtignnqavs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtjppnmuqv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gthyopiwma.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gttxznwlbi.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtsinkukqn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gtqmpaynth.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gtuonqqsfc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtraxrwnrx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gtsiqggnmr.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdtyyguhe.html


<!-- 参考信息 -->