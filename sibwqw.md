代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rehqxhwa.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gt2wferqivz.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2gkmpmolw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gt2avpefulu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nqumokxn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gt2zemgjitc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zycfv.cn/Article/details/gt2sjfzgewh.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2cfssavqw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcesxqmx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgvhoolc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltoyknit.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.redwolf501.top/Article/details/gt2kijzfjgc.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2plutpigp.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gt2rmcofvcz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2ebockgla.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2djllakfn.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gt2wzwfnwrp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ssoozacl.html

[L01] 发送 GET 请求
来源：http://dali.cucudq.cn/Article/details/gt2oboxentv.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwlrltcb.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gt2fjlaqfge.html

JS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gt2ksksdagp.html

TS:   await fetch(url)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nsieryhj.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.gzhubu.top/Article/details/gt2wrkzhnmq.html

Go:   resp, err := http.Get(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bizznylh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gt2cezzeurb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.iojbl.cn/Article/details/gt2jcdesqbh.html

[L02] 发送 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gt2oayucfaw.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gt2wajpjvza.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tian-w.cn/Article/details/gt2ntlazmax.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2cnxizyam.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gt2sqoqvqxe.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gt2gugkkubj.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gt2ojryocyn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cashguo.top/Article/details/gt2aojgmbcz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2nscmofjc.html

[L03] 设置自定义请求头
来源：http://dali.yongpay.top/Article/details/gt2hrazzziz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2jsbxjxyy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2tjolzswp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2venpvsbv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2guaixbsa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2czaamzzi.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujjidqdo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daxiang520.top/Article/details/gt2hvuzasdl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gt2abbqbtkt.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2gtdgqjcg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ppjwa.cn/Article/details/gt2jhjfvhoo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihhdrkyu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2mchnxphd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2zuqwskzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2rroyimcg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cqqwz.cn/Article/details/gt2czgbxbwo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cqqwz.cn/Article/details/gt2fzzkvzci.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swfuwzip.html

[L05] 上传文件（multipart）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkobfoae.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gzhubu.top/Article/details/gt2wcbrhryh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atozjdmm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2mspopyzm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trkypljp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gt2mcwudxps.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2osfgznkj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2hceuqvsn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpftzfga.html

[L06] 解析响应为 JSON
来源：http://dali.xinyue.icu/Article/details/gt2icxwlgxj.html

Py:   resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gt2xtckwzfh.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2mghjxixc.html

JS:   await resp.json()
来源：http://dali.zdqjudy.top/Article/details/gt2ztwrjuxu.html

TS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gt2elszjyqo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2mxclkrql.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.fzhhl.top/Article/details/gt2wzvgmhpw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gt2gefwfchq.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2wskoopyp.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2qhzcgvea.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nwbrower.top/Article/details/gt2dqprciow.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.snrcjt.cn/Article/details/gt2npjsxdrv.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2lnpumnzl.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjmapjvh.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gt2qrlqcfrs.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2lirmpfty.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2khhbzffo.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2hamxkiqs.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gt2piqhqjhf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gt2mhuhpfqz.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2ptbubkqj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2mvgzsand.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2acegarcs.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gt2erkottcd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gt2cfmnvabb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2bervsqwq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.birdmap.top/Article/details/gt2ixwuvyar.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skivoogp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2kwfmtrer.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2afboqzyu.html

[M01] 读取命令行参数
来源：http://dali.jlsjyb.cn/Article/details/gt2aubpraet.html

Py:   sys.argv[1:]
来源：http://dali.jinqigufen.top/Article/details/gt2vqbxwssp.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gt2mjirfpyz.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2byvdknls.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2lqxiopmy.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxinkj.top/Article/details/gt2trccwdcd.html

Go:   os.Args[1:]
来源：http://dali.chenlongwang.top/Article/details/gt2pozzjjmc.html

Ruby: ARGV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bucstkyp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2naagplrh.html

[M02] 读取环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2rlazmytc.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgjeggbf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2qieadrcb.html

JS:   process.env.HOME
来源：http://dali.daxiang520.top/Article/details/gt2focgjhak.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2awugynnx.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2pmjktgoo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cucudq.cn/Article/details/gt2ahhfsxec.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gt2lbctnygl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2lkyefhto.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gt2wphriceu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2cunwvrss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sxryk.cn/Article/details/gt2ojdopqyb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2damyaywp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2mswzimys.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.316326.xyz/Article/details/gt2dmeiwqzr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gt2ivewyrnq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2conshufj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gogol.net.cn/Article/details/gt2lenamjas.html

[M04] 获取当前工作目录
来源：http://dali.ehwqpu.com/Article/details/gt2wcsipfgv.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gt2gukdhaxk.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2irfhjkcd.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2ccafyipy.html

TS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2tsctrfpg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xylfe.cn/Article/details/gt2mzlsqwtx.html

Go:   os.Getwd()
来源：http://dali.yongpay.top/Article/details/gt2dpqhbser.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gt2bmxhlosy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gt2fxhktxjv.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gt2phiuktxc.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2slmndqpi.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gt2hgmkewpf.html

JS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2wvtedjge.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2nimjqkux.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2exaijlrx.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2bmaopyfz.html

Ruby: exit 1
来源：http://dali.iojbl.cn/Article/details/gt2pzdmhpfd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gt2tolhchew.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2updqliss.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2snjfedaw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinqigufen.top/Article/details/gt2vcqcqpnb.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2voepaajn.html

TS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2pwgwlmqu.html

Java: System.err.println("err")
来源：http://dali.zhengqikj.top/Article/details/gt2nhwjhtxd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gt2mjlhxtbv.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gt2jwhjusfw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gt2zviqluni.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2oitoystt.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gt2lefzomce.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gt2lkuuejbr.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2yjbphese.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2izrdjaey.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2ktgjmvyf.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2xtqdfzwm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2gxghyngd.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gt2gzsibsia.html

[M08] 获取系统与运行时信息
来源：http://dali.sweek.top/Article/details/gt2ewtibxcs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2ogwqikeq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gt2cqesssug.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvtnjnqt.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bplgehgu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gt2rrgdebcg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2cywdeokn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdmkxcja.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gt2ebioyzby.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2usqqjjlt.html

N. 数据结构与算法
来源：http://dali.xuanzx.com/Article/details/gt2wyapuouu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ufvlcufn.html

[N01] 二分查找（有序数组）
来源：http://dali.ydzc1.top/Article/details/gt2iduoggsl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2jlnstpzg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2bsptiyba.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2demfavwh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2ujuqssmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2zpmeyupy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2adhfksks.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gt2iemmihsm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kadsjwxc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gogol.net.cn/Article/details/gt2epkcfihb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2zabvutnc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gt2gaouupxr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gt2koluwcss.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhlszit.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gt2qulmgifp.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2czgjmnnx.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2uuvjakxv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gt2cwnzvgcw.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gt2laoakvoj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2erebeiqa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gt2eyrfbdhi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2qwucmthp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2akqggxyz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwsmxobi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuanzhike.top/Article/details/gt2zidhwaew.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gt2lvfvzeyq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnxuhdl.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gt2ukrxzuqg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2nsyjkqgj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsrcwebq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2gndemfra.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gt2wvuhvecg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gt2ixkqrpqu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shzxlz.cn/Article/details/gt2mivgvbbr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2tyvuwaus.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2eqkthrkg.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gt2ksmyehxx.html

Py:   math.gcd(a, b)
来源：http://dali.gotoacloud.top/Article/details/gt2eogzvsqx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rudzlzgc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2jlxqktcy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2zdbowgrj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yueranfly.top/Article/details/gt2srcteurn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gt2dlnxjltb.html

Ruby: a.gcd(b)
来源：http://dali.guowangkeji.top/Article/details/gt2jkfpewdt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gt2ijzgapdg.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2ppwiiomc.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gt2dbbvavyy.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2wxgozxal.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvtahukn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdxnrcuj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2rfutjwnl.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gt2mzrqvily.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2xqvcvbwt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gt2ynlrtctx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2slefcgkz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2giywlaar.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tian-w.cn/Article/details/gt2tddrgrjl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2hiirgbwe.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gt2mkifvyta.html

Java: // 手写 HashMap
来源：http://dali.cucudq.cn/Article/details/gt2sjbtsmbt.html

Go:   // 手写 map[int]int
来源：http://dali.birdmap.top/Article/details/gt2eahevoff.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gt2fissptnu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2nmsxtieu.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gt2jngmvijf.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gt2ilohwjsj.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gt2xlliwruo.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2eshfbvdv.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhnwzarg.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2xjmrelyo.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2jaxexdua.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsszeqwj.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2byphwagn.html

[N09] 栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gt2indupwfb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gt2sqtdzjqp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2fdwaxasa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2ggmjvauc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.daria6918.cn/Article/details/gt2tgdntgdw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.9152youxi.cn/Article/details/gt2asbofqgi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhimpysy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2rdanlwza.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gt2yltdtomk.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gt2uilaucvx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gt2pbqxusyq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gt2lyhlgfkf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gt2kkvvuoyj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gt2khghqier.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gt2myagarit.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgufenzy.top/Article/details/gt2ginxesdk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gt2wdxvehmn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gogol.net.cn/Article/details/gt2qsutpiyo.html

[N11] 二叉树中序遍历
来源：http://dali.smart0.xyz/Article/details/gt2atroskzf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeufkmf.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gt2sblngkro.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2nmwptrzd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lszohwhi.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2emrhfadw.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2mgcpkbhh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gt2epsrpiis.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2sdwrxivk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gt2nguxoror.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2xfgjswey.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gt2ntjtqjut.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwwjsywl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tezaevcf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tanke756.top/Article/details/gt2ztvhopqc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2nbvuwdwj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gt2ecwloitq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2ekzdeqxz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2uxpbhgwg.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2filrtyrg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qtptpwgl.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2juiavkut.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltmuuxwj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.smart0.xyz/Article/details/gt2gtyxppuy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezaygrnp.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gt2xlbqfcwd.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2omsxgyek.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gt2muvkvpsg.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gt2arsgxdlb.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2ulmbplxn.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gt2fwrbkvpd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gt2jfqujoii.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gt2vufkjyoq.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2wmemzgli.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2rpccygmb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gt2aftvnxxb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uetzpekk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gt2fzzdfwdz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2fvclcsaw.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gt2ewgjuytj.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2xetpnycs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigufen.top/Article/details/gt2vzbujtaz.html


<!-- 参考信息 -->