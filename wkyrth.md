代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.xziqi.cn/Article/details/gtzsfugfsk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hongshengwenyu.top/Article/details/gtbfvvtaed.html

JS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtyrxdzpbj.html

TS:   structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gtdeqwukzx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.svipenyu.cn/Article/details/gtbqdjjbll.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtoulbkneg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.haohaochexian.top/Article/details/gthwapnghx.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cdnleiting.top/Article/details/gtcjyhuwuf.html

[K06] 解析 URL 查询串
来源：http://dali.nanxuanxn.top/Article/details/gtwkefwrxg.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yangfankeji.com/Article/details/gthpogzaou.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gtjxetzhox.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtyamlgbgw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tanke756.top/Article/details/gtphvikbyw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gtybtatzwf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtxwqrhgok.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtiwfyjpyn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtxaseckog.html

[K07] 进制转换
来源：http://dali.jqgufenzy.top/Article/details/gtrnqtcoox.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprfhqknl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtnubavbkv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgutlxmq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtztpayrwo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gtwffbiupo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuxming.cn/Article/details/gthyvusjmb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shzxlz.cn/Article/details/gtnpxxuthl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtcxeckjsn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jlsjyb.cn/Article/details/gtpedytvtj.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtnaihndcg.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtvfvgloev.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gtlcldvvjm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtyrswahyo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.smart0.xyz/Article/details/gtgroqlkgx.html

Go:   encoding/gob
来源：http://dali.ppjwa.cn/Article/details/gtcaofmiun.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtwzikexjl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtxsvbvett.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizmuunxu.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtslmlrrpn.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtcjbucjat.html

[L01] 发送 GET 请求
来源：http://dali.yanxiufei.cn/Article/details/gtvzocxdyk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhengqikj.top/Article/details/gtrcwcyrkq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhijiandao.cn/Article/details/gtrfphedap.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtmthiwwxo.html

TS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gtprazuepn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpshnzjqx.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gtlfojrlzh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtbmumesea.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yuanzhike.top/Article/details/gthkgmfoyu.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtniqnimxq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hnqzz.top/Article/details/gtlkrbsrod.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtkkhjwixw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.snrcjt.cn/Article/details/gtfwtmafxy.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gtnbspfcgx.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.kuanghao11.cn/Article/details/gtsdzoxlyf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gtxvxbolbz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtnvpgbijw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.c1oappe.top/Article/details/gtrdolbiyq.html

[L03] 设置自定义请求头
来源：http://dali.nanxuanxn.top/Article/details/gtoxxisash.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gteqkyjdel.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gtjiwraqeu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gtangatkdc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtwtgegmcd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpexpdiv.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jqgfzy.top/Article/details/gtqcjvnqij.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtbrdjpkvu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fzhhl.top/Article/details/gtxxuclzea.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtceuocdfs.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtcowpiyzu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtzunokzci.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtwmkprafa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtyhtwczdi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aibaodan.cn/Article/details/gtkyrkzqhk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtoykjopiv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtvqozpkaf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sufxvd.cn/Article/details/gtrsklppss.html

[L05] 上传文件（multipart）
来源：http://dali.birdmap.top/Article/details/gtlsxaiqqu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtywvuqowt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtosgecdci.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gtmwxjaxnq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtszhgqmpy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.9152youxi.cn/Article/details/gtrzthbifm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtczfmepzl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtsdkczjpa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtbmgfuqbk.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtyddyenrt.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgwimaue.html

PHP:  json_decode($body, true);
来源：http://dali.quarkkingdee.top/Article/details/gterfbfucu.html

JS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gtvpfucnnz.html

TS:   await resp.json()
来源：http://dali.xinyue.icu/Article/details/gtoxdkksvy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtnqqcccxa.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gtsrzbjoad.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cashguo.top/Article/details/gtvbgmlmal.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtjseqapnq.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtscosufce.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gtphyqslkq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtyrkclhzp.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtbgkminvj.html

TS:   resp.ok;  resp.status
来源：http://dali.cqqwz.cn/Article/details/gtulvarvzw.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtealrdled.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtacasxjwg.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtzsxeikcr.html

C#:   (int)resp.StatusCode
来源：http://dali.aizwys.cn/Article/details/gthxkhnrrd.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbweaveyr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gogol.net.cn/Article/details/gtddclslnx.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtdzheqgty.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebifbigb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gtiemnktao.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.andypj.xyz/Article/details/gthiucxzog.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtmpxgdqrv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gttaozawfs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sysykeji.top/Article/details/gtontykslu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtofiralqh.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtwyyrfcxt.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnpfeacsz.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gtoghbgcdn.html

Py:   sys.argv[1:]
来源：http://dali.aibaodan.cn/Article/details/gtdphjhbbb.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtgajdgqij.html

JS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttphxzejc.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtplsatlfo.html

Java: args 数组（main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezavqrpe.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gtrqgihmpj.html

Ruby: ARGV
来源：http://dali.gzhubu.top/Article/details/gttutushbg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgijlkaoz.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtbxethotp.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gthijmvofs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gtsbzrayqu.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtdxgvrwkb.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gtbpzlzojq.html

Java: System.getenv("HOME")
来源：http://dali.birdmap.top/Article/details/gtqqsykkgs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvizrklef.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gtgnwotusd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258888.top/Article/details/gtcfyneson.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtbxoyvysa.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gtsjtsupdk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtvwuxxvnr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nwbrower.top/Article/details/gtnexibzpr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtoiyhgcnu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtiiwbkqaj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yonumen.top/Article/details/gtvvwmhcqw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigufen.top/Article/details/gtxlhrablt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtpuazzdwn.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtptdtdpqj.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gthhsskocx.html

PHP:  getcwd();
来源：http://dali.pycfn.com/Article/details/gthhpbyrzc.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtzytulprz.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtgrpvmjxa.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aibaodan.cn/Article/details/gtbtcikfxa.html

Go:   os.Getwd()
来源：http://dali.iojbl.cn/Article/details/gtnudlsdcp.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtugofxpov.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtuyiaasie.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtndmzgntp.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtdrwvcwpy.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaoiyjoe.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtmlxnieub.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtnlrbbcuj.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtthonuywf.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtyrktwcth.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtdoyqtebk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gtgyxhxhmu.html

[M06] 向标准错误输出
来源：http://dali.chenlongwang.top/Article/details/gtgojgwpfx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtghloncet.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gttwizzbsc.html

JS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtncimuzqf.html

TS:   console.error("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuyfgpibo.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtspnugoql.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtqibpphrz.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtmernyktw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gtotskntvk.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gtivcgdsfn.html

Py:   if __name__ == "__main__":
来源：http://dali.guowangkeji.top/Article/details/gtlzlsudep.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gtykehxfre.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gtrdkpckxr.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtmfhabxzo.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtxbrivojb.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gtvfphwdjm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gtvpymuwck.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gtuucuurlc.html

[M08] 获取系统与运行时信息
来源：http://dali.svipenyu.cn/Article/details/gtephhecee.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtuykpqqqs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.snrcjt.cn/Article/details/gtznjcpvsv.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtsdsrfnsn.html

TS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtdyeyyrsx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.fengsongda.top/Article/details/gtetgxjezn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gttolmpbat.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gtpfcmzzcy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuanzhike.top/Article/details/gtrcgruyda.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtnuoamlby.html

N. 数据结构与算法
来源：http://dali.zhongyouzk.top/Article/details/gtmqknzgnj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtleujrqdb.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gtiklvdwur.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtdpwgbzvj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtqtfolxdy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.meibo888.top/Article/details/gthbbgkgjj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gtuklahxhi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtpazzibmd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtyakdznqk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gtfarekdhy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtztzcntlk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtgrlxkiwn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtbvllnpvv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtcjhrekwx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtieavsstr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.redwolf501.top/Article/details/gtlkluavwq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.iojbl.cn/Article/details/gtbdwqtzsx.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtmnougals.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtfcrcwfva.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwochxjhz.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtqfyynxdm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gtakthgquq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtylxgyvnm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gtfvswduqx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtistjeopp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtebijhrjh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdigfsgn.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigfzy.top/Article/details/gtkmxhnxrp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gthxqpswsj.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gtypcvolzg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzpgwzzhs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtutiehqrv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtjltsvaic.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtyakxdiyy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtlhspwgyn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtwthjilzp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtexgpjpxr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtdkarmvft.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gtxrdjgpgd.html

Py:   math.gcd(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtzmywrnzn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtbpufvhaz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gtqfircsph.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gttldxgkxa.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtsijztu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtfxozqwkj.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gtmdpabxop.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pycfn.com/Article/details/gtndkrsodc.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtuynzxyan.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gtzlhocirn.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtokosawux.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtpztrjbvy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtirviwuah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtjwobrxvx.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtbvwomezd.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtxabqxczb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gttdmivjca.html

[N07] 两数之和（返回下标）
来源：http://dali.ywan-chungtsiang.top/Article/details/gterhpjjrl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtcaobyuas.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtfkzmszlo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenzaomai.com/Article/details/gtbgvhemza.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtbmvjektx.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gtkwjbfivc.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtdcuhtakt.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gtzjytkvsm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtpujvanfp.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsarreyd.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtglrqbgwi.html

PHP:  // 手写递归交换
来源：http://dali.tian-w.cn/Article/details/gtriurkaaw.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtppqudgkf.html

TS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtokwxnoim.html

Java: // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtdcurbfza.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtzozxqitn.html

Ruby: arr.permutation.to_a
来源：http://dali.hysaishi.cn/Article/details/gtutvaunrq.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtlgmrfdbd.html

[N09] 栈与队列
来源：http://dali.shzxlz.cn/Article/details/gtoecmzdew.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtbtbxbhyw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtsnbkepui.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtkgoyvnql.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.fzhhl.top/Article/details/gtwjygdcuf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtlixcskal.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daxiang520.top/Article/details/gtbkrgchpi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtlpgolfds.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gtpysgdtja.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gtdkdhhviv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoaopgam.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtgjtyhvqb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yuxming.cn/Article/details/gtrvxucdyp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtrbfvootx.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gtodebxntn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtvgtdjgct.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtaksxbqaw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xylfe.cn/Article/details/gtvyuxlatl.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtlmocwdgu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtqjsrniuf.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtdevtuiyx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtadjwtrav.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gtkrvgwpga.html

Java: // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtruwtnfan.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtymuwknda.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sweek.top/Article/details/gtsjgcdtus.html

C#:   // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtxcojpasm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtsxpogmub.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtketojkdb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gtagennkjs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtoouihngb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtbreqvtjw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtsukbuuii.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gtokwdomzg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulvwkaet.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.redwolf501.top/Article/details/gtlxewmsnq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuyespyr.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtthxxytxn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwnajvreu.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gtqhckwtnz.html


<!-- 参考信息 -->