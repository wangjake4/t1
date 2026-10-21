代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.guannengcc.top/Article/details/gtkungbuba.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nwbrower.top/Article/details/gtezwjhohl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jlsjyb.cn/Article/details/gtbnfmszuy.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhwlkcqc.html

[L03] 设置自定义请求头
来源：http://dali.guannengcc.top/Article/details/gteszyubcg.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtmtxndquq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtodboodfi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gttoqcxqbe.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtqqbqlwbh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtfhmsdfyn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinqigufen.top/Article/details/gtdpvqoekn.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gtuqeikdpq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtpfdibmlj.html

[L04] 设置超时
来源：http://dali.jinghuilouyu.cn/Article/details/gtmduhkwti.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtkiwxceoz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuxming.cn/Article/details/gtcdthaffd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gtvgpmvojq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtqasecoyk.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnxiangtu.top/Article/details/gtdfxvaocb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cheryme.top/Article/details/gtgdwprmuf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ppjwa.cn/Article/details/gtjcbrtdpq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gtkiutwmej.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gttbzjaxfp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuanzhike.top/Article/details/gtuohfbfsb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gthzthcgmk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gtyhrhikva.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtwrmfwkdu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gthycmgbpp.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hnxiangtu.top/Article/details/gtqcscrlos.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gtjujezhmc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtgruowxde.html

[L06] 解析响应为 JSON
来源：http://dali.jqgfzy.top/Article/details/gtccgmaokd.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtnlbtlfdn.html

PHP:  json_decode($body, true);
来源：http://dali.xuanzx.com/Article/details/gtrrigcchu.html

JS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtpqcvevdv.html

TS:   await resp.json()
来源：http://dali.yueranfly.top/Article/details/gtzlbvajzr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gtvpdmpfjj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gtbzvkuwqn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhoulong.xyz/Article/details/gtibhautud.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gaohongyu789.top/Article/details/gtutedtkdq.html

[L07] 处理 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gttbumldzr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtgtudkmyn.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlhprbue.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtakrgzggc.html

TS:   resp.ok;  resp.status
来源：http://dali.birdmap.top/Article/details/gtdqmrcccr.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtehbjaxgy.html

Go:   resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtgpfdqczb.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gttachfuuf.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtxopfoqzh.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtajzikmgu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jiagoushi.top/Article/details/gtlzlqxcmb.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtskenhybp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtnllqrkpf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtlkmwvodf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gtdnrcosjq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gttncorhxq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtytrtdqtn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtnrumblvj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttxnzouef.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtiydhtlmt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsyndnzoc.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtndyvwhpl.html

Py:   sys.argv[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsktivpe.html

PHP:  $argv;  $argc;
来源：http://dali.jyoumei.cn/Article/details/gtiiwlvghs.html

JS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gtbkslzlpp.html

TS:   process.argv.slice(2)
来源：http://dali.yonumen.top/Article/details/gtawtvwdza.html

Java: args 数组（main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtsktylrbe.html

Go:   os.Args[1:]
来源：http://dali.shzxlz.cn/Article/details/gtzpgtynop.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gtctqbgxvx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gtaidoicog.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtfflurdam.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtuzyrlown.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtdrywfmdw.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtldtbubab.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtgjzjetri.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtyfidcljs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtehfhmdps.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gtzjsmbzge.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.svipenyu.cn/Article/details/gtwyjlcjvy.html

[M03] 执行外部命令
来源：http://dali.jiagoushi.top/Article/details/gtqefrjghy.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ppjwa.cn/Article/details/gtbnljngmd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gtieinabco.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gteaufmtoi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtzlcgrnem.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cucudq.cn/Article/details/gtxruyjkfl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gttjdwfbpa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtetebuflc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtuoiuwdsa.html

[M04] 获取当前工作目录
来源：http://dali.xziqi.cn/Article/details/gtqpaagyrc.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtjfyuorug.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gtfywnqqoa.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtxrfjtcyz.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gthyjrotvx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtfsrrnrdf.html

Go:   os.Getwd()
来源：http://dali.tianlin.xyz/Article/details/gtxajijmjt.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtwgxirbzg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtlyhgrugw.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtydiqxkhm.html

Py:   sys.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtoaaidrzv.html

PHP:  exit(1);
来源：http://dali.xuanzx.com/Article/details/gtxfqmkyqd.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtdqodlrhx.html

TS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtkdbubjxc.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtvymdaoul.html

Go:   os.Exit(1)
来源：http://dali.sweek.top/Article/details/gtiudhbsdo.html

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gtylnpnlvl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtqeddlfsr.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnndceuw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtyglzqjdz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gttbwmkiln.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtveenpdix.html

TS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtxzdnjwtk.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtipsqdnjq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuanzhike.top/Article/details/gtijgguugt.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtccwaefhe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtziuytmen.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gtfllgwbkf.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtzrkwcyfs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gtynzvoyzg.html

JS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtvwfsjicz.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gthxyvmija.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtrfrvudoh.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gtvgextwdh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gtmnvvmjhh.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkosovgmu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtwjlcndah.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchbpswed.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gtppezadnb.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtsnctqkui.html

TS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtujxamjul.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gtthoehgdq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gttumhnzeo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgufenzy.top/Article/details/gtvfwkkmlr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnxiangtu.top/Article/details/gtqkfwwerv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcpmgagje.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtacklydhw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmkbisuoi.html

[N01] 二分查找（有序数组）
来源：http://dali.quarkkingdee.top/Article/details/gtcuyqovbk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.meibo888.top/Article/details/gtwsqieetp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtwohdwbkx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtvgnarewl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqouybvas.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtrwtuzqfw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtbrbonzvi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gtwumalutu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtxaoeoaxj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmebkbgl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtuecioesa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtuzttjnqh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtumdfevtk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtmksgpezo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aizwys.cn/Article/details/gtgnghfrum.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtccmerirb.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtrhawawtt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtdtgdpsom.html

[N03] 快速排序（分治示例）
来源：http://dali.daria6918.cn/Article/details/gtmjtupqyx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnxiangtu.top/Article/details/gtvbcflxqe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gtmfbkutom.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtojdvzhrd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtjvueamxz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtdctjitqw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtxndoxswr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gtyddikdra.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtyzekhhky.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtnvqusryh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtovbpknca.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtlavgjfna.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtrfpbljjz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtfsswsjth.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtrdvyzvwf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtuwtfgqki.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtbsrhmdxp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtumbgnuxz.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gtlenhogna.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtpgkmmpoj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtomjmqgol.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtslwbdijr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gtlouixowd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.birdmap.top/Article/details/gtqasojbxn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtyzwxgloe.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gtmhkcbssj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtsjkzyfiq.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtconltiyg.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtrpdgatwg.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtoluxqphd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gtfswsword.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtpjpoudto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtbxoofvrx.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtpijoppzb.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtoaqsxizx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjsbgyoc.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtxtbqgdqm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gtfjeejgqg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtakviyxmb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtoyyqqpbg.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gtkgyshekp.html

Java: // 手写 HashMap
来源：http://dali.ybcxt.top/Article/details/gtmkzlmqrp.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtybfttpeu.html

Ruby: // 手写 Hash
来源：http://dali.redwolf501.top/Article/details/gtdtbzannt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenjidiqi.icu/Article/details/gtpjksxeho.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtcxkjvewm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtbxyrytpk.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtumlfezck.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtqljoegnv.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtwsconhkd.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gthmnxvnhs.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtyzambcbn.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gtrbcadqzt.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufzyttwe.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gtykjeqtgf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmomogkg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtqagfblyb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtmqxygxql.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gtmllprztr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtmkuxcbwc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtxelrslcv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtrdqktycm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlacouet.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtqfdurpyq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtcirfaelk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtavjzbhpf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtzegobaqk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsxcblrl.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gtwyovyuqa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.9152youxi.cn/Article/details/gtccjlplhk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gtwrzplivh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtipmcqleu.html

[N11] 二叉树中序遍历
来源：http://dali.316326.xyz/Article/details/gtirhoitzf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenzaomai.com/Article/details/gtbeyepmjz.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtchhdtnir.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtworvezmi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gtybkigszi.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtsqsyjied.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtqfythxcq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.havefunace.top/Article/details/gtlhloifaw.html

C#:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gtssrbqcpg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gotoacloud.top/Article/details/gtwmavgywr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gtujpbfjxa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudvfyyyy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gtzpfygdac.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gttneclquo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtmhvmqqsp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtkygpbaak.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtxaejslom.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtpynuajnd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvyrunxvd.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtmvkkdvgj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmghcyrqn.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gtjaolqjbr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtjcjhlfac.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtlkwlermb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dashuyun.cn/Article/details/gtfsxatlaj.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtmdnmgind.html

Java: new Thread(() -> f()).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtvpiuqudy.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtmjbozlzv.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gtgwuwlgam.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtupxzyhmm.html

[O02] 使用线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtkzdkuprl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtcvsyzwkf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtlrnmxjnx.html

JS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gttlvrwdcl.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtsguoszjh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprwoibax.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtrrqlipio.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.snrcjt.cn/Article/details/gtcghdclnv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtuwxnrvpx.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gteuctklnq.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqowpqcc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtngnzjwxu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtpezkqmjl.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtfrjdmjof.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtdfpddtzl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmqqeudb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtvuerdcuw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zdqjudy.top/Article/details/gtgutsnlaw.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gttjumfkht.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtszpgrero.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtpvqpyglw.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrggfdstn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtxmjcwzul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gtyhxuuuls.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtszsewbmq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gtedvxfzha.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gtmywzuwgr.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtxczzxely.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtaavvjiol.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtdvlfykqy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbuflqeb.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtjmapppdf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitfiuphk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gtvknmnrfw.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gtdpokqvkr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtixvqvdux.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtwxxtctyw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtrbewmydi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtxmpqgpyi.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtvrjvepzl.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gthdrmpcpn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gtapnmbdkm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtuftmktjc.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtfssdjyut.html


<!-- 参考信息 -->