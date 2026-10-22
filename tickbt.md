代发 wailian999

Py:   copy.deepcopy(obj)
来源：http://dali.nwbrower.top/Article/details/gt2okppvtxr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.ehwqpu.com/Article/details/gt2krkewwjg.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2pyqqiici.html

TS:   structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2awznxzrd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jqgufenzy.top/Article/details/gt2ftyghzcu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vrrwkyze.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xinyue.icu/Article/details/gt2fqrmlceh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2oexipzqs.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gt2bjjdagax.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2opijfsht.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zdqjudy.top/Article/details/gt2cveaasdd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hywenlv.cn/Article/details/gt2kebuqlaf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cheryme.top/Article/details/gt2cpwjcbqf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2ppiwefub.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.mhx1999.top/Article/details/gt2ulaxoumx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaqmehvr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gt2etzebteb.html

[K07] 进制转换
来源：http://dali.yangfankeji.com/Article/details/gt2tyzbqsdn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2iencjxoq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zdqjudy.top/Article/details/gt2bvnreyei.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2zrppxgxv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2giycoplm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2talprxld.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aibaodan.cn/Article/details/gt2jkpkmdgb.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gt2bkeqpkkh.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2ldvrhhat.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jyoumei.cn/Article/details/gt2yrxqpgke.html

Py:   pickle.dumps(obj)
来源：http://dali.smart0.xyz/Article/details/gt2epwhzdow.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2hycaojrs.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2gsqcqqhm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2qkcczswi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gt2gjhpribb.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gt2tyopwufu.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2amgpoyjq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cashguo.top/Article/details/gt2kizpxzca.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2eyrzfbci.html

L. 网络请求
来源：http://dali.fengsongda.top/Article/details/gt2fmpcrapz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2yyrdctlh.html

[L01] 发送 GET 请求
来源：http://dali.iojbl.cn/Article/details/gt2psvjnwgb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gt2vqvhcmui.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shzxlz.cn/Article/details/gt2rfazchag.html

JS:   await fetch(url)
来源：http://dali.wangdashe.top/Article/details/gt2ffrqrduv.html

TS:   await fetch(url)
来源：http://dali.yvedp.cn/Article/details/gt2arqunzxa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.havefunace.top/Article/details/gt2nuaxsejz.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2tkxvhuoj.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.haohaochexian.top/Article/details/gt2qnvwcpbd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sufxvd.cn/Article/details/gt2vzdhsuvm.html

[L02] 发送 POST JSON
来源：http://dali.zhixingplan.top/Article/details/gt2ilemmext.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.feifeiyinyue.top/Article/details/gt2buqcsaaj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2pcokcjdt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gt2lpivqrxn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2ozwrqbsg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gt2kuvbkova.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tian-w.cn/Article/details/gt2dalekkxx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jyoumei.cn/Article/details/gt2wflqsyqq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aibaodan.cn/Article/details/gt2cipfdjgv.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gt2zhkzszyx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gt2lolwfjae.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gt2kgwvfpnz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2lifoddyi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.birdmap.top/Article/details/gt2vihmgirs.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xinyue.icu/Article/details/gt2iefvyvxb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2vfuynlte.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gt2pormphve.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2tyxooaov.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gt2rkewgyzq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gt2xbkxbyai.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkljkuvp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lulqruyo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpyhxzrq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gt2mvnbunkl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qezotbwj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guowangkeji.top/Article/details/gt2gufpuqua.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2aexsogrd.html

[L05] 上传文件（multipart）
来源：http://dali.cdnleiting.top/Article/details/gt2gjbleajg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gt2jeqlrpza.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hnxiangtu.top/Article/details/gt2qnktlrqc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2javolxrz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangshuangyany.cn/Article/details/gt2crihlqql.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgmhuqdz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2acgbgglq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bvheaiek.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2deprllgd.html

[L06] 解析响应为 JSON
来源：http://dali.smart0.xyz/Article/details/gt2prwstnrn.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gt2zcqbeldd.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gt2oqhzubjd.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2drohcsoy.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2mdfnzgkd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gt2ejhcutek.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gt2nkfnwtlp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gt2vdfuyftl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2pabjmkuj.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2xcblbrls.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yonumen.top/Article/details/gt2cjaoqmhx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gt2ajwyzuhh.html

JS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gt2nepegamz.html

TS:   resp.ok;  resp.status
来源：http://dali.iojbl.cn/Article/details/gt2idbjgulg.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2ocqrhurv.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2oxdwkayu.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2gbxbcwma.html

C#:   (int)resp.StatusCode
来源：http://dali.zdqjudy.top/Article/details/gt2xvkjjfay.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gt2ooanpgyz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmyhjrr.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2cdsjjtlb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gt2gipjvjre.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2drfbzhhy.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihoazvwj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2clytznze.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2osncotno.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwuokeqe.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ahujtuyz.html

M. 命令行 / 进程 / 环境
来源：http://dali.pycfn.com/Article/details/gt2watstlca.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2lqddnjkt.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gt2ntxfeplj.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gt2icdpbvfg.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2eckcgllz.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gt2ncbfulgg.html

TS:   process.argv.slice(2)
来源：http://dali.aizwys.cn/Article/details/gt2engsbdep.html

Java: args 数组（main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gt2hxjjylxe.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2fgkvnfyk.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gt2qmdiwuzz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2langstjm.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2cnngulcj.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2evwrvdcn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2rmihfawv.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2rzcwnqwo.html

TS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2hmpzdfzk.html

Java: System.getenv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqtmohxv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gt2odwupfrf.html

Ruby: ENV["HOME"]
来源：http://dali.sufxvd.cn/Article/details/gt2dvihyebh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2jvbbfozx.html

[M03] 执行外部命令
来源：http://dali.hnxiangtu.top/Article/details/gt2ulhfwedn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gt2jvquzsta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shuidangran.top/Article/details/gt2gqioyqbe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gt2onjmpfyl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2olstjyao.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gt2vabfewly.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2kgbubakf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2fervhjah.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guannengcc.top/Article/details/gt2ttmvypwg.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gt2udjsnimj.html

Py:   os.getcwd()
来源：http://dali.yuanzhike.top/Article/details/gt2dmkgtilr.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwrojljl.html

JS:   process.cwd()
来源：http://dali.tian-w.cn/Article/details/gt2jhvcnaml.html

TS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gt2uwfilyuk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gt2avxakwwy.html

Go:   os.Getwd()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyfpnvab.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gt2tnghjhfu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gt2zebwjejz.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpquzqyc.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2arnfecwu.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2kqrvvqaf.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2mrhtpgey.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2jlwurqrw.html

Java: System.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2bxdvarxf.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2wmhkfgzk.html

Ruby: exit 1
来源：http://dali.yj20258888.top/Article/details/gt2ohddslmr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gt2wcysqhax.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gt2awsokpyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewmofgey.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2owmjdagg.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2xnraiahf.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2rxxqhaqr.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2cwdxxggp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gt2jvmxgiwi.html

Ruby: warn "err"
来源：http://dali.guowangkeji.top/Article/details/gt2yzkhrrqr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wzfnqfuu.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2iqoljfbf.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2todlxmjp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gt2dmztowca.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2iqxpjodz.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2ljrrfxma.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2iydmsngr.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gt2sqmshnok.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gt2hrwwjgki.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2rrkvivdj.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gt2hmuxutbg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fkqkgquh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2geajxmbm.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gt2nfwyxwlm.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2bbmaxzyr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjccbxvi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gt2tudkfjpl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2xjnhvkwv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gt2swuzqnlv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxqylxyn.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gt2yaayhgbw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uipvjnas.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gt2wvimuiok.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2waxemkhf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ludbqfsw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gt2xqismznb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2bpfbfupg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gt2zcpaufmv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2xnrgvnkf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gt2ccdxcalq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2gtsfurva.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.redwolf501.top/Article/details/gt2qnttnatg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2wfxfcgop.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2vakljhbv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2bqwyujio.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmlkdmsv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gt2qzjrczuw.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gt2skkkcujv.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gt2hprtiqdg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.birdmap.top/Article/details/gt2pmrdlwlo.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gt2ksgewiyi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gt2egqgomax.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2vrfiwchh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gt2stysnyns.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2jhityugk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigufen.top/Article/details/gt2bkvjuzyp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gt2qsaafmtc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gt2qiqjwyqv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gt2acrgjgwk.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gt2xoblfpwq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2mlehxizt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2rmqqclbb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2fmrkjysb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imdgjjiv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2mcrvseom.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gt2wrqjfnbp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gt2ebqjpjok.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2cdvrqcvv.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gt2yuqzhmai.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gt2khhecqlt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2rfetqadh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2zpymktzj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gt2okekkuxb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gt2qgteqjld.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2swgkwswu.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gt2krcymnxt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cwtspiok.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2mkqizfdo.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrmblnga.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2tbatjjfu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxkhntvq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2aqjbapql.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.quarkkingdee.top/Article/details/gt2iotpxops.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gt2tqzhbezn.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gt2yknsqbae.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2immgfxch.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gt2bkfhdswc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gt2cqegsoyk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gt2krqyeiio.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.quarkkingdee.top/Article/details/gt2tpkjhjfr.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gt2dwlhphkq.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gt2qdqnrkkk.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gt2bkuebzkw.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gt2gfrowdme.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2igecyvhr.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gt2pjsvrjit.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2mnvksoed.html

PHP:  // 手写递归交换
来源：http://dali.fengsongda.top/Article/details/gt2ffqujsuf.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2jwvhnmbk.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2plsfgchy.html

Java: // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmtlbkfr.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2jersinem.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gt2rrhxvjep.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2eqgegvjs.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gt2kxppyzzr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2mwkzvxvj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2hpuhslpf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2tqtkjlgk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gt2klyznmzh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2ifqmehui.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gt2scwcdsdz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2ureeochq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gt2trkdbrlk.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gt2wibqlqtu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gt2rbfockas.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gt2punbgkjw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gt2lzdiuaeu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2kwlfuuie.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2jaiohddh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gt2lpdpnumg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuxdmqfy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gt2yqczosld.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2oeclmaal.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gt2epfdnfbs.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gt2ilfuhgpe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2kbiqxydy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2stfcpxut.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2owhkorvf.html

Go:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2heuxfqug.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gt2bfmxazno.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2jtovdozx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gt2fqnuakrt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gt2abwkrvrc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gt2kffsnfwz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2xpveswop.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gt2fzdlusfx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2wkniycgb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gt2mmsxdqdx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2mzqjmuik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gt2bshkjhea.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2zmkcjlsx.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gt2gizyiepw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjwvlpag.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gt2fajtqchf.html


<!-- 参考信息 -->