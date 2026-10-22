代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cucudq.cn/Article/details/gt2zwrbnkoy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gt2honkydxr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jyoumei.cn/Article/details/gt2spsqgkoy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2peqcwyly.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2rbfsbazl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gt2xeoztdqc.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gt2xkchnjam.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gt2msrrajgq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2vstgolkd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.birdmap.top/Article/details/gt2tgzzstct.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jqgfzy.top/Article/details/gt2xkrpnwtc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2arihqlwg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gt2lerskkho.html

[K07] 进制转换
来源：http://dali.0kj1m.cn/Article/details/gt2gjhhyxqi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ppjwa.cn/Article/details/gt2xihtodja.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gt2rmelkwkz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gaohongyu789.top/Article/details/gt2yucyykhq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2rzzfhkyv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gt2ihtssxhn.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yangfankeji.com/Article/details/gt2igmsrpmo.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ybcxt.top/Article/details/gt2fexzduyy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2fuqxoolq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2fsvqbzcl.html

Py:   pickle.dumps(obj)
来源：http://dali.ybcxt.top/Article/details/gt2vtyxpahc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gt2ggopqhbq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gotoacloud.top/Article/details/gt2huidvetq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gt2cyhdikyx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sweek.top/Article/details/gt2knqkqscq.html

Go:   encoding/gob
来源：http://dali.yongpay.top/Article/details/gt2prusyaqd.html

Ruby: Marshal.dump(obj)
来源：http://dali.mhx1999.top/Article/details/gt2rlndnodf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ppjwa.cn/Article/details/gt2ywxnabqj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2msutlvxg.html

L. 网络请求
来源：http://dali.yangfankeji.com/Article/details/gt2gseezcso.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2enmyoqhd.html

[L01] 发送 GET 请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2zaacdbns.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eskbeikx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinqigfzy.top/Article/details/gt2myirrnqv.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjwsgfve.html

TS:   await fetch(url)
来源：http://dali.nwbrower.top/Article/details/gt2fprajhof.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cucudq.cn/Article/details/gt2gpystttq.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfqukcup.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gt2clojsxym.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenlongwang.top/Article/details/gt2nqhyjslf.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gt2zligsckk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbksyznu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shuidangran.top/Article/details/gt2booxjvte.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhiwuduotai.top/Article/details/gt2zndxenfc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cucudq.cn/Article/details/gt2adztbbgp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.svipenyu.cn/Article/details/gt2newvhejy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yueranfly.top/Article/details/gt2mbpvbkob.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gt2rbdddwkv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zdqjudy.top/Article/details/gt2ctloftpb.html

[L03] 设置自定义请求头
来源：http://dali.birdmap.top/Article/details/gt2xmjlenok.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gt2ihbobxls.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhengqikj.top/Article/details/gt2nhxoowhl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfzxpsqc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gt2burzmplu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinqigufen.top/Article/details/gt2vhziwgmm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gt2vssudcyl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cashguo.top/Article/details/gt2dhjccnxg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2dnbvttla.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gt2pemmpouw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gt2mntdegkw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gt2knqosujd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2khekkirw.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangshuangyany.cn/Article/details/gt2tshsuvqf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tian-w.cn/Article/details/gt2ouwccfhl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhengqikj.top/Article/details/gt2ehiycjhh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shuidangran.top/Article/details/gt2ocvdkcji.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gt2wqpwzukg.html

[L05] 上传文件（multipart）
来源：http://dali.yvedp.cn/Article/details/gt2qrsyofvq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2wdzydpzm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gt2spdcnbxl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2uqvezhll.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2oyisfqau.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.bjfxy.top/Article/details/gt2ivdfmeav.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rucrgahq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2dgezbwzy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2caukkmix.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gt2jnktkgto.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2erwhaiku.html

PHP:  json_decode($body, true);
来源：http://dali.daria6918.cn/Article/details/gt2habhuitu.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpmnfghe.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2hsoinska.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cqqwz.cn/Article/details/gt2zoawdnbn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gt2lqdbeeno.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gt2zgxgdnxu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jborsdnh.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2audnezpf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2yiwtnbmf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2vwhfjzou.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2imdtpovm.html

TS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2dwjzadqw.html

Java: resp.statusCode()
来源：http://dali.yanxiufei.cn/Article/details/gt2mgwmkced.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2oxstjdoy.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gt2spqrgibu.html

C#:   (int)resp.StatusCode
来源：http://dali.xylfe.cn/Article/details/gt2gzvefqms.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggooarra.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gt2irdefkyz.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2equztsri.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2qzytomvi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gt2vtzrouvi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gt2znugnxzd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzaovujc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2oaswkcem.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gt2hpjfytej.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2vxjslnny.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gt2zmsrcqpy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2osgndzrh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqbmfjo.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gt2tcxuzhse.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2xoklgiky.html

JS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2aczetjgt.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2vbejeihu.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2snnszhlu.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gt2aobavfrv.html

Ruby: ARGV
来源：http://dali.birdmap.top/Article/details/gt2snsknzwk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2bilkwzmr.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gt2qwnjkekg.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2jdzdiwjg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2qjbzjoro.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gt2ltmnunat.html

TS:   process.env.HOME
来源：http://dali.yangfankeji.com/Article/details/gt2dyzeyzoc.html

Java: System.getenv("HOME")
来源：http://dali.pycfn.com/Article/details/gt2hvipijde.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2yixhprnl.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2eofzbzld.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2mgjqswxt.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gt2izfzigbz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gt2zvjaodbg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gotoacloud.top/Article/details/gt2zzvlsokq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2kzgjjdtd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2ougrhcfq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuxming.cn/Article/details/gt2tzomnewu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gt2mpghuvqd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gt2wagxnkjd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2bpjqozxs.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gt2bedflmdm.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2lnprpioe.html

PHP:  getcwd();
来源：http://dali.smart0.xyz/Article/details/gt2bfcclqap.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2dsrwkutt.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2qnteckcu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gt2jfljqzdn.html

Go:   os.Getwd()
来源：http://dali.hysaishi.cn/Article/details/gt2ggjsydiu.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gt2lbnccvbg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gt2xtpdqfzw.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gt2publjijx.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2amopkiij.html

PHP:  exit(1);
来源：http://dali.daria6918.cn/Article/details/gt2ameaoqbz.html

JS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gt2svhuwdgn.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2vtchskvw.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2nqexqgfv.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2yotqdgnf.html

Ruby: exit 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2bcptijkp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gt2ahzzmpyx.html

[M06] 向标准错误输出
来源：http://dali.snrcjt.cn/Article/details/gt2pngjpiss.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gt2huiwkjyh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2jfongnsu.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2lqdsfmay.html

TS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2utcibnhq.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gt2qecmrzmw.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gt2xdxngbta.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjsmnjuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cdnleiting.top/Article/details/gt2nmuelxbl.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gt2dwiloptd.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gt2lihrvujt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gt2fpjclakd.html

JS:   require.main === module
来源：http://dali.0kj1m.cn/Article/details/gt2sshksdzx.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgotyqch.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jadbdued.html

Go:   func main()
来源：http://dali.sxryk.cn/Article/details/gt2xqeiyaut.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2sgkwmdhl.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqwyxaoz.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gt2lihfjfag.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gt2dgqjykpy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gt2dlnfoqlt.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2qvvcggpk.html

TS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2dgwflykq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cdnleiting.top/Article/details/gt2hehcnijb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gt2wwzkdagv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gt2praedpgx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gt2mqhwyyen.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2pqbxzdvy.html

N. 数据结构与算法
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgmkcqna.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2uxtssvws.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gt2yuxljhvm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2gdyzibtn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2eepbvqbm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2vikznjph.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2vdomefjz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bdeeofil.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2fgnxohet.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gt2gocshvij.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gt2qrqqyodb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gt2ndtghute.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2wuyksymw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2imugxcme.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2ggxkynyi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2djnpyfqj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2zpienyqi.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nmbtlmbz.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2ydupgsdr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gt2yfkojbuj.html

[N03] 快速排序（分治示例）
来源：http://dali.jyoumei.cn/Article/details/gt2dumkadck.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.c1oappe.top/Article/details/gt2qzqjamgl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iixyocrc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ydzc1.top/Article/details/gt2vhpptgok.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gt2ghxivzue.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gt2rbmjonoq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhxvqbah.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gt2usxqfcly.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sufxvd.cn/Article/details/gt2tmbtjhpo.html

[N04] 斐波那契数列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjyevxpj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwijxwsz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2lwnnzisp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2elycogan.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2gcsopmmm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qansgsww.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gt2pwlradeu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gt2atzmxbrr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2acuhjtxx.html

[N05] 最大公约数
来源：http://dali.9152youxi.cn/Article/details/gt2avjgnjjo.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2ytvyznto.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnqzz.top/Article/details/gt2pfeliphj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2dreeaizj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2lrcavkni.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gt2tkntangs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gt2lteqheat.html

Ruby: a.gcd(b)
来源：http://dali.yvedp.cn/Article/details/gt2pzvzntsv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2ofsdfxnj.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2gvxffqra.html

Py:   s == s[::-1]
来源：http://dali.yj20258.top/Article/details/gt2dsnhsqbe.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gt2fzccgoht.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2eqimltpd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2aczoanho.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gt2wefxryjh.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gt2lkoooexc.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2shsnakeu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gt2wwpesmjt.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gt2fhgaiycb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgmxomqw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.redwolf501.top/Article/details/gt2affhssog.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.iojbl.cn/Article/details/gt2olppthkh.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gt2wxtzrefv.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zcrlrflv.html

Go:   // 手写 map[int]int
来源：http://dali.guowangkeji.top/Article/details/gt2nfwcagyy.html

Ruby: // 手写 Hash
来源：http://dali.birdmap.top/Article/details/gt2ixecjzfx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gt2mjlfumgx.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gt2xudnzohh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2wgvbztxl.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gt2jpypcasd.html

JS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2bkbyruop.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2fmlddklo.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2vmfpioby.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2tcnazqqv.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gt2wylqttjt.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2cyaymecq.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2nyqeocwa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gt2hmvnpkva.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2bxhgjqhw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2wsbbvcyn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gt2gfgxynhv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2kxpqtbuh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gt2lzkpilkz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2ucqexnzn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gt2qqfvqlga.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2ylcohfzz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zdqjudy.top/Article/details/gt2vaffknoa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gt2hsifbmjd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jyoumei.cn/Article/details/gt2zntlbabh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.c1oappe.top/Article/details/gt2odzqhdlx.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gt2dwnqzsfo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gt2qlwucbke.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gt2rjxgqewb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hammf.cn/Article/details/gt2sykhevqr.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gt2stresgfm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gt2liybtmmy.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnfmnnud.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gt2pfuxsfwh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2orxplyxi.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gt2bpqdecbk.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2lzgqgmzy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gt2bllxkyxv.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2xiaqmrte.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqcsiskw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2wctqncem.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gt2orxqldtt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2krjrpnnl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2qzmiaiql.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gt2jkgkolqh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2evlwhper.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2qpmhtrnv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2ftkoiqrn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fplfgpry.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gt2kujjzypa.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2rqmlxcij.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gt2corhlpcl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gt2gwryohym.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gt2wiaurnav.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gt2aechhmkp.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gt2qmfqcqff.html


<!-- 参考信息 -->