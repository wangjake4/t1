代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gt2guilnwbl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2qpuejlyu.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.bjfxy.top/Article/details/gt2cznvzwtn.html

Py:   pickle.dumps(obj)
来源：http://dali.daxiang520.top/Article/details/gt2ojsrerqz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gt2keqpjgli.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gt2yhyhoyto.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gt2hguiopxf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jinqigufen.top/Article/details/gt2dqhllyjl.html

Go:   encoding/gob
来源：http://dali.jyoumei.cn/Article/details/gt2matmawml.html

Ruby: Marshal.dump(obj)
来源：http://dali.yvedp.cn/Article/details/gt2xjfqkexg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2ofimtdzt.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ouybhaiy.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gt2fvssqviq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wfvzljsc.html

[L01] 发送 GET 请求
来源：http://dali.hnqzz.top/Article/details/gt2nzqiaonu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fzhhl.top/Article/details/gt2rcdloaex.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gt2vgwqtgmt.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2hqfduvzm.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmwpuimp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yj20258888.top/Article/details/gt2csgzqump.html

Go:   resp, err := http.Get(url)
来源：http://dali.hywenlv.cn/Article/details/gt2ynyffeqa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yanxiufei.cn/Article/details/gt2fcdetmon.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.316326.xyz/Article/details/gt2etordsrc.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gt2xbtuojty.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sufxvd.cn/Article/details/gt2ilgtcmog.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.andypj.xyz/Article/details/gt2xzahlouy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gaohongyu789.top/Article/details/gt2nxlhfqje.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2vyaeftou.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilehpzgl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.pycfn.com/Article/details/gt2qixlyhnn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tianlin.xyz/Article/details/gt2ryntemhv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnxiangtu.top/Article/details/gt2nybxlqcq.html

[L03] 设置自定义请求头
来源：http://dali.ehwqpu.com/Article/details/gt2jdgzhncs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hammf.cn/Article/details/gt2pnthlkye.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2ovmouagm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gt2zwwvocjw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zdqjudy.top/Article/details/gt2zbofnjjy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gt2btrakjhf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gt2icsgalup.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gt2zutcmunx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sufxvd.cn/Article/details/gt2acqyttmv.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gt2xuktrbum.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2dcnlbcbi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.snrcjt.cn/Article/details/gt2qespmizw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sysykeji.top/Article/details/gt2oglccqkj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2fgyiiskb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2pszfjhbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2majkvbdb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gt2erljplrn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2tuctpdsf.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gt2goxufjtp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gt2uarxdjqc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gt2iksbszal.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2hwzrhywz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gt2zadjsbry.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.meibo888.top/Article/details/gt2fsfoahsx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.gotoacloud.top/Article/details/gt2vzoedvxg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhongyouzk.top/Article/details/gt2tprqwecg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2ktdhdfwc.html

[L06] 解析响应为 JSON
来源：http://dali.zhongyouzk.top/Article/details/gt2dnjuuefl.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2sthelhfi.html

PHP:  json_decode($body, true);
来源：http://dali.yonumen.top/Article/details/gt2zlqtiowy.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2pncdmeyn.html

TS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2xehgwwip.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gt2pnkqmyev.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gt2rtubkmrx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2pviufazo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2ycrobjwr.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggofedur.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtuvknuv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gt2iahucpjg.html

JS:   resp.ok;  resp.status
来源：http://dali.jyoumei.cn/Article/details/gt2fgkrparo.html

TS:   resp.ok;  resp.status
来源：http://dali.cdnleiting.top/Article/details/gt2qdduucex.html

Java: resp.statusCode()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxoqjfha.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gt2molqvrua.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gt2lsqlfjgn.html

C#:   (int)resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2oiultrje.html

[L08] 并发请求多个地址
来源：http://dali.yuanzhike.top/Article/details/gt2vbfcbfum.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2izznkres.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxinkj.top/Article/details/gt2yhisncsk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iwvflogx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gt2vnzpawlu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gt2cgzbuivf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gt2sxbfklva.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2fpjlaifz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2dkwjvykv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2qdebjngf.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gt2jttodabu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2mldusmwb.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gt2whpietpm.html

Py:   sys.argv[1:]
来源：http://dali.wangdashe.top/Article/details/gt2qjluytjr.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gt2ykeaemls.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wirdrnos.html

TS:   process.argv.slice(2)
来源：http://dali.yvedp.cn/Article/details/gt2ozdjpxxu.html

Java: args 数组（main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gt2lljbzllf.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gt2qzhmsnvw.html

Ruby: ARGV
来源：http://dali.nwbrower.top/Article/details/gt2kczrsqny.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gt2hyuguuik.html

[M02] 读取环境变量
来源：http://dali.wangdashe.top/Article/details/gt2wuhttmbn.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gt2yzngnpzq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2ditugqxc.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2suifnjgf.html

TS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gt2zwzgkdte.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2txybubhg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2rpmpcdia.html

Ruby: ENV["HOME"]
来源：http://dali.shuidangran.top/Article/details/gt2sqskxoyq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2qmltyiec.html

[M03] 执行外部命令
来源：http://dali.dashuyun.cn/Article/details/gt2hvedjtli.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gt2ntrnrwhm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2utxmrrno.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fckwwzaj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2holpfnuu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gt2roljxzzz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybolxhvx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jqgfzy.top/Article/details/gt2uowgnclw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2myvdcgdl.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ybicwjqn.html

Py:   os.getcwd()
来源：http://dali.yangfankeji.com/Article/details/gt2wxinrofc.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gt2unbnhtnt.html

JS:   process.cwd()
来源：http://dali.dianchejie.cn/Article/details/gt2elivaxhs.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2hjsctssd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2rykzoywu.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gt2ikribmbq.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2ktdvwczy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2kvisxrzi.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gt2jwxklozj.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2bfhzjzxn.html

PHP:  exit(1);
来源：http://dali.ehwqpu.com/Article/details/gt2aosfkvmb.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2npxlladq.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2cwmovqsq.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2sqfzjlpk.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2qzmcjewi.html

Ruby: exit 1
来源：http://dali.chenzaomai.com/Article/details/gt2ahyrhmuj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangshuangyany.cn/Article/details/gt2kelrulem.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlazbirz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gt2zdyezxks.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxlyxyjp.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndvbxudo.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2xnnfopje.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gt2bqgestnn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gt2vvsohbjg.html

Ruby: warn "err"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqjzzrpz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gt2nnjeombw.html

[M07] 判断是否为主入口
来源：http://dali.chenzaomai.com/Article/details/gt2fwymzufh.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gt2drnendgs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xziqi.cn/Article/details/gt2ctrhuokj.html

JS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twiyudgy.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gt2trwrxmhi.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2vtdmxnhn.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2jqgxroyg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpellief.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gt2czygqsvk.html

[M08] 获取系统与运行时信息
来源：http://dali.hnxiangtu.top/Article/details/gt2wycaeehc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gt2adufhjma.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuxming.cn/Article/details/gt2tzzlfigf.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2ibkolusm.html

TS:   process.platform;  process.version
来源：http://dali.zycfv.cn/Article/details/gt2hwtxmqzd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2yentwiuc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cdnleiting.top/Article/details/gt2hytisyro.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gt2eepuzqti.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2imvrrwcr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2igmmbokh.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gt2zluwgkrv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2nykkwbfl.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gt2fgdwurnn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2hrriwnwg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gt2zosysyvj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2iajtuowr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2wgvxjtux.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2lvaszqcu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2rvoznwsf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gt2odsequtr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2ybeufixh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2yekkbrxf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2stevqmdx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2yiywafaw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gt2rhbakqns.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2fjhchnar.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gogol.net.cn/Article/details/gt2xyxrcqok.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2aomsdkva.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2ayovkdgf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gt2aibkwyie.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xckgpnzz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2dinfsral.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tanke756.top/Article/details/gt2gulcxjar.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubhmmahk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gt2jbljvcfm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2najlvibi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ydzc1.top/Article/details/gt2rhzmuflh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gt2oqexjfog.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gt2sdkgwgis.html

[N04] 斐波那契数列
来源：http://dali.cdnleiting.top/Article/details/gt2luisatgw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uqwrdouc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thvhrdbc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxggrpjy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2cypmavom.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gt2tiporisg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2gynzvfor.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2nvmywltv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2kcutnrpa.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gt2tsonogcf.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2awuwecpx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.smart0.xyz/Article/details/gt2pkydaooj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2kxgeaihy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2ndlonrwd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2nengadbf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gt2vgkvtgmx.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gt2sszhcuqj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fvqqnplo.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gt2mzauyegg.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2kukmmhdr.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2dyflzxgn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2lecirlhk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2ykhacxvx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2huqzunro.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gt2tpfaayhk.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2stbubdkc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2xvjidmxw.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gt2wuichxkb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2dyejcosm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gt2rigstngg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guowangkeji.top/Article/details/gt2tcjgfmct.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gt2jpxenwlx.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gt2hgribfxj.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnlxdlof.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2bwoqzpkz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txolcqcl.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gt2kpqjqaoe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2npzumsma.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gt2mhqhflls.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2yjibfkur.html

TS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2ojpyeefh.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsrjyjvl.html

Go:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2jddgcwvi.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2khofimmi.html

C#:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2mvavkeao.html

[N09] 栈与队列
来源：http://dali.meibo888.top/Article/details/gt2kovyyvtv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2zfbacrur.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2jqsxykjb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxlpwuvw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gt2ppwntxbr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dksggufu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2ytgjwwgo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2tlufacdb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gt2pxftvwlo.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gt2xhpurdqk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gt2acgplzvt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxrqmlwy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gt2qcjyzssp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2ddltclmg.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gt2nzzcgptm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gt2irhgtqnx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gt2rxbddaku.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gt2bbaeousd.html

[N11] 二叉树中序遍历
来源：http://dali.ydzc1.top/Article/details/gt2brxecjyj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gt2yhamicxs.html

PHP:  // 手写递归函数
来源：http://dali.yuanzhike.top/Article/details/gt2xitzvinb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2kqtpazez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gt2njylftbl.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2jhadvvee.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbjkqjgz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2nqvsfska.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2psoitubn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuivfbjn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2mhkzuerv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gt2cvuqphth.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2qjzicjop.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gt2rdwoleat.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2oivfczdu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gt2teyazlfl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gt2vrukibvs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2ktxvgsxr.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojoocyws.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gt2zipnennh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2yzsftzki.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2yqfiyfcw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.bjfxy.top/Article/details/gt2xunudzyz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gt2zduwddlu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gt2nkjmsjqy.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2fhxwczcn.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2bmcwfqwz.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gt2vobsdgvp.html

Ruby: Thread.new { f }
来源：http://dali.zdqjudy.top/Article/details/gt2bsryqglx.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gt2jirwhlmv.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gt2dejlbzez.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nkbszhym.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2dquatexf.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gt2ufnqvkiw.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gt2droxuiju.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2xlukbnmn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gt2akgjzwrv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gt2huxhqgvq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gt2odvagcem.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2cjqphpfm.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2auvcaxmn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gt2psrilbpy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfupipmz.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2qjqnyaxn.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2ilngrquu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gt2bykrlkpu.html


<!-- 参考信息 -->