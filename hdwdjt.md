代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dashuyun.cn/Article/details/gtmetnqfxh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.dashuyun.cn/Article/details/gtloswiycz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtcuhaupta.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtrhqztznt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtoatnvbjq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tanke756.top/Article/details/gtmpdfrfft.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jianghu66.top/Article/details/gtpewplytb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtgceosppk.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gtziynsbwh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtuuagoyts.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.meibo888.top/Article/details/gtmoffhajf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtpmncoclz.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuxming.cn/Article/details/gtkternops.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gtosztrsvo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gttngefrmv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sufxvd.cn/Article/details/gtmhxascdg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtujzgopai.html

[L04] 设置超时
来源：http://dali.jlsjyb.cn/Article/details/gteiszlykv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtirywhatq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.daria6918.cn/Article/details/gtzivilxeo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gtxlvjjrmy.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtyprhrvid.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gttkonizbw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jlsjyb.cn/Article/details/gtzoafcise.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gteljivbhd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtgqzdgwst.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gtdxqpglvd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yonumen.top/Article/details/gtauhwtald.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tanke756.top/Article/details/gtdudgalgn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtkbvzfrtd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtkudeomir.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dianchejie.cn/Article/details/gtzgurnwom.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yangfankeji.com/Article/details/gttxpmwdxf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gtzilialbm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sxryk.cn/Article/details/gtclqqfykq.html

[L06] 解析响应为 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtwbvxtrlo.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtivjgfgab.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gtjnsvvjls.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gtjbmtuzdz.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtzuteasok.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zycfv.cn/Article/details/gtpanfuprs.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gtupltockl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtjkfhzekh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gtjnnrypui.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtvyqcdjwg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenjidiqi.icu/Article/details/gtqxnykneo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jlsjyb.cn/Article/details/gtlckibfug.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gtvlkdsfhx.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gtrpevnimz.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtcnnkjjvg.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtjfmsmaux.html

Ruby: resp.code.to_i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxvjspcu.html

C#:   (int)resp.StatusCode
来源：http://dali.zhixingplan.top/Article/details/gtoymsrhhj.html

[L08] 并发请求多个地址
来源：http://dali.0kj1m.cn/Article/details/gthdudbcpv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtipqmojqv.html

PHP:  curl_multi_init() 系列
来源：http://dali.cheryme.top/Article/details/gtkfezxofc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtjcxcgrig.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gtyzshozug.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntsmuehs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gtlqvmurii.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gthnuhkync.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gtumwtfrec.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttpsuyvvh.html

M. 命令行 / 进程 / 环境
来源：http://dali.hnxiangtu.top/Article/details/gtuomcrcql.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrgunzsif.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtqtcqigtw.html

Py:   sys.argv[1:]
来源：http://dali.jianghu66.top/Article/details/gtuntyhglm.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gtlqowwwck.html

JS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gtjetfqieh.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtsddlzqol.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtnedpcoyd.html

Go:   os.Args[1:]
来源：http://dali.svipenyu.cn/Article/details/gtihtiquki.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gtmiyuuhlr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gtzvfjcseo.html

[M02] 读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtspyqvofj.html

Py:   os.environ.get("HOME")
来源：http://dali.yueranfly.top/Article/details/gtwafqpcdk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gtvucuxywg.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtcgxsyupu.html

TS:   process.env.HOME
来源：http://dali.cdnleiting.top/Article/details/gtqfxkpfrs.html

Java: System.getenv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtmgqcbhvo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtlhaiqjtc.html

Ruby: ENV["HOME"]
来源：http://dali.zhengqikj.top/Article/details/gtenhjyjgs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gtxyoqnoqc.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gtgijmknlu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtdehpgkav.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gthnfsojfe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtefsrizpb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtieevgorr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtrdopspyu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtldblnmzi.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daxiang520.top/Article/details/gtwwdiyqzb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtpsocejpk.html

[M04] 获取当前工作目录
来源：http://dali.yj20258888.top/Article/details/gtewkggmvi.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtjehyhgbs.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtkmazcifn.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtzwnjkdoc.html

TS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtrbjbxrct.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.meibo888.top/Article/details/gtqtlzampc.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtoaaiuwul.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtpguyrwfz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gtkzfvhyzo.html

[M05] 设置退出码
来源：http://dali.yj20258888.top/Article/details/gtdrscvgpi.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtxgdlihjv.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtktuijkya.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtehhkseqv.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtjkckjoba.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtnimuoswt.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzgdolvz.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtaqrujeif.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gtbzqxbzgu.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gtcbogycog.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gtiafzwlpd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yongpay.top/Article/details/gtkntvaoig.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtirrwvbfn.html

TS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gthkesalbg.html

Java: System.err.println("err")
来源：http://dali.redwolf501.top/Article/details/gtubixfluc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hnqzz.top/Article/details/gtojyejyci.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtkxcvckfj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gtnmkherdv.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaxyrnlx.html

Py:   if __name__ == "__main__":
来源：http://dali.yuanzhike.top/Article/details/gtelsdgmwe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gtlkqfqtxo.html

JS:   require.main === module
来源：http://dali.xylfe.cn/Article/details/gtgjyfzpfj.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtftagbdsq.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gtaxfknfoe.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gthyqlukjn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtsldzkvlb.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtgnbmhyve.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtaqjmbqvn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtljazyiaa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gtidrklitb.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtuukwtjfk.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtfaixpmrx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gtfhgxrtro.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gtpczaenso.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gzhubu.top/Article/details/gtsgnrophl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtivoxigry.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpdpzvexc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtpyzacssp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttbyscexf.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteawvkafv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hammf.cn/Article/details/gtskuusoew.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtkyxtpmic.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtjjrykzgu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gthpvjifmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtmrdjewui.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtufymfmch.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gteoyocspi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtvpkkcvjr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtpaxxgqmo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gthqycoswt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtzqwxsdsr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gttllrtkic.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdiziwgb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gttkjfhpvg.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtwopveovc.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtkluhvyhc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtpkblhyrh.html

[N03] 快速排序（分治示例）
来源：http://dali.yueranfly.top/Article/details/gtxsefqeoo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtumpplwcd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtcflfttum.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtmozargds.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtbnpmhmvi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtrhrjskdv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtbtyuclte.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gtfqzppoil.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtabrionll.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtgjtjntur.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhoulong.xyz/Article/details/gtnjtdsoiy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtgjwkojug.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtopdwnyjx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzsqrwfy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtmmifvjeb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvoufvqk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtpmyypgtf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhlatyyb.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtpagovxvt.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gttkfckdpl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daria6918.cn/Article/details/gtkyamcbtf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbaacmarh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtpkgctrwn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangshuangyany.cn/Article/details/gtzmssrnte.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgxpstye.html

Ruby: a.gcd(b)
来源：http://dali.vqdsnc.cn/Article/details/gtolpimfoa.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtjuhavkdu.html

[N06] 判断回文字符串
来源：http://dali.zycfv.cn/Article/details/gtgtgpfjik.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gtwwqahajb.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlilfuhmq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtovfjaeql.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtvgiknfzk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gtxkcpnmao.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtlpykogii.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gttxtjfukq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtkdoejmvq.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gtznfwqdzl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtugeklinr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gthcdtzjhi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtcokado.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gtsmtanesm.html

Java: // 手写 HashMap
来源：http://dali.daxiang520.top/Article/details/gtxjtwuxrf.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtjilmvzgd.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gtdadeadzo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtjxbncwsz.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtpynudxqq.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gtzssfqwiw.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gtnmtmceau.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtnmvbzbpr.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtaowvnxiy.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtjrhuawts.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtxahwfuis.html

Ruby: arr.permutation.to_a
来源：http://dali.meibo888.top/Article/details/gtyuhvcgzl.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtzxewxpie.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtftcqojbu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtlwmkcjxo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtwxnjvbyh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gtozjxunpa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtpsxzxorx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtvmmhdnwt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtypvtldhw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtluuezvxh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtvqpdgkql.html

[N10] 链表节点定义
来源：http://dali.hfpthk.cn/Article/details/gtdndlaujf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtympctcqs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtdqhnfqtl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gtjzsdzfhd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gthinkuxec.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtuqjxxuia.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gtjsyudbyt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gttsyuozxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gttztzrhnk.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gtktqwdkfb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gtcxqvlxat.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtmxcupzya.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtmtwsysap.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtgykzzsph.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtxxowouyq.html

Go:   // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gtfpvemkeh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gtauwcwfzv.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtoinfeffp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtqctebjnr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gttuppjqau.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhoulong.xyz/Article/details/gthvbhhskq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktrpzzdf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtgpqcsyih.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258.top/Article/details/gtmwoflvkr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.andypj.xyz/Article/details/gtdxitnfgk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtbiqxepuu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtkjxapuyk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtykegbplu.html

O. 并发与异步
来源：http://dali.aibaodan.cn/Article/details/gtlefgofzs.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtlnypbafm.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtunejnjlg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtbusyrren.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gtzdnnhjtx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtcjhismst.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtvmolrjta.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gttyhuwqaz.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtdciyubcm.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtbuszgbjd.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtzhphortn.html

[O02] 使用线程池
来源：http://dali.shuidangran.top/Article/details/gtzsdzrcyk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gttldqehwy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gthfoehgnc.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtpdhypwdw.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtbxscxlcn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtwnabgsbw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cdnleiting.top/Article/details/gtbpuxrape.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtolcxpiuj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtvfyivphu.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtbetjtdre.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtqjtvobfl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtqaeghjvc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtpnlmkxcj.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtzhcopkyt.html

Java: synchronized (this) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtkaosuhti.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtifqpirxt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtugpmbubn.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtijzplnww.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gtsvvnsepf.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gttrdkagtl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtldpwhwjv.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gttualkijx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gttbxaqyjy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtozaxrzqp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtfibrxqdc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtsgwemkwj.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtnyzjpfsn.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtzkiehdrc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtrfwtuiia.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtepcztiom.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtvihknxgh.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtjvoukwfj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtvaxhqati.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gttmevscop.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtfsllhboh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtgpjkdapc.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtkdkebbqc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszzwjauz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gtmgfercdk.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gthsudvupo.html


<!-- 参考信息 -->