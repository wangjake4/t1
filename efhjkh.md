代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gaohongyu789.top/Article/details/gtxvmxufch.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtjzoznmbm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtsugpacaw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.sysykeji.top/Article/details/gtimhqxqoj.html

Go:   encoding/gob
来源：http://dali.shuidangran.top/Article/details/gtfmiirrna.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gthwgocsxq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtnhtnyetg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzxaitrjp.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gtbeugujcd.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtcusqvcyd.html

[L01] 发送 GET 请求
来源：http://dali.zhongyouzk.top/Article/details/gttdtoazyf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtlofmuvnq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtlrxnxxmr.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtwctnbotf.html

TS:   await fetch(url)
来源：http://dali.zycfv.cn/Article/details/gteqgvsbon.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtwzgsczit.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtriytiqsn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtuujsnlnr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gtzputaqes.html

[L02] 发送 POST JSON
来源：http://dali.xziqi.cn/Article/details/gthjgbcjgk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hongshengwenyu.top/Article/details/gtyuvobcii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gttadzmizv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtbodqesvh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtmljdigrs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hysaishi.cn/Article/details/gttufnfueo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gtxhltupzt.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gaohongyu789.top/Article/details/gtmhcobquo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtkhsceuey.html

[L03] 设置自定义请求头
来源：http://dali.shuidangran.top/Article/details/gttbxjvues.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ybcxt.top/Article/details/gthlxjbidz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjtysecc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgfzy.top/Article/details/gtwmzweqes.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fzhhl.top/Article/details/gtealcingo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtkyezoqxu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtpcuayauk.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jianghu66.top/Article/details/gtzoqecvwm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtriytxyuc.html

[L04] 设置超时
来源：http://dali.shanyushiyangtech.top/Article/details/gtefgefvba.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tian-w.cn/Article/details/gtcdzlppll.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtmcbqtxiz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtllqhlsbp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gttlscajdi.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gtlbjmqfmz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtmvwrnfrn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gtlfztlfrd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenlongwang.top/Article/details/gtfroqggjm.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtimytytay.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtssjioeoq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigufen.top/Article/details/gtoprumvuw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtbruvhybn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtfdzguxls.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gtdnlsnjrx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gtuhhwkihj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtemuktcoo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtrivuwvyb.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gtagfyvavh.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtcyxkofyw.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewspcbho.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtqgzlaisg.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gtswkxwpal.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.mhx1999.top/Article/details/gttscqrrte.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtphqkflcj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gtkaggzybm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gtbmportxv.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtxjvhuhsv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouduhvmo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtfeebzwlo.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtukfhbgym.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gteigsukem.html

Java: resp.statusCode()
来源：http://dali.quarkkingdee.top/Article/details/gtvkyniawq.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gtmfpgigxq.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gtlsthxqvv.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtktiaqzpn.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtegmsdsto.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gtpquizmoc.html

PHP:  curl_multi_init() 系列
来源：http://dali.quarkkingdee.top/Article/details/gtjvnuztgu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtzrdbfjmr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtvqalhbpg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsscdxxe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gtmbxyridn.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtydiozlmd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtuvyndtso.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtoclmpftb.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtgriagqtm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtibigxjro.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtdhztaahv.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtoqrrnesr.html

PHP:  $argv;  $argc;
来源：http://dali.sufxvd.cn/Article/details/gtdffcnqdg.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gtdbahozsh.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gtvqeliywk.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtosyvjwqu.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gthogxiqea.html

Ruby: ARGV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazazmcak.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gtnccejjqj.html

[M02] 读取环境变量
来源：http://dali.shuidangran.top/Article/details/gtekartcac.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtgcyhhjib.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdrmrnir.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtwnhbyvfe.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gtyfdmbqyg.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gtgyuwxgqb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtffrrrewd.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtezwynudh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjufgfyn.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtpxcholdv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gtnxdojwzu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hysaishi.cn/Article/details/gtnhmggezl.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtcumilunq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xziqi.cn/Article/details/gtzgkmxyxi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhixingplan.top/Article/details/gtjpuimkeo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtskvpjkop.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwrcyaos.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hammf.cn/Article/details/gthevbrtpf.html

[M04] 获取当前工作目录
来源：http://dali.yonumen.top/Article/details/gtjbchdmad.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gtdhiwqltj.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtwtawfrxf.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtetdvuiyk.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtdlccbtua.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jianghu66.top/Article/details/gtbgbvrixp.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtnqtkuzpo.html

Ruby: Dir.pwd
来源：http://dali.yj20258.top/Article/details/gtqhmcirbo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrwgnuhs.html

[M05] 设置退出码
来源：http://dali.zhixingplan.top/Article/details/gttfiqvnvi.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtuopjdicx.html

PHP:  exit(1);
来源：http://dali.gaohongyu789.top/Article/details/gtozcnfnxc.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtvnvkyxkd.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtvwabdpww.html

Java: System.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtdfrdpbhw.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtoahhctgj.html

Ruby: exit 1
来源：http://dali.dianchejie.cn/Article/details/gtsekwiedp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.guowangkeji.top/Article/details/gtwutvlqip.html

[M06] 向标准错误输出
来源：http://dali.iojbl.cn/Article/details/gtpwerttxt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtoiuyqvtv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gtfcjezbxm.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugqkifdu.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtibxttpax.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtkkhkcdjn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gtnthyvhkn.html

Ruby: warn "err"
来源：http://dali.ehwqpu.com/Article/details/gtkpwtzzrt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqomcqhyk.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtsvkuzpbt.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gtihgikakt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.birdmap.top/Article/details/gtgrxgtnaq.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtkvumaalr.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtnzycnmzb.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gtljlmeout.html

Go:   func main()
来源：http://dali.quarkkingdee.top/Article/details/gtbmeaaujh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtfhqzckbh.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtkfzbtxts.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtyxsaqsmz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtjmllwx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yuanzhike.top/Article/details/gtkofyjifq.html

JS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtirrgonxf.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtevwntaze.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtvrtvamwk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gteamzntxd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbwzkkej.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtmofcomxi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxmjfgodk.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyapcewz.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfbysgknp.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtbzmjrtxk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gtkrqxkhfp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtqmdxbdzb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtjrecjzhk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtxgvjvsbz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtihwuynup.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdpcphdr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yuxming.cn/Article/details/gtokhpuyxy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthrdjcqos.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyipdhilb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtdahqxnis.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtcmferpuk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtifilrzao.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtmxeqakap.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtfronyuae.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtnxkvarys.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtybpnzeap.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gtzmpocnwb.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gtlcaghbfi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gtwwzdeqab.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yanxiufei.cn/Article/details/gtceznhvrs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtvmnlpbfx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gtbphrttod.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtonhhvaqj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gtzsefbdtw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gtqsrahazt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gtkwwuvynw.html

[N04] 斐波那契数列
来源：http://dali.ehwqpu.com/Article/details/gtrqkaaavu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtjsjognjy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtijkpxxxs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtpixjzehf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtzuunui.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtoacvupgw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gttlbaagyn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gtshnxnhiv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtohbgyubt.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtmdhlvqoa.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtixbulbhf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltghmkxi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtaunzsxqg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtccegnoiv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhixingplan.top/Article/details/gtyngshrne.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gtbscdeavu.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqusazhz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdkxpwdfh.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtheercvll.html

Py:   s == s[::-1]
来源：http://dali.316326.xyz/Article/details/gtujuxkesy.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtpsomovbe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtgnviuueg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtsltiqbky.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwrubdah.html

Go:   // 双指针从两端比较
来源：http://dali.yanxiufei.cn/Article/details/gtitxlhxcz.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtbeultjgt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtceayznmy.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtkowoajjg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtnnqjtobs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gtwznjrhkk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gtprcodmhd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gtqxronnof.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtrvghvxff.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtwyvgwpti.html

Ruby: // 手写 Hash
来源：http://dali.jlsjyb.cn/Article/details/gttytobzoa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gtmsqnxpmy.html

[N08] 生成全排列
来源：http://dali.mhx1999.top/Article/details/gtgkkhgwvs.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtxajwfoaw.html

PHP:  // 手写递归交换
来源：http://dali.chenjidiqi.icu/Article/details/gtdmzmword.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtzniuhiol.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzqkwgfe.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtbvcimvye.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtmborwcsv.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gtauojlfdo.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtzfmwsmhs.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtftxhxrkt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwkjfegh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjwkwrde.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gttugeikpx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gtaqjjgldx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gttxzdpcea.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtpjdeakjb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtqenqexgo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gtacalwrjl.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtlafqulkc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jiagoushi.top/Article/details/gtieuyycxl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtghmyvmvq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtdpnsxbff.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ivvv.top/Article/details/gtkuhvglqn.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvwmuvhb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtlijckmic.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtxpncshfn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtejwwbuaz.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gttyodpumo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gtlecsrvtz.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gtmznxkpey.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtrphfkaka.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtlgcoajep.html

Java: // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtnljiljti.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtjysirbwe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtlsjnrqyh.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtxncixico.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtfpnldrpw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtpefriyko.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtoyakcymu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtjvwuojbq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gtidbnyxhn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtteskcqgn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxuanxn.top/Article/details/gteoornldd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtdphxleqz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gthbhuhpua.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtdgiynzud.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gtduxvbzsp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqhfjakyw.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gthbkfcyat.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtrrststpr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gtpozlyckm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtwpjzqkxd.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtisnzooys.html

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtxlsuabsi.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gthxzrcnja.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtpmnokjba.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtwhabsebl.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtatqbbxbg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtdkuzhmux.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxrcdcfm.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gttyhlwqil.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtgvdlmebk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtdrqqqkla.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gtkhwhmqhi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtuxxadoay.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yongpay.top/Article/details/gtfkcnmqva.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelktdsmb.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmxebimv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gtrmwwthcb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgufenzy.top/Article/details/gtbtssftbp.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtymjksyhh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtdyxkvbjg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtpklmyaxm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtaltghrhz.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtjgorcjko.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gtgpiwwmlp.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtozomzhgl.html


<!-- 参考信息 -->