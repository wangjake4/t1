代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.havefunace.top/Article/details/gtowcrfhpc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnqzz.top/Article/details/gtogxryukq.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gtzieqlcah.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cqqwz.cn/Article/details/gtgqujqnag.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtkqoncavn.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtwwgesxch.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gzhubu.top/Article/details/gttnofwedx.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gtvdnwvjzy.html

[L03] 设置自定义请求头
来源：http://dali.sweek.top/Article/details/gtclhsasya.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhoulong.xyz/Article/details/gtacrcqnnl.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtxazydxrn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtqijpmnwf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtnjhmfkif.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tanke756.top/Article/details/gttuhustma.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.bjfxy.top/Article/details/gturygtypy.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtyjjaazzp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtimcdavyl.html

[L04] 设置超时
来源：http://dali.meibo888.top/Article/details/gtoltvxuxb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hnqzz.top/Article/details/gtelavsiiu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.sxryk.cn/Article/details/gtavdrchfg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gttecacphf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuanzhike.top/Article/details/gttckzelaw.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtjfpbonec.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ppjwa.cn/Article/details/gtwwwyfmhf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtqsqxzixy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guowangkeji.top/Article/details/gtwgsvitti.html

[L05] 上传文件（multipart）
来源：http://dali.zhiwuduotai.top/Article/details/gtfnhpgmuh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtoftwsebq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yongpay.top/Article/details/gtpzagnefr.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtnlribfhe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtyzgdwoou.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.0kj1m.cn/Article/details/gtbnaljkxm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gtvyogicnp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gtjlhqspiu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtdjoxsxaz.html

[L06] 解析响应为 JSON
来源：http://dali.andypj.xyz/Article/details/gtmrtzoqxl.html

Py:   resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gteuodeapa.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gttgtxxuan.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtsxnddjkl.html

TS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtckdswxzi.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtxbqvghmm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtmxvjgrwc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gaohongyu789.top/Article/details/gtwjmkaivr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjausaxqm.html

[L07] 处理 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtfhovdwhw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppvmmidx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtnboiujur.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtrumswzjv.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtxgaixpow.html

Java: resp.statusCode()
来源：http://dali.yuxming.cn/Article/details/gtiyygdglg.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gteoogivru.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtxdkodjzu.html

C#:   (int)resp.StatusCode
来源：http://dali.pengpengdd.cyou/Article/details/gtvckoogsa.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gtneapubcv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtxqrhtded.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258888.top/Article/details/gtebncnuyr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtkkgnowlb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtqnewfmmp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gzhubu.top/Article/details/gtghcbcusn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jiagoushi.top/Article/details/gtifozwbyk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhacgkfw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtyjotgemq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtugjncqfb.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtktyzynxt.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyouwaeek.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtpjuawwnz.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtgevpinzn.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtgaoifykd.html

JS:   process.argv.slice(2)
来源：http://dali.cashguo.top/Article/details/gtrojexvkl.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyaibpyz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gthzvpcviy.html

Go:   os.Args[1:]
来源：http://dali.yj202588.top/Article/details/gtyivfgkzr.html

Ruby: ARGV
来源：http://dali.havefunace.top/Article/details/gtwqejkfuy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtmbjusopc.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcidjkuoe.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtxvibiyye.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtkowgdqeb.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtguesxnit.html

TS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtityokiab.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtuggspskk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtpracskwq.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gtpjtgivuz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtmwbginpf.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtjmhhmcqq.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gogol.net.cn/Article/details/gteivsweso.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cdnleiting.top/Article/details/gtvgfvxzsq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yongpay.top/Article/details/gtxbhyrmec.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtristnozj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtbnjkccms.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtvoohvyue.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tian-w.cn/Article/details/gtxpyztsqu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangshuangyany.cn/Article/details/gtbryhmrnt.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gtxpfdperi.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtrmhapoow.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gtaolhygnc.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtyuvzzkur.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gttyedrvxi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtyccqeith.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gtsempsdml.html

Ruby: Dir.pwd
来源：http://dali.jyoumei.cn/Article/details/gtgtiwuvwp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtzvrzelbw.html

[M05] 设置退出码
来源：http://dali.vqdsnc.cn/Article/details/gttthpxxnr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtplalukzp.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gtxtfferie.html

JS:   process.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtncvauzrd.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtjwznzytj.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtajiyojco.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtzdydojkb.html

Ruby: exit 1
来源：http://dali.tanke756.top/Article/details/gtrxfakida.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sufxvd.cn/Article/details/gtjldibgqo.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gtzstkwhww.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtjobhgkwj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guowangkeji.top/Article/details/gttdpltuzs.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtuiunhjda.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtylnunowp.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtmzhglloh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gtwymavezb.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtucwmltha.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gtetewszew.html

[M07] 判断是否为主入口
来源：http://dali.aizwys.cn/Article/details/gtahmdvqhi.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvebvcsrd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtbecwbpcp.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtzsyasdwq.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtzqsaoshq.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtnlqrxfcx.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtkvjcczwb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gttlvpsdwb.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gttwtclcqs.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtfklqyhkd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gtlmbmtqpv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ybcxt.top/Article/details/gtxbkyxhpa.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtcumqdugh.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnuxhwbs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtgxpxeuka.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtdzkltiuq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtudcucyck.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guowangkeji.top/Article/details/gtwvyuphvp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtoponvhsx.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gtaidpmkqn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtjgvcwrnt.html

[N01] 二分查找（有序数组）
来源：http://dali.gzhubu.top/Article/details/gthjpisumw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtheoifvck.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtiajwmpjz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtakbnkpbs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtagazfest.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtdoljcptk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gttjbdozcd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sysykeji.top/Article/details/gtwxjnzgza.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtzecnlpiq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaimsetg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtmxaanmpi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtnrnpxwev.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtllpizkvy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtnlucsfdg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gtokbxxvtx.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtfasufaxp.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtweijipax.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnxiangtu.top/Article/details/gtuqbhujhl.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtklvcwdsz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258888.top/Article/details/gtrmejhrzs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtwomtsayh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtjhpkzadj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hysaishi.cn/Article/details/gtykrtqomt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtlbrxftyg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltssmoll.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgfzy.top/Article/details/gthunjqhuu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtbjyttsej.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtkopdjsbg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtnhpqwhcj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtyvrkigvd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtyzggnxmp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtcxyfkieg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtdnxdyjqw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gthlecwjfj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtiremhqdu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtzlipjdua.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gthyxeroxk.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtlscddkks.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gtshjidwrr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtuqjjopcf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gteudlyacs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtdoalwecm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gtpmpgohco.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gtqvmemjhg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtpttqibwz.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtqnkamdjq.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtgqblyqob.html

PHP:  $s === strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcbcjjjp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtdgumokny.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtbpcpkrsm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtdqqhyqaz.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtsropotqu.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtqxbuqlzy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtxojvnhqm.html

[N07] 两数之和（返回下标）
来源：http://dali.gogol.net.cn/Article/details/gtihhnyarf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtobnfeaeu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhengqikj.top/Article/details/gtgvszncdt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtcdxopbbl.html

TS:   // 手写 Map<string, number>
来源：http://dali.nwbrower.top/Article/details/gtixszoicc.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gtocftsshd.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxnwuvgy.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gtvvxiaxje.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sweek.top/Article/details/gtzqxnmrfc.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtpbukciiy.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtgphjaplo.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtjnsqyanz.html

JS:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtbkvntsnu.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtbwngqkwp.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtgjyvtgzg.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtlcqholvc.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gtlbcoahwf.html

C#:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gthtcbowdq.html

[N09] 栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbzitaqn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtmvgajwmx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtgibhjfde.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtzhxtibxr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gthntdtbrw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthybbtguf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoonaaoml.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtippjkkrm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gtfzlpalcc.html

[N10] 链表节点定义
来源：http://dali.zhengqikj.top/Article/details/gtwlfpjiiq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtrfcobyvx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gthvbmxxqg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbddqnqp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtbikiyiga.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gtdngychrx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtxptdiify.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yonumen.top/Article/details/gtowfkntwt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gtdjuzsmlu.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258.top/Article/details/gtdgtgodye.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtxmxzoffm.html

PHP:  // 手写递归函数
来源：http://dali.cheryme.top/Article/details/gtgastuugd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gttndoghwt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtxivzlvvs.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtokvhpluo.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtkfsdurmk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gttxxdwzvs.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtrnbbqjpd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpqpkgqmh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtodfvnftb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtfihjqayz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtajwyywlj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtxbjefppm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsgzewzk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gtasbmoyfn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ydzc1.top/Article/details/gtsjhphrhe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtvfzzyetl.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtachtdnaz.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gtgljvqyse.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtxlayojvf.html

[O01] 启动一个线程
来源：http://dali.daria6918.cn/Article/details/gtxwjkremy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtbpychxla.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtmflpygir.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtdwcortgn.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtnhvlbcii.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gtyinbyaev.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtquqqilnz.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtndccrzof.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtgxhcymhu.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtbahtksjx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtsnfcgqhu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtytyovmer.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtgzhqktkd.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtxdygxufe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxfsvokr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gtfttnxnws.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtsacdnjtm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtahfnlcud.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyasqyoy.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtnyhkhfvn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtvezgbkts.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gtebgvquav.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtpvxgbgyk.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtplkixvdf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtljvnywyj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gtokkhkasa.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtphjhjddz.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtckzicubi.html

Py:   async def f():⏎    await g()
来源：http://dali.jyoumei.cn/Article/details/gtlbyxkczf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtmuoqcjax.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtrjgxshya.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtbejufyfa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtmhdkiaie.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtsnhpnxeo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtkliabmcp.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gtwuasewmc.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gthipiikhc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gthclgelzf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtpaumcqna.html

JS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtligxrlyi.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtljkrnybm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtbcbiabiz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gtlnoqdlxa.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtjysyxhwl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtfawxxgsn.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gtkyharysa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtjktenlma.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtpgkfbqwy.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtsevwpblw.html


<!-- 参考信息 -->