代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.wangdashe.top/Article/details/gt2ipvnotnt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gt2wgtneqoj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gogol.net.cn/Article/details/gt2bwpfstai.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dashuyun.cn/Article/details/gt2ouxhzani.html

Go:   encoding/gob
来源：http://dali.iojbl.cn/Article/details/gt2llvdhrtz.html

Ruby: Marshal.dump(obj)
来源：http://dali.c1oappe.top/Article/details/gt2mrjepuqq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsrijafj.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ryxmsmln.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gt2jqkzcrau.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2jhqtgdku.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gt2ljwqlslf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gt2gjyhlldo.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dashuyun.cn/Article/details/gt2dcyhodqu.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gt2akwjeodr.html

TS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjthenuo.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gt2rdcvhhma.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gt2srhmkjxa.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.chenjidiqi.icu/Article/details/gt2pddgfluj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xuanzx.com/Article/details/gt2ututebzd.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2remlaadb.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2dfafgyes.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.wangshuangyany.cn/Article/details/gt2qcjiwzqv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gt2pvllhtmh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2snywhygq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gt2fcswtmev.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yj20258.top/Article/details/gt2aakrskhi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.dashuyun.cn/Article/details/gt2dedzuvpz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2hokhbgzq.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gt2awfkcqqp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gt2laivvygf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gt2slwtfzcg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2frhnvgwc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2nwqzjnhh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhongyouzk.top/Article/details/gt2ovsfqywx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2scezymme.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ydzc1.top/Article/details/gt2uglgbrmu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sweek.top/Article/details/gt2zyuxstmg.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2xyvriuwq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gt2uyccrlac.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2wiqqywml.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2wejgxcww.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2semalpcx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yueranfly.top/Article/details/gt2vodpfyow.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2nnplxyws.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.dashuyun.cn/Article/details/gt2fdzfzril.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2nbtcrxpy.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2mpgmdbmc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigufen.top/Article/details/gt2wnofjtjo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuanzx.com/Article/details/gt2ixflpjgh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cxwzejax.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2maxtuano.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2gpmbnfem.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhongyouzk.top/Article/details/gt2dmfavvys.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gt2sqqyopsz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2avujckmo.html

[L06] 解析响应为 JSON
来源：http://dali.hnqzz.top/Article/details/gt2cntijwnk.html

Py:   resp.json()
来源：http://dali.tanke756.top/Article/details/gt2ieouwuuj.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2raabvvlg.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2gfxnmnod.html

TS:   await resp.json()
来源：http://dali.ivvv.top/Article/details/gt2gezkppif.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2xnjyszlw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhongyouzk.top/Article/details/gt2uwylndwb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifhzdzug.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2fzxzkrph.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenjidiqi.icu/Article/details/gt2lizncrbd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2kofeeorl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2xninkflr.html

JS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gt2jyuglygp.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2wwqdmjov.html

Java: resp.statusCode()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vevanhcd.html

Go:   resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gt2uwtjbxcu.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gt2cginbpfs.html

C#:   (int)resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2qruxboor.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2rdjujrvy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhpfoumv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gt2exguudmx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gt2idmtftde.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbdhnxtf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gt2wjqianeo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2suzdrggw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gt2vtnjqglw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozmsfhbs.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2uycytbzc.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2zqjxdxrw.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2eilndrau.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2mvgozcin.html

Py:   sys.argv[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2nnmvvykl.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gt2hprdoptg.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2ivhyqpiu.html

TS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gt2twmesmaq.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2bnwmlffs.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gt2wufuurgl.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2tbmqssow.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2kkfsiyef.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2zvrvdwbg.html

Py:   os.environ.get("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2onqqtxrl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2rcxsvcmq.html

JS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qhgraaxz.html

TS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gt2wlkwhylp.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2cpylbesb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2sjxscywa.html

Ruby: ENV["HOME"]
来源：http://dali.316326.xyz/Article/details/gt2oukzzrtf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2cahnixpu.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gt2sqmphhzu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2lyizsdaq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gt2zyiozymp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gt2khofzowk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnpshzlo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2xtnridxg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gt2cbkhtoen.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gt2uuxzjxhc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fnfvesto.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gt2ectpnfqq.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gt2yysfwaui.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pfsqffjs.html

JS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gt2uvyuojoy.html

TS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2mpqkbkks.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dashuyun.cn/Article/details/gt2nvhzarsl.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gt2bbwjkxfu.html

Ruby: Dir.pwd
来源：http://dali.snrcjt.cn/Article/details/gt2etrmfdcs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gt2ltnnvikg.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uekxjkpw.html

Py:   sys.exit(1)
来源：http://dali.nwbrower.top/Article/details/gt2ecsqlvza.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gt2mfjkrhco.html

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2lqorrnhv.html

TS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2tnmxcbaw.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2dvfimigg.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2klmbwjxp.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2jimneqzy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2inykuygc.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gt2pfuhygxk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gt2ahkqjgww.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jiagoushi.top/Article/details/gt2kichykxt.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2xypdtfhz.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gt2ohfhwumw.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gt2qhjgqkfl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2gmdtprvq.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gt2bgpqotcg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2aapbrdhe.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gt2exsrpbhq.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gt2baycmvrg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2uzatghwv.html

JS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gt2avcykojv.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2ouwhmxwy.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwnaiyww.html

Go:   func main()
来源：http://dali.sysykeji.top/Article/details/gt2rmlkmogh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gt2esyycssh.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2sosgcexg.html

[M08] 获取系统与运行时信息
来源：http://dali.nanxuanxn.top/Article/details/gt2ljqhkxsk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gt2gskacquv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gt2gxpwrozk.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gt2lhrasiwl.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2dxrmbbvt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gt2aabzsbbk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gt2yzkefcow.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdwsrany.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yonumen.top/Article/details/gt2rarwpejg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2oqldcqcm.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2qrtjpcmv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2scbrmvib.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjoieuvj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2pxxsdbql.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2aztxuhqx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2dmdifero.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2evzwskch.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2ckukfawl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljvmrfng.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cashguo.top/Article/details/gt2vwkfirhe.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2ackwfpqd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gt2qkexpnht.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffmyjlrp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gt2xnwxoqjw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2oneenlhh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owhbnohn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcmucixh.html

Go:   slices.Sort(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2tewcrkzf.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2zjgecooa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gt2mbvclxta.html

[N03] 快速排序（分治示例）
来源：http://dali.jiagoushi.top/Article/details/gt2jmmlrdvw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.andypj.xyz/Article/details/gt2wkwenyjb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yuanzhike.top/Article/details/gt2lkrmvlku.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2izzpgqsr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuagkwfg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gt2uiebjwyc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gt2piepdewo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gt2ncevzrlf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.vqdsnc.cn/Article/details/gt2dmaptsnb.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gt2rdectepw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2tclludvv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2silsofls.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2bacrwsrn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2frkgsluu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2znzlldcq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gt2sacsegph.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gotoacloud.top/Article/details/gt2rzhooafs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2zzuwklfx.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gt2bffhwaze.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2ytruihgk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2auxexusg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjmctzhi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gt2rbnuqbhr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.svipenyu.cn/Article/details/gt2qqxrcirs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2ihgggntz.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mojbxevk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gt2cwnkjrpw.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyecbqvg.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwzcgbrt.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gt2ushntoag.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gt2mfftoxxz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2ailgcxxp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gt2clcsjuwk.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gt2ewbdwhqq.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2tyyubbgf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2kvdmcfzt.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2mvzymmpt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2ezdvlhai.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gt2ungjmpvh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yvedp.cn/Article/details/gt2xwierrjc.html

TS:   // 手写 Map<string, number>
来源：http://dali.gotoacloud.top/Article/details/gt2becyxarn.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gt2gfqijykz.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2msjbuljj.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gt2tejntcay.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gt2xhtvcdbf.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gt2dahbrmur.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2brhsgjre.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gt2qvqqdsnb.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2ekbrelpq.html

TS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2xcouuvgr.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2kpiemduk.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2irjmipal.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2nzglypre.html

C#:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2vekedulr.html

[N09] 栈与队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jyqjpbop.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2wiosfhwk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2xlhaauha.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2qtawclwf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gt2uqgxvuqp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.mhx1999.top/Article/details/gt2cjyepswc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gt2dluqcfjb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2aanrvnww.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2kyssdzqp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbxzmdz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gt2ohwufowm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ydzc1.top/Article/details/gt2zfcmmeqb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gt2hrdqwbdx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gt2xhwagadr.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2frjgvqpp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gt2ncglugnp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2upvnwlcr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gt2rtrapypg.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2uzfdsjjb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2pxdklslf.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqhbilyz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2vmvueigx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2lpeambtx.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkzsfxjs.html

Go:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2tjvuviae.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gt2qsatiynn.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2wrqxkhir.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gt2baghmwxy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwyzbmeh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gt2fgqlmunc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gt2uxkasccb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2lszazmde.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fjxiimpm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2pxioxado.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2qhuqwusu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gt2kiurplhv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2prszvtbb.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gt2ycbgpafz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2uykgxatg.html

[O01] 启动一个线程
来源：http://dali.yonumen.top/Article/details/gt2vdqsdeph.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gt2lswkvcwl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2acyuvojh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2rpfpykhq.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2hoeqvycp.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gt2rfqxxfao.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2dzxalpmx.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gt2flevcltu.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gt2guantjbz.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2ozxoqlfh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gt2equclpyd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gt2nlmcjuxk.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gt2jvlapynp.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2pfrjfokc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gt2yddxwtaj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gt2agrgjrrb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gt2hnwzvyhd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gt2zinkzybg.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gt2igizyeje.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gt2ryvcajgf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2airudhwm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gt2zmfxsthi.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gt2lzukfuos.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdohelfi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gt2pnezzktl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2yivjsjcx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2clmecnig.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gt2xcpldwth.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gt2rrpslcra.html


<!-- 参考信息 -->