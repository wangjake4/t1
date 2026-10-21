代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.wangshuangyany.cn/Article/details/gtqasdfdab.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gtmsdodxsc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtktpabgzs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tian-w.cn/Article/details/gtfspaxotb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrqqcbjy.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sufxvd.cn/Article/details/gtiwgjffqn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cdnleiting.top/Article/details/gtdnkpekhm.html

[K05] 深拷贝对象
来源：http://dali.snrcjt.cn/Article/details/gtjwazlney.html

Py:   copy.deepcopy(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtfpyblewa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.pengpengdd.cyou/Article/details/gtzcldzpzi.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtkxyraajw.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtfeysblad.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.guannengcc.top/Article/details/gtbxfleprq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ybcxt.top/Article/details/gtwkizlnrh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gteduldtzf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gthmrjhvso.html

[K06] 解析 URL 查询串
来源：http://dali.yonumen.top/Article/details/gtjngaiwsa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtberymwvd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.mhx1999.top/Article/details/gtmtnwfder.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gthnuwziux.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtutddtxvu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.fzhhl.top/Article/details/gtddikcdoe.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gtaoopyyfo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gttyyvlyqs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtfphpvnpk.html

[K07] 进制转换
来源：http://dali.ehwqpu.com/Article/details/gtseucsubd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtqlencuez.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hysaishi.cn/Article/details/gtultqhoed.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtqbswzekq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtorklyzbg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtqhzqhfan.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.tianlin.xyz/Article/details/gthcmceomp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gthhymznld.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtwwfpixtj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenzaomai.com/Article/details/gtxmsxwwxa.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gtynqtyryq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqbueeia.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtxynljgpq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gtlsdxlykr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenlongwang.top/Article/details/gtfbflpbou.html

Go:   encoding/gob
来源：http://dali.daxiang520.top/Article/details/gtjwbuuxmr.html

Ruby: Marshal.dump(obj)
来源：http://dali.jinqigufen.top/Article/details/gttitxadpg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanebgnnq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqmqluavc.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtqpicryqz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvhbhkpti.html

[L01] 发送 GET 请求
来源：http://dali.chenjidiqi.icu/Article/details/gtobyyomay.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tianlin.xyz/Article/details/gtxpojyqcn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nanxuanxn.top/Article/details/gtpsrsxnzs.html

JS:   await fetch(url)
来源：http://dali.cheryme.top/Article/details/gtnboowbnp.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gtexwwtpqm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyxpyvhu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrujynvyi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtljfgaxcc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.quarkkingdee.top/Article/details/gtjjeujzux.html

[L02] 发送 POST JSON
来源：http://dali.zycfv.cn/Article/details/gtmgrdffuv.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258.top/Article/details/gtnvfwpujs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.meibo888.top/Article/details/gtneamsuli.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtpiiunizn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.kuanghao11.cn/Article/details/gtacddyckp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.chenzaomai.com/Article/details/gtpybbywfl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gtmcigvcqs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aibaodan.cn/Article/details/gtglklvlzc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yongpay.top/Article/details/gtrvikvfhj.html

[L03] 设置自定义请求头
来源：http://dali.vqdsnc.cn/Article/details/gtjjdjomvq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gtvtlropff.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ppjwa.cn/Article/details/gteblzqbcd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtlwjodvpp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtyazspzge.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gogol.net.cn/Article/details/gtgqezymmy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gtpqakjlsv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gtbahgpcnf.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtmuugecwh.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtayofglou.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xuanzx.com/Article/details/gtmeihsobe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonnsmych.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gtacwprvwf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shuidangran.top/Article/details/gtxnwmicdk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.svipenyu.cn/Article/details/gtoamlnthb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gteszkpizx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtemzpmith.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ybcxt.top/Article/details/gtgocnhfnm.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtefjctnsk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gtjjrhvzmq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtpfrliwds.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yongpay.top/Article/details/gtevfroufm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtrodzlgbr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gtakyoumfj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cashguo.top/Article/details/gtultdkdql.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gteclpaqmi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtrhowfeni.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtwzitnxii.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gtwhusajvu.html

PHP:  json_decode($body, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtnjcbqsmk.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtsoqfrubi.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtjqswrkuq.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zdqjudy.top/Article/details/gtfsodfkbr.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenzaomai.com/Article/details/gttaisuoft.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gtqivhuerj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gtzakifidq.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtjebmbxyk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gtpsxefmbz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hfpthk.cn/Article/details/gthbcdlvjf.html

JS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafmfpmis.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gtwlnqnokl.html

Java: resp.statusCode()
来源：http://dali.zhiwuduotai.top/Article/details/gtrcjtwsim.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gtxvgctwwk.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllagvvix.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizyozwsz.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtsmyaqfhn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyvjbqie.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqtlwool.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gtroqvwecs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtjsjimlns.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gtrhlfkipw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fengsongda.top/Article/details/gtmuizriog.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258.top/Article/details/gtiflzydnr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gtxtpeecyi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtsyanjehh.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtzeoauecq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtftqhtxtk.html

[M01] 读取命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtwgdkffor.html

Py:   sys.argv[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtrdsnfdex.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gtnvqblgfp.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gthxgebxta.html

TS:   process.argv.slice(2)
来源：http://dali.andypj.xyz/Article/details/gtnbbhffgz.html

Java: args 数组（main 方法参数）
来源：http://dali.yuanzhike.top/Article/details/gtjgqaamvm.html

Go:   os.Args[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtorivzsgf.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtzhdggmzv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtlheyhnkh.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtozdpyihh.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gtxsppdlrc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gtgxdbbqfz.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtwtqaqomq.html

TS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtarkxztsb.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmxazsth.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gteanlylab.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtbturotsp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtdjxmwppg.html

[M03] 执行外部命令
来源：http://dali.0kj1m.cn/Article/details/gtilwhtmce.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtacvwluwh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.svipenyu.cn/Article/details/gtlkboqyjq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtfdcqcbjb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtaljhdheg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gotoacloud.top/Article/details/gtoqwqegkl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpszvfpih.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.sweek.top/Article/details/gtrsbjpoqs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.andypj.xyz/Article/details/gtvzejlxgr.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtnrbioowb.html

Py:   os.getcwd()
来源：http://dali.havefunace.top/Article/details/gtuaxictli.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gtbljxmqgj.html

JS:   process.cwd()
来源：http://dali.tanke756.top/Article/details/gtfhkroojk.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtrwlhyqpp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwvwdwxz.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gtsyzzxdiy.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gtttgmqpwa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj202588.top/Article/details/gtxdbqnwrw.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gtrddmyckb.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gtzbeofyrd.html

PHP:  exit(1);
来源：http://dali.mhx1999.top/Article/details/gtasjmmuzt.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtfxtbwlji.html

TS:   process.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtwrlzfowa.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtjdoaramu.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gtivxnwnrw.html

Ruby: exit 1
来源：http://dali.cucudq.cn/Article/details/gtgoeynlmy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtqiomikls.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gtvdvbjfwk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtibtosnmp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtbphwpklf.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtdlotrynr.html

TS:   console.error("err")
来源：http://dali.zhoulong.xyz/Article/details/gtcexpkvfp.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gtlqljkkqa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gttnrbvtqn.html

Ruby: warn "err"
来源：http://dali.shzxlz.cn/Article/details/gtpovhsybh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtticcfflk.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtbqcfuwqg.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtrvyqlkjd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gtubzqeami.html

JS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtmdphfvzk.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtcfuhajoc.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gtmqzetwfn.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtzabvwgka.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gthujtsltx.html

C#:   static void Main(string[] args)
来源：http://dali.jiagoushi.top/Article/details/gtwetakucc.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtmcvzwhnt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gtipabfdhf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtqocwpsgg.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gtpdzogspf.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtdopbvvha.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gtcwlakvma.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtumcgjldr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtmcgduijd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gtrveeuadv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtftoymohd.html

N. 数据结构与算法
来源：http://dali.redwolf501.top/Article/details/gteznsoefn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtauwdndqe.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gteufddtwa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gteejgkaml.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yvedp.cn/Article/details/gtjlaxlwls.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtpzwcwxhn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtxksxgvdq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvsczobw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtopymnene.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.svipenyu.cn/Article/details/gtewjbpfmo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtnhfcqfuf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtsudjzdxb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtlebguaqo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtsppccgry.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfgemfwv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtfnuhhlmy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gtraoilaqw.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtggdnbnuk.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtlrkilnki.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtesdceoco.html

[N03] 快速排序（分治示例）
来源：http://dali.ybcxt.top/Article/details/gttucrxtgv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tian-w.cn/Article/details/gteoydobqf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtgiotkjgf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gttttndybr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtkrakbkrw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtlpwmsezb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtdegocibz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtifzgzofi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gtvhcnvoyj.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtmcbjyhtc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtwbxwvgfj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gthcumzmxj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozusvgub.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtlnwqalgl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtkiefslxo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gtnlsamuhv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtdvsrdoud.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtywiexaqd.html

[N05] 最大公约数
来源：http://dali.jlsjyb.cn/Article/details/gtlqnxtdxp.html

Py:   math.gcd(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkxettmq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmawwubm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gtjgvetpkb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtgrweemvp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtmcqmiyeo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtestkwvry.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflsnxmos.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtosucskag.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gttylugtij.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gtxjxbesuq.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gtrqrtpthk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gttfrjxxck.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtuuboleyq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtjcjssnsn.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gttnkgepzh.html

Ruby: s == s.reverse
来源：http://dali.xuanzx.com/Article/details/gtvyarjvjm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gthkxjwkel.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtcuozzxdq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yvedp.cn/Article/details/gtbzuyhcdv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangshuangyany.cn/Article/details/gticcgisjc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtwwoicnlm.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtvlpgqkpo.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtaembnluv.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtfghdngbg.html

Ruby: // 手写 Hash
来源：http://dali.jyoumei.cn/Article/details/gtqghoyyaj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yuanzhike.top/Article/details/gtatpwpunc.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtfpnqukzi.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtqugtntbv.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtamiyezrf.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtvtotugbi.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtxsrfcpxf.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtbifakgml.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtiwquzomx.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtdvcqedai.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtgryjlppq.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtbwnxjypr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gttrvpcdtz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gttugcjasl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtgmwzhkgq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hfpthk.cn/Article/details/gtxavgzeim.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gtpgbdwezv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtddmspsol.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmosldsqn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtjwgngkik.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtpmeoppfg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gtbczholzc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrxzxkyh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cashguo.top/Article/details/gtfdltkqfc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtvzvdkgye.html

Java: class Node { int v; Node next; }
来源：http://dali.haohaochexian.top/Article/details/gtlstpwwyt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtkoavqwhe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtuvysyjff.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gtnrhfcpex.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtgsbhrnjo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtmqkkggkp.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gttmsjjrzu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtmqeheqrl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gttdterqfd.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtyfosxres.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtgicruoen.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtgmphbvuh.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtmhoqpeat.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtyteqktqi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gthimibupf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtgeryjhvj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gtawooaahr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpouoqzgn.html


<!-- 参考信息 -->