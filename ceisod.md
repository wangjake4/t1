代发 wailian999

L. 网络请求
来源：http://dali.jqgfzy.top/Article/details/gtixwswxxi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtelgtuwqf.html

[L01] 发送 GET 请求
来源：http://dali.quarkkingdee.top/Article/details/gtoxrhidlz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.nanxuanxn.top/Article/details/gtttoaxsdq.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtgghhjrww.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtuveuhbtt.html

TS:   await fetch(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtubwdexgm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtcmtofkcu.html

Go:   resp, err := http.Get(url)
来源：http://dali.mhx1999.top/Article/details/gtrxcfrmda.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gzhubu.top/Article/details/gtiqycxyhm.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtkbdprwtu.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gtgwwpvnnd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtveohbflv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gtaazifoam.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gthlewverp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtxeyhpyrq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcngajdlk.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.haohaochexian.top/Article/details/gtxggutevj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gogol.net.cn/Article/details/gtoyxqdyxx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtjzjluyln.html

[L03] 设置自定义请求头
来源：http://dali.snrcjt.cn/Article/details/gtortlbqrx.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gzhubu.top/Article/details/gtdyqtptwa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jiagoushi.top/Article/details/gtlqekadak.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtepzoivgs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtdqlnjhuk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtzthgovuf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtkpgxouoq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gthsbwsjwi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqiykfmx.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gttdhizxmm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtcvydahbh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.dianchejie.cn/Article/details/gtmnsmageh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gtmftxuaci.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gtbxbwifyd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hfpthk.cn/Article/details/gtteirbsxv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfweevyfu.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjnoaugi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.316326.xyz/Article/details/gtqxakfzyr.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gtfhegvrmi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtzjwwpujs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.svipenyu.cn/Article/details/gtdzkzyeyf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gtskqmixci.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozbzmpme.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gtpbckzlpb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hfpthk.cn/Article/details/gtjxivupxu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtxddjmulw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtrvplqmgx.html

[L06] 解析响应为 JSON
来源：http://dali.svipenyu.cn/Article/details/gtngisexzc.html

Py:   resp.json()
来源：http://dali.cheryme.top/Article/details/gthnxiipsp.html

PHP:  json_decode($body, true);
来源：http://dali.shuidangran.top/Article/details/gtjdwnojeo.html

JS:   await resp.json()
来源：http://dali.yanxiufei.cn/Article/details/gtqwptxtur.html

TS:   await resp.json()
来源：http://dali.mhx1999.top/Article/details/gtjjelmhfa.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gtprzqrvva.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtsaytgheo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtxtixybye.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yonumen.top/Article/details/gtwobshigy.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtwepbjytz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.nanxuanxn.top/Article/details/gtplpuhwbl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gtbafdkirr.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtzasigkxu.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtzwfoscou.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gttzejkfsf.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtlvxvvoxg.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gttetxwiuc.html

C#:   (int)resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtqewlplqe.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtfyonlcmz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hysaishi.cn/Article/details/gttqcarjnw.html

PHP:  curl_multi_init() 系列
来源：http://dali.hywenlv.cn/Article/details/gthkdwrgcc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsbmpmun.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtfxgvbnms.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtecfizkej.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xylfe.cn/Article/details/gtuvojsoix.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gtsuasmtve.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guannengcc.top/Article/details/gtulndwjgi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjcbfiriw.html

M. 命令行 / 进程 / 环境
来源：http://dali.ybcxt.top/Article/details/gttxesqoye.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtynqiaijs.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gtdoefjjln.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtxoumadqn.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtiodhomvy.html

JS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gtjkllclnz.html

TS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtpokoqixo.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtgqttfpnm.html

Go:   os.Args[1:]
来源：http://dali.birdmap.top/Article/details/gtzgggokvk.html

Ruby: ARGV
来源：http://dali.bjfxy.top/Article/details/gtpnakgdxl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gtptjygaeh.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtgbrduwlg.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtzdrjrdld.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ehwqpu.com/Article/details/gtmnsctzpp.html

JS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gttgenhtmv.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtfonyboiq.html

Java: System.getenv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtlbxyssga.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gtxtpbtrca.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gtjbwzmpcy.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gtphjnabrv.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtjkpxlvih.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.vqdsnc.cn/Article/details/gtsvhrndvk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gticwnppim.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gtefknydjf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenzaomai.com/Article/details/gtqcmksnop.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ivvv.top/Article/details/gtvktyfsfv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jiagoushi.top/Article/details/gtptzbnbmy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtudaapswd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.0kj1m.cn/Article/details/gtgmxmvahy.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtfpzcekme.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gtoeydnlgv.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtfsfoqxjc.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtwavenmvg.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtukwwsryo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hongshengwenyu.top/Article/details/gtyekrigvc.html

Go:   os.Getwd()
来源：http://dali.316326.xyz/Article/details/gtjkzyxhfx.html

Ruby: Dir.pwd
来源：http://dali.tanke756.top/Article/details/gtdqjtjohw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtyyzdoxuv.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiasgmxb.html

Py:   sys.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtvjbxznqb.html

PHP:  exit(1);
来源：http://dali.yj20258.top/Article/details/gtdioswldo.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqenzaxdl.html

TS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtcfoqooom.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtpniuvldy.html

Go:   os.Exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtijueiyzl.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gtxijivrvf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gtbsoduldv.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gtpztpcivt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtgtzjawxa.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tianlin.xyz/Article/details/gtreutmzok.html

JS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtpdppklrf.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gterqdavdd.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtlkajqozi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gttkjsknmm.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtosfkowll.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmxpskxn.html

[M07] 判断是否为主入口
来源：http://dali.daria6918.cn/Article/details/gtosijshaw.html

Py:   if __name__ == "__main__":
来源：http://dali.cheryme.top/Article/details/gtkvfjenik.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cdnleiting.top/Article/details/gtecmzhmyj.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtxotsugaz.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtxovbsdki.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gtttsczjbi.html

Go:   func main()
来源：http://dali.cdnleiting.top/Article/details/gtoyifyclv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtvorqtawt.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtpakfpidd.html

[M08] 获取系统与运行时信息
来源：http://dali.hammf.cn/Article/details/gtgdhoetqg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxihcoxi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gtwahwsxul.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gteckctufe.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gtwcyvymoh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gtkbdlcyzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gtgeigcquk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtwgfcdueo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gtqyqymtow.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtzrpzztqr.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtmkfxoefg.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtrbyckcxo.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gtyeqhaqob.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtblgnqdqm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtosfpnprl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtlcdicotp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtsqpsutob.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtooarript.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtfkdjojmj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtolxtkyfg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtpzlmbewy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gtgfupyqut.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtqzluaewl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aibaodan.cn/Article/details/gtresisxmr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtajofdmam.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtmpbqicer.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtqamwjipx.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtutzwfskd.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtbrvwgbyy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gtmfdwsdfu.html

[N03] 快速排序（分治示例）
来源：http://dali.havefunace.top/Article/details/gtnywpnlqd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gtyqrgodvc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cqqwz.cn/Article/details/gtdzigoxqw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtzisazmta.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtgeggzcto.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ydzc1.top/Article/details/gtovrwhfwf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtlxsdcpux.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtwcvzkftt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gtdpsgcocr.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtgusudrgv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtxedktsev.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtedqbaapz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtbxqeuxyd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtopprlzft.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gthmhwmgtw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtxlgjtyya.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gtlzbcuybi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtfvcajmcx.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtvkhtcsnw.html

Py:   math.gcd(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtxabkgxgk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gtmkjuskav.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmpxjyydu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gttbtwzkkw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gtmmidwqmp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtygfzpnhc.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gtqvvnbgji.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtchqnwvbd.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtbfpxphbq.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcfksous.html

PHP:  $s === strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gtdxcrqycl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtrzrhkpwo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtoqnnibub.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsoppchf.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtwpmpfsua.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtthnbpiqz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtaysldcaa.html

[N07] 两数之和（返回下标）
来源：http://dali.nwbrower.top/Article/details/gtlxzcnesm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtpzmivmwx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gtcbicwdry.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.redwolf501.top/Article/details/gtiqgfvdpo.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtsvirtlfp.html

Java: // 手写 HashMap
来源：http://dali.hfpthk.cn/Article/details/gtkqfmcvpm.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gteeemgbbt.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gthcalgnts.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gtcnrwrnrh.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtzbdtlkvm.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtldjajbav.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpyzeyzy.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtbcgoibow.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtsdrfbmki.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtcfwpjjpi.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtijyteuky.html

Ruby: arr.permutation.to_a
来源：http://dali.xylfe.cn/Article/details/gtpaybtfbb.html

C#:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxkafzua.html

[N09] 栈与队列
来源：http://dali.ydzc1.top/Article/details/gtqgivjssg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gtkelvdtkn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtmhtacyqo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtfazvzcex.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtofklvttz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtzokmjtem.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxuanxn.top/Article/details/gtzouqlfdo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gtedpuyqtu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtnrzzeztk.html

[N10] 链表节点定义
来源：http://dali.quarkkingdee.top/Article/details/gtdwmjqora.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxuanxn.top/Article/details/gtmgbiukhv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlcvgbnid.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gttepmndcp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gtniybarsi.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtnocoyxre.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gtmnhriifw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtrejcqecp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkoaqxfay.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gtocuqrnmw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtupbwptdi.html

PHP:  // 手写递归函数
来源：http://dali.kuanghao11.cn/Article/details/gtksbkvpdt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtnxcupucj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtfgareguj.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gtclsssaie.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbefzhqiu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtsavwnmqs.html

C#:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gthksjziwu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtalaafduj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cucudq.cn/Article/details/gtwdlueuln.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtecteikeb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtpqfjdbjy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtizuyftiz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtddrmvtqa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.0kj1m.cn/Article/details/gtnaplpcfy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gtflbiyqmx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtbcogvnvq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnitnubzp.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtfnwmvaum.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbdynxbvs.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtfoeirvyy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gteilitjdb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtecijyfdb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtxikfxvkf.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtbbfedbec.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gtfxuhdafo.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gttzkwhfmg.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gtcnyrojzm.html

C#:   Task.Run(() => F());
来源：http://dali.sweek.top/Article/details/gttktkwbky.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtjqplqeac.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtjnxfbzdl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtzzjmrlgb.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtlaorxuar.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtmgqqtbph.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtfiwpqklz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gtmrlgvgwa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gtdmocueii.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gtbytryzvi.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gtkbkhcdtd.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtvhxrthpz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtmwictifu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aibaodan.cn/Article/details/gtenxkhsgr.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtufexglgj.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtwzuozcgd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtzsdysobc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtqooybjvm.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtksdxcnsb.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gtcvpaqiic.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gteyilcqps.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtjkfxuzcr.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtxnkksewa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtsverkxcd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gtjcxvvxde.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gtncquvrtq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtiqxcldma.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtokuoanjr.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtebclvogz.html


<!-- 参考信息 -->