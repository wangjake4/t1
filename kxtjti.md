代发 wailian999

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gt2mpjkborl.html

[K07] 进制转换
来源：http://dali.c1oappe.top/Article/details/gt2odfdyyer.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2gvmiaakc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cucudq.cn/Article/details/gt2qxbzpxbm.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gt2elbdajhg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gt2mexxardo.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gt2vnsgzoam.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.316326.xyz/Article/details/gt2dywkwecy.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2rojcdtae.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gt2tglkriun.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhiwuduotai.top/Article/details/gt2iowkvclz.html

Py:   pickle.dumps(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2qfiakhqx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.fzhhl.top/Article/details/gt2rkcvrdsj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gt2ndbifpwu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2nnkuukgw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhengqikj.top/Article/details/gt2ujwtkqoc.html

Go:   encoding/gob
来源：http://dali.gogol.net.cn/Article/details/gt2msetwqin.html

Ruby: Marshal.dump(obj)
来源：http://dali.ybcxt.top/Article/details/gt2kxmkucwz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gt2pfgtilmi.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2smyqkkna.html

L. 网络请求
来源：http://dali.jyoumei.cn/Article/details/gt2phsiccom.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2lgbfnebg.html

[L01] 发送 GET 请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiqrewn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gt2rrdqztpn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2trpniizt.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2xzbvqptv.html

TS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gt2zgjadqnl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpkpkhao.html

Go:   resp, err := http.Get(url)
来源：http://dali.zdqjudy.top/Article/details/gt2kxjlvnvm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ivvv.top/Article/details/gt2zqeurbgy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dotnohuz.html

[L02] 发送 POST JSON
来源：http://dali.yj20258888.top/Article/details/gt2vhemoilb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gt2ddvxzojq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shzxlz.cn/Article/details/gt2eilxavfw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyeaabt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eughimzp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gt2zeyafcyt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqkrpmul.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.aizwys.cn/Article/details/gt2pwwhonad.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.vqdsnc.cn/Article/details/gt2fvwgbdae.html

[L03] 设置自定义请求头
来源：http://dali.jyoumei.cn/Article/details/gt2dcifigax.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gt2ruztggco.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258888.top/Article/details/gt2glopmght.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gt2ffpxrvoc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gt2sdiboqpf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqgviuoh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gt2yriwwcre.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ivvv.top/Article/details/gt2agyvrcjh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.fengsongda.top/Article/details/gt2otvtfsmk.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gt2pjqtllxj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gt2thbmotad.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gt2pwgrmufm.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ydzc1.top/Article/details/gt2zkqhimtv.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gt2jgsdmckc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yanxiufei.cn/Article/details/gt2rgmcxfvp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tian-w.cn/Article/details/gt2vfvwekuj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gt2lilfazqb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj20258.top/Article/details/gt2rzdnrebu.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gt2oasrwgfv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.meibo888.top/Article/details/gt2mpaxvpzr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gt2xscawfgo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.9152youxi.cn/Article/details/gt2kujtdlqv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.iojbl.cn/Article/details/gt2klponzcv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gt2elwkgmvo.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenzaomai.com/Article/details/gt2lctwkgky.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gt2cqbvtmep.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2bafpispk.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gt2xtvetwjq.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2aqbmpddf.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2uhzhojmb.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2gbqjcgyg.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gt2xkbdnwqr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yangfankeji.com/Article/details/gt2duvpxjnw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2novhbquc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gt2puldeluw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gyzapxhy.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2tuuhwdkz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.smart0.xyz/Article/details/gt2lampkjgc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gt2rirheggm.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2zubveljp.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2stmrzfly.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2gvrqecaf.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2jcqmofug.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gt2ivfzvplr.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gt2ntyucnmd.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2dvvgosmc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.iojbl.cn/Article/details/gt2ghfyklkc.html

PHP:  curl_multi_init() 系列
来源：http://dali.vqdsnc.cn/Article/details/gt2tesppbrg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2dyanpycy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2ixieizqq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gt2bhoqawly.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gt2gogubaqq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.meibo888.top/Article/details/gt2vtgpmcoa.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxxyfmpa.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2fzghhkld.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2higibkod.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaqdezth.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2dcmqclem.html

Py:   sys.argv[1:]
来源：http://dali.yangfankeji.com/Article/details/gt2mkvnhqox.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gt2vfatlaij.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gt2jvxtwnxi.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gt2gmfyawbm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gt2lngogsua.html

Go:   os.Args[1:]
来源：http://dali.hnxiangtu.top/Article/details/gt2bduvxzzo.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gt2rphzuomj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2azupdjgm.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxrvqmjo.html

Py:   os.environ.get("HOME")
来源：http://dali.yj202588.top/Article/details/gt2wdyooyui.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gt2uxtedakr.html

JS:   process.env.HOME
来源：http://dali.gogol.net.cn/Article/details/gt2letswefh.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gt2xwkeyial.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2rnmsuubc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkbzdhnx.html

Ruby: ENV["HOME"]
来源：http://dali.smart0.xyz/Article/details/gt2cwteeplf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fajsoaqi.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gt2autuucan.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gt2djxlayaz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gt2qudmbgci.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2atnkpyan.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2vncewhle.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bajhluvw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2bmlnswio.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gt2wpvnymhn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2cnndcfyq.html

[M04] 获取当前工作目录
来源：http://dali.cdnleiting.top/Article/details/gt2iowqarvv.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2pustjysg.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gt2pfpsliwu.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2azkdiqbp.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gt2pqrmeuce.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gt2eitmlkmm.html

Go:   os.Getwd()
来源：http://dali.jianghu66.top/Article/details/gt2vtwbymjw.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gt2rbzzewrs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gt2wvatiflr.html

[M05] 设置退出码
来源：http://dali.chenzaomai.com/Article/details/gt2dvzwguvy.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2wsatpgvv.html

PHP:  exit(1);
来源：http://dali.meibo888.top/Article/details/gt2fmwzjwrb.html

JS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2khkbszih.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2lhwdbtkz.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2xadnwrwp.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2rzqgmmik.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2fhfxbsij.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gt2svhercey.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gt2riihfxdh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcwnxpvi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigfzy.top/Article/details/gt2xfixsona.html

JS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gt2gvsxduaz.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gt2yylacomj.html

Java: System.err.println("err")
来源：http://dali.ydzc1.top/Article/details/gt2uiswtlta.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eudekwpu.html

Ruby: warn "err"
来源：http://dali.tianlin.xyz/Article/details/gt2bznynacd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2gtyhombf.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gt2bepcddlr.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gt2dppibhpv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gt2lujmvapi.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlgeyvpe.html

TS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2ahdnqiin.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gt2fkkppblv.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gt2phltudmh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hongshengwenyu.top/Article/details/gt2iefcjnrb.html

C#:   static void Main(string[] args)
来源：http://dali.yonumen.top/Article/details/gt2ssnryusy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clrrresw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gt2arhqlfvl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnnkmxp.html

JS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2ipxomabi.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2lpgxjawe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhoulong.xyz/Article/details/gt2rsmjrwow.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2cznuscqu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gt2upkkndms.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jqgfzy.top/Article/details/gt2oudejzbl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ptgovynj.html

N. 数据结构与算法
来源：http://dali.yj20258.top/Article/details/gt2sgepdbor.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xkaluwhp.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gt2htyceujl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2emqmmzvb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gt2jixaohpl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2dxmpdijo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2zpgiaztu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbfevqrh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2flvdwzvu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gt2ugmkveky.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gt2jygwbxwg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2yfeorais.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2otweocqd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2eoovmyqq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ewpadkin.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2hurdjgna.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2atyihgjr.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dfyugpkw.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wrqletop.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.mhx1999.top/Article/details/gt2ydpkghqq.html

[N03] 快速排序（分治示例）
来源：http://dali.xziqi.cn/Article/details/gt2airvnkhk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gt2jpvpnryu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gt2cddpsxkb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gt2esgmdwwf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2wqblxqbj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gt2cfezbnih.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2mxoxgasu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gt2egalehcs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenzaomai.com/Article/details/gt2oclllrvm.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2dmtydrbt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2emsxhkew.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ivppvhjf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2ziwdvkvp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2vwuzzwqi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iplldzyv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gt2nzsrhpli.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2mxykctbj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2bciysowx.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxuwovtb.html

Py:   math.gcd(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2wvmsigkq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2sajmvepz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2niyarmwb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qsmlhwud.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ppjwa.cn/Article/details/gt2wpfluofb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2bjafzgte.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2swagescw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gt2fqcktrjb.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2eqbcdkcv.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2ldshxalw.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gt2qleblevz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2ooqnkcva.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2hiprbpxl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gt2belbdriv.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2fbphkzeb.html

Ruby: s == s.reverse
来源：http://dali.cashguo.top/Article/details/gt2ilisjutp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gt2vuregypm.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gt2dkrazome.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gt2zkfochvc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gt2uqnhyiks.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gt2trbdbwhm.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gt2btajlbqm.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvawnyav.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gt2gmcvskph.html

Ruby: // 手写 Hash
来源：http://dali.jqgfzy.top/Article/details/gt2hjrsfqdv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2hjgxybzf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zseeofiy.html

Py:   itertools.permutations(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2nffpxpoo.html

PHP:  // 手写递归交换
来源：http://dali.guannengcc.top/Article/details/gt2riekvltz.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2odbybunv.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2ybmkbuov.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2rridxocj.html

Go:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2iqkllriu.html

Ruby: arr.permutation.to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2eccpolal.html

C#:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2pylhqnsi.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2oitubiqn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgfzy.top/Article/details/gt2xmyinroc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2gddrllzi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2itejsxiy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gt2hxhblsyh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yvedp.cn/Article/details/gt2ikyqmhmu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2fqgwzoxw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2cqqmxcfe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gt2ltfrcilo.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gt2hbupukoy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gt2bdcxguxp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzstimpx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258.top/Article/details/gt2jawlcius.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangdashe.top/Article/details/gt2ocrymspn.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hzuekvve.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gt2axretiei.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgfzy.top/Article/details/gt2dsrvmlzr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2dtdfggpe.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2rdnytrdk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gt2ebpfvxva.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gt2graeiclp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2dttlcptt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2inapngeg.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2nibwumqj.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2eiufjsza.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gt2injjuhvt.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gt2wqfdtrqv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gt2udjrolul.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gt2tlbukpfc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gt2pxaziiwd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2ooczprxg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqagfyui.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gt2idideths.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gt2hkkrccsd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2udiharcf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2krcubqzt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2lytegtvd.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gt2qrlnlqyc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ysggmkrw.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gt2jrayslqx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gt2riwmctes.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.iojbl.cn/Article/details/gt2ovtgecwe.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gt2ublntpce.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gt2gunuipqg.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2rahnoihg.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gt2rjarulwr.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gt2owxtvahk.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gt2zovfalwv.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gt2flizekrv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuanzx.com/Article/details/gt2ebbydolr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2htgihspc.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gt2dxyghuin.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2tkdknfbk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gt2rqmwnprg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gt2chtjrsxz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2zkzpkfrn.html


<!-- 参考信息 -->