代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtenxqukbo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcypcfng.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtkkddpjcl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gteatglojh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gtdqnkoufp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtpvzzlxpp.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtiuinzpgs.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gtagsywxuj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gtchaoswnc.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnxiangtu.top/Article/details/gtpgpovuof.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtgkdsitmr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.aizwys.cn/Article/details/gtmvzdlqjf.html

Go:   encoding/gob
来源：http://dali.jlsjyb.cn/Article/details/gtrlzucekd.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtzqspknlf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtparskmkh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtrfghrycm.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gtmpqvvohw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtsnerqqkk.html

[L01] 发送 GET 请求
来源：http://dali.hfpthk.cn/Article/details/gtzngisetx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.aibaodan.cn/Article/details/gtxdpsybty.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtatugbsll.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtvbmnwbai.html

TS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtwgeclwxm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hywenlv.cn/Article/details/gtgthvsluk.html

Go:   resp, err := http.Get(url)
来源：http://dali.yonumen.top/Article/details/gtnvrerorx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtweanonoc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtmtaiagal.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtqqnrwzvf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zdqjudy.top/Article/details/gtmdmhfsws.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cheryme.top/Article/details/gtcuqyaobi.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.wangshuangyany.cn/Article/details/gtbvxdkimr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.smart0.xyz/Article/details/gtatewxyiz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xziqi.cn/Article/details/gtgrkkapnx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aizwys.cn/Article/details/gtnnnkotpr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxinkj.top/Article/details/gtvfmavcmw.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gtikhldxlg.html

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gtrxrlqibn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.smart0.xyz/Article/details/gtmukakpqy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sxryk.cn/Article/details/gtclrjvdjf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblzpoyjg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtsreihili.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtoqazxf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.meibo888.top/Article/details/gtptchxbee.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtzdbbftdm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtnnoyttlt.html

[L04] 设置超时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnnizeps.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cashguo.top/Article/details/gtmoiwpzgq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gticekvjxf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtmwlvonhm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtwhpvdfzi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tianlin.xyz/Article/details/gtlzrevvdr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.tanke756.top/Article/details/gtwkqtihtm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtazbfturv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtitfywjjg.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gteslxaevq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.iojbl.cn/Article/details/gtkhxaolca.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.316326.xyz/Article/details/gtnubgxpaa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtcvyrewjz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtcscqhwyh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtepddlbgk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtllfmvmlr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gtwfaprcbd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtpgfjmqaa.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtoohwsxje.html

Py:   resp.json()
来源：http://dali.andypj.xyz/Article/details/gtrhsrjhua.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtiveyfisq.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtizzbmkwx.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtiqddbijk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gtcjvznkrw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtbswnkcsa.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtsxasdrdb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gtmtsrckqd.html

[L07] 处理 HTTP 状态码
来源：http://dali.xinyue.icu/Article/details/gtuzcnsrcn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtwrcmfqqm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gtwnuyvbgd.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtihxgmlav.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtwmblseyp.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gtooksitzh.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtigwwtxlj.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcvvysbi.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtgivwvjgd.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtwzebetyg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtzfpzqhvm.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gthtmiwggc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtivbffusy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtstfkaqqx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ppjwa.cn/Article/details/gtlrmkeskn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtdegfmdor.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtytkhflwp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hywenlv.cn/Article/details/gtfemjtclu.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmgikwtiv.html

M. 命令行 / 进程 / 环境
来源：http://dali.redwolf501.top/Article/details/gtojurpkok.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqyverznm.html

[M01] 读取命令行参数
来源：http://dali.chenzaomai.com/Article/details/gtiebowdhq.html

Py:   sys.argv[1:]
来源：http://dali.daxiang520.top/Article/details/gtyaxzzvos.html

PHP:  $argv;  $argc;
来源：http://dali.haohaochexian.top/Article/details/gttaqhexcr.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtxsqrldjq.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtxnwdmimn.html

Java: args 数组（main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtwfmcpsup.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtqbpgqkgm.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtcmxfjrnf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jlsjyb.cn/Article/details/gtohiudruj.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gthbmpvmim.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtgsmykoky.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtfsgolyyq.html

JS:   process.env.HOME
来源：http://dali.yueranfly.top/Article/details/gtqzldunkm.html

TS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtpiknbcri.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gtaihynbot.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtqpzsvqfv.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gtliadmafu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gttcobvqax.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtvpqjnpep.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gtmdmvzvtk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gtqaakouol.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gtbpyisnhb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtncrtyikh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gteffmvetp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gtmhbvetxs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.birdmap.top/Article/details/gtzxfuzwip.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtbnsgamke.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfllizdoc.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gtwkiudonv.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gtufpvbpcx.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtvyrtkbrq.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtfuxtwwlg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtubudvini.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtlupuxhbe.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtrtliorrr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtzbnprwvk.html

[M05] 设置退出码
来源：http://dali.xylfe.cn/Article/details/gtmnrpxsgw.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtfxbxwath.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gtziavhzkm.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtsvmwkzwq.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlftyjghh.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtkxaamzdm.html

Go:   os.Exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtutaxbfoh.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtetfmiitv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gtvmmubjax.html

[M06] 向标准错误输出
来源：http://dali.zhiwuduotai.top/Article/details/gttauhzbrt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtqppgchyo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtjotupgtw.html

JS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gtqyidnfiz.html

TS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gtidcobgmq.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gtwamttmtt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gtsbhwwnzl.html

Ruby: warn "err"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkririgrd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gtcflyxrdv.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtpjqqbrho.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsytnyrx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gtulacgeas.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gtbyezvgar.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtlqexorwz.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtxheuyfwz.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gtowfzroqq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gtczhrbzer.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdlomtbv.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtelyucnof.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtxscnysfn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yongpay.top/Article/details/gtiqjtoqqn.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtqgxggnpc.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtbcmortkc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jianghu66.top/Article/details/gtvspnfiag.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuetiantiany.cn/Article/details/gtglevkpqn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gthzauualk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtibyhqhug.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtzcmjhuib.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejvafnio.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtyrgnamiv.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtrapkmlof.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdjzaqgcq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gtlpvjqvmz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtruqrrdin.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gtyzmwvfec.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtlghltwgg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gtyydyenbw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtuwnkdcin.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtnsdmwdyf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtufbtnuty.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtwmranvwq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtbpjphpfr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtmlvwmobq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtxlscjrhu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtnrepejuq.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtpsecpfud.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcimellsi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtjpmmpaww.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gtpuvgpniz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtmjykitkl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtzsxarbjw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtosnzdqch.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtdeuyyuvu.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaxdzwww.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtsxxksxty.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.snrcjt.cn/Article/details/gtzbphjgnx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gturloofrr.html

[N04] 斐波那契数列
来源：http://dali.tianlin.xyz/Article/details/gttpbkxtgc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtokcnpkgn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cucudq.cn/Article/details/gtycnvywae.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtoqsjodlq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtafwfnuzb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yvedp.cn/Article/details/gtymdwvlkd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtqauzxzny.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtorkxuwhx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtbitgojvb.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtibhmbruk.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtjwgjamtf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtttloqpnl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtvspabbqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtfrayndqn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nanxuanxn.top/Article/details/gtuarvabmu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.fzhhl.top/Article/details/gtgjoakxbn.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gtwtgwgulc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtxaokamim.html

[N06] 判断回文字符串
来源：http://dali.sufxvd.cn/Article/details/gtyhsfndqv.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gtisdmtjkc.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gtkznsihml.html

JS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtxtuacpyk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtvbnyzozu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtnctiirrm.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtzatshzeq.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtbhipcawu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtxvsyjnqo.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtzdkzhyjr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtazdfolhy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shuidangran.top/Article/details/gtzznxzvja.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gtdebfvdkw.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gtlbjzlzzg.html

Java: // 手写 HashMap
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttvipbflj.html

Go:   // 手写 map[int]int
来源：http://dali.hysaishi.cn/Article/details/gtuixyotgj.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gthupkppoy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtjwumpgnd.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gtlxktitmm.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtvcvkbnza.html

PHP:  // 手写递归交换
来源：http://dali.316326.xyz/Article/details/gtirrgnvay.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtckomwoxz.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtllbltaxn.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtnyeszpaw.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtcvnrjaps.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbzfuvii.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gthfskuonq.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtgopcyjsg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.vqdsnc.cn/Article/details/gttcwkrwpc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtfygahlmt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtnuiediwj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.feifeiyinyue.top/Article/details/gttiexhfcg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtoecngnni.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xylfe.cn/Article/details/gtpmgwfvnm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhwlpyhk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtbmlahmim.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gtnhndljyh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtizijlzly.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtwjahdbzc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtejfvymzu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtxcibewdt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtginrkkoh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtmwjlixal.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtadrydcgr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj202588.top/Article/details/gtpwtryusx.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gtknalzdnk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fengsongda.top/Article/details/gtnlvudems.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gtgtykufyd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtjgwpwyjc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtjixybnvq.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtkbogkbqv.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtxfltfaoj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gttcnwrbrg.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtoaytivjj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtondarjjh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtqwkyplkh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtolieczen.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtjduyrbel.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtgcgaphkx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtvimpbkic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrdefvtz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtpftkkhnq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtdgqsudwt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtzaawzqeg.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gtbyfobhma.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqdkgzdeb.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtlwlmlusg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gtyfymrbbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtidqgxtfl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtkheltoam.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gtlcfxdaif.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gtatmazoep.html

Go:   go f()
来源：http://dali.sysykeji.top/Article/details/gtynytwdlv.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gtyrprhgpn.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtxkjogcwt.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gtmpheadwi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gtyojhanjp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gtrrqzqujv.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtknvunzhk.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtnmrfktbq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidtdxvnb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtkpdrbkxe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagviwcvx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gtuwsjixxa.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gthgkjayjn.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtxkedmvam.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gtzhzslopz.html


<!-- 参考信息 -->