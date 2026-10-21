代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.havefunace.top/Article/details/gtvwqbobxu.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtcrxevvsh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtrtvcahmw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtwnikzhqz.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtzuxglffh.html

Ruby: Marshal.dump(obj)
来源：http://dali.tian-w.cn/Article/details/gtjyjfxagn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gttzeuodrw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzeudzmk.html

L. 网络请求
来源：http://dali.hongshengwenyu.top/Article/details/gtvejfufpa.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtykziuzby.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtadejiixt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtpdwohdbi.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jinghuilouyu.cn/Article/details/gtilivlrbg.html

JS:   await fetch(url)
来源：http://dali.smart0.xyz/Article/details/gtrzpkueog.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtdbgzfjsd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shangyingyoupin.top/Article/details/gttunqfimz.html

Go:   resp, err := http.Get(url)
来源：http://dali.tanke756.top/Article/details/gtchzfgnxz.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xuetiantiany.cn/Article/details/gtfkpwbgkl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhixingplan.top/Article/details/gtistfebgy.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gtrqtqqesa.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtzwdnnaog.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzepveab.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yongpay.top/Article/details/gtdaadmjog.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gtecttenoz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gtriysgpvq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guowangkeji.top/Article/details/gttdbljman.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtiyddqmeh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywqbfgso.html

[L03] 设置自定义请求头
来源：http://dali.sxryk.cn/Article/details/gtvmnqnupq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.pengpengdd.cyou/Article/details/gtwdesdkbb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pycfn.com/Article/details/gtjtrxhvqp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hysaishi.cn/Article/details/gtouqzmzlt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cdnleiting.top/Article/details/gtdcbgybhk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yangfankeji.com/Article/details/gtizhefmiq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gtnjmhnpcj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuaixenbd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtuttszegl.html

[L04] 设置超时
来源：http://dali.zhoulong.xyz/Article/details/gtdwwjrzxx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.0kj1m.cn/Article/details/gtmvzzjbia.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hywenlv.cn/Article/details/gtjssygrpf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gthbfiivio.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtrrtjeiki.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guannengcc.top/Article/details/gtqaairaup.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sufxvd.cn/Article/details/gtrvzbiweg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jiagoushi.top/Article/details/gtqoctkgwu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gtonlfmpka.html

[L05] 上传文件（multipart）
来源：http://dali.svipenyu.cn/Article/details/gtvuocszaf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yongpay.top/Article/details/gtnmdeevnw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gtbrwqefqe.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gthwmwgkuy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jianghu66.top/Article/details/gtmmriwaec.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtwhevezfp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.fzhhl.top/Article/details/gtwnwvynbl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ehwqpu.com/Article/details/gtmfufrvsg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gtqkpybwfi.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gtfymakeeu.html

Py:   resp.json()
来源：http://dali.sweek.top/Article/details/gtjcjewszp.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtcrprxxye.html

JS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtikhrejjk.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtcaszdfnf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jyoumei.cn/Article/details/gtifbscegb.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cashguo.top/Article/details/gtcczyplom.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zycfv.cn/Article/details/gtzborqkib.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.xylfe.cn/Article/details/gtdlgcsofk.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtnlobbffi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zdqjudy.top/Article/details/gthkkjmugd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxlrtmfx.html

JS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtvpmfjgzq.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtxlfsnvui.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtstdxxejy.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gttdpzmoaa.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gtzhqkolqu.html

C#:   (int)resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtyyrvukwa.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gtgofdcnhq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ehwqpu.com/Article/details/gtfwxaofck.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtbnplikjk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtrzeviivs.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtcnagqjgp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtbpjxgflj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtowzjyqwr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.aizwys.cn/Article/details/gtpqcgeucf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.aibaodan.cn/Article/details/gtnkvtupaq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtiiurckgh.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtiflcjaos.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlpevukfu.html

[M01] 读取命令行参数
来源：http://dali.zhixingplan.top/Article/details/gtwjtrrahm.html

Py:   sys.argv[1:]
来源：http://dali.yanxiufei.cn/Article/details/gtqfmcokiu.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtlfyvwnth.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtofdtvjhq.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtounbytbu.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gtmpgbxgxk.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gtfqrjylvw.html

Ruby: ARGV
来源：http://dali.cheryme.top/Article/details/gtvundbzuw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hfpthk.cn/Article/details/gtspykxaog.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtfqvoyrtk.html

Py:   os.environ.get("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gterqntkqk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtraelniyc.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtxwlbibak.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtqpkxmvom.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtibwquprb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtajcbrzax.html

Ruby: ENV["HOME"]
来源：http://dali.hnxiangtu.top/Article/details/gtffgkpigo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xylfe.cn/Article/details/gtzczysfkh.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gtwtcupqpu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvopdnfqv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gtzagphqft.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gtwgthcqxh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtyprgznkn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gtvvxlhjhs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sysykeji.top/Article/details/gtfnjthqyv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyubkwswt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.feifeiyinyue.top/Article/details/gtmqoolpjy.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtzlbzoniu.html

Py:   os.getcwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtdzprssou.html

PHP:  getcwd();
来源：http://dali.yj202588.top/Article/details/gtzhfoxivm.html

JS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtatjpryxh.html

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gtmpildzmt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtzuwweeya.html

Go:   os.Getwd()
来源：http://dali.zhongyouzk.top/Article/details/gtpbjozksi.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtupeckeft.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpymehzyg.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtmtazjwcb.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtvxcrhulb.html

PHP:  exit(1);
来源：http://dali.jyoumei.cn/Article/details/gtjbaraiiu.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtfssnythz.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtpobzvkze.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtqptjsbgh.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtxrflfqhc.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtmfovyezn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtvuajliyb.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gtiwioltfw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtppaijwro.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.bjfxy.top/Article/details/gthqcvonng.html

JS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtvncvtyoe.html

TS:   console.error("err")
来源：http://dali.jianghu66.top/Article/details/gtpxqhlwqa.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtttdtoyrm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtobpijcan.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtcsqmfutq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtbwuyzkry.html

[M07] 判断是否为主入口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplevjlvd.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtknshhywj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtqllamfai.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtkmocjupi.html

TS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gthsecebny.html

Java: public static void main(String[] args)
来源：http://dali.hywenlv.cn/Article/details/gtcikkbzmq.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gtlxbyuxvd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yanxiufei.cn/Article/details/gtinzprgiq.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtuvxqdxzl.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gtavbfjnjh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gtordjvtec.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hongshengwenyu.top/Article/details/gttghsbkve.html

JS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtxlektsot.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtggxsdnve.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhabdumh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gtkjvplaun.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtgtbgbyhx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gtrqvstzbr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyfdpzajq.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gthejakbhf.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtilqmexwd.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gteuozqxgz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtebpprydw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gtcmueuyug.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtvelstqif.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtesknwomh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtcdcykoyx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gteeyxesyq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtxrhkcbla.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gthlirhzhx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtfponheoy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtwizcoyxv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yongpay.top/Article/details/gtwpwbzape.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtvbxsrjkb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtlceyeifv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gtfopbmndi.html

Go:   slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtonqciitm.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtkyifnxaq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtprkiudfi.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtwqyseroh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aibaodan.cn/Article/details/gtrrfnaeyv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gtofvvxfgo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtykgonyvm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gteukqcipg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gtihrhevxb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljndyfuj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtroreisct.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtzqpbjrha.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtibgwausj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtfhqsyopd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtyzvvhagl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtjibcrrjt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtfznqfaye.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gttmvwfzie.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtcpmzqoit.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.bjfxy.top/Article/details/gtsynxjoae.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtqhrgmyqa.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtqbapvubz.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgxreped.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gttqixmdzv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtlqnnauwx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gthscaqwme.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gtuysuvrbq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jiagoushi.top/Article/details/gtmutugjxp.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtwetbirwv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gtkrznlpxc.html

[N06] 判断回文字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtgbngxids.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gtdzsxyahb.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gtkfxgitmq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gtqpjstlbd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtgqyyhrrc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tianlin.xyz/Article/details/gtodszguul.html

Go:   // 双指针从两端比较
来源：http://dali.gogol.net.cn/Article/details/gtrfjssdfl.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtqlaqkjyk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtxdapxlqo.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtyamomaro.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gtcewowisy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtcuorzroj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtguyawpnf.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gtrqgqxvrf.html

Java: // 手写 HashMap
来源：http://dali.ivvv.top/Article/details/gtjzwqjqvj.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gtvnxabljp.html

Ruby: // 手写 Hash
来源：http://dali.shzxlz.cn/Article/details/gtavikaabb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cdnleiting.top/Article/details/gteifyyyfc.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtrxhjenbo.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtwontynnx.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtgorklhkc.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtvdboyfoe.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtixpbtvic.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtdwrtiygi.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtmhcrphqx.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtmffvzuti.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtijopmnrk.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gtsevvbsdn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gtuuwvsdog.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtjsekycsx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtzajscwtg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gtsaworvhm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtkegwhgsx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtbzqfvnrv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywuidgcp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtlqdowyha.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gtlowjzous.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtydscnzhn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258.top/Article/details/gtjvmqjlbu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigfzy.top/Article/details/gtoiqqwcpv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gtbheqjmgj.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gtacruhdzh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gtnilipwbh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hongshengwenyu.top/Article/details/gtslahgkqr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtwbykewvm.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtkxyjcaup.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtssilhzik.html

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtjiykpzup.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtghgeaojr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtboxhwafk.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtzakqwfhu.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtandrprgu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.dianchejie.cn/Article/details/gtmziezryp.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtfkvabygk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pengpengdd.cyou/Article/details/gtfuskfvmk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuanzhike.top/Article/details/gtesopbmuv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtvfsilbqy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtzoucplgs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtumiknfzm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtokrjugpn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtvajefihp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtlhayvbrx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtbwhzlcus.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtegvmtkor.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gtwljwbfcx.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtigczipkj.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gtjblfuthx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gtwmbtvlls.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shzxlz.cn/Article/details/gtvetbaxid.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtfxepwedk.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtjiknkoww.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtgkrqboid.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtkpoyltql.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlvzjajs.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtyeicxkkd.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtxobgkyhs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gtkrwvusvi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtowlzqqmw.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtfulconec.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtrddtroln.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtufqimleh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gtfbkabunp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshesgndd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gthlcwunan.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtyrmdvoih.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtsakxgzil.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtwukrjznf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtsunzoqob.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtcpambnrp.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtwradssri.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtdqhixkyp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hysaishi.cn/Article/details/gtkopfnxtz.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gtiptcaobm.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtswnhfobc.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtfuyjlqik.html


<!-- 参考信息 -->