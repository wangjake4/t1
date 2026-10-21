代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.jqgfzy.top/Article/details/gtsyksblyw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gtezavlvqa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.dashuyun.cn/Article/details/gtrhhjpcqm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtdckdjyzm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gterpowewq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shzxlz.cn/Article/details/gtxiffmtgk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dianchejie.cn/Article/details/gtfksbdsgx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nwbrower.top/Article/details/gtwyluxnsl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cucudq.cn/Article/details/gtwfploedf.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtiyihvzlx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxuanxn.top/Article/details/gtyntjxepo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gogol.net.cn/Article/details/gtalddastv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gtttqhgeax.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gtpcnzmbbh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.c1oappe.top/Article/details/gtdsxnbxev.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gtwiajwvsl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtlzxqmbwt.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtetxbvytb.html

[L05] 上传文件（multipart）
来源：http://dali.jinghuilouyu.cn/Article/details/gtiynwbfgf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgufenzy.top/Article/details/gtgwuszxyf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xinyue.icu/Article/details/gtgshqsxao.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtuqsegcpa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtzywnqkhn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.tian-w.cn/Article/details/gtjjimsyma.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtbsabolcy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gtwsykuowy.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yuxming.cn/Article/details/gtssdmxboh.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gtynmdtwfe.html

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtnhobpbte.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtghnmoosi.html

JS:   await resp.json()
来源：http://dali.havefunace.top/Article/details/gtetejmxjn.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtguzgedmp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtwqdvurzq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtmpymryon.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtszpadvef.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtgxsalmje.html

[L07] 处理 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtoujtpnlu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tian-w.cn/Article/details/gtlcwybvlu.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtrvzelfon.html

JS:   resp.ok;  resp.status
来源：http://dali.chenzaomai.com/Article/details/gtmtwuozma.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gtsqfnmqcr.html

Java: resp.statusCode()
来源：http://dali.snrcjt.cn/Article/details/gtkuueasxq.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtjtwomlxl.html

Ruby: resp.code.to_i
来源：http://dali.chenzaomai.com/Article/details/gtglhwgtra.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtonjydzty.html

[L08] 并发请求多个地址
来源：http://dali.9152youxi.cn/Article/details/gtaujksuic.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtfxppnfbh.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtrhaohxmc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtzlxcorgf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtoqorhzgz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gtxdllmwig.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yuxming.cn/Article/details/gtuonxlhyg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtozrhnkdf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtgxhypydc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtahkrwguw.html

M. 命令行 / 进程 / 环境
来源：http://dali.shzxlz.cn/Article/details/gtzykuqghf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtwqrfgxbm.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtkmtwtybt.html

Py:   sys.argv[1:]
来源：http://dali.ybcxt.top/Article/details/gtqyygzrsp.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gtnpopddbk.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gticgluvqf.html

TS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtxqxgcoxu.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gtdbejdklc.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtbtpajkfb.html

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtzghabkxx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtffwpiqyq.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gtnnccmquk.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtgqjzfsck.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtbmeiewwg.html

JS:   process.env.HOME
来源：http://dali.tianlin.xyz/Article/details/gttjutmbdo.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtyjvmsreb.html

Java: System.getenv("HOME")
来源：http://dali.yonumen.top/Article/details/gtsschldjo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtoszxurct.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtdrdgjivb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtwbrovqwu.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtdetukwbt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gtvfatufzw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtjmternul.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gthxsksejd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkzmcwtq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gtzbhdcemz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258.top/Article/details/gtwgtzicco.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gtheeturnm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gtqftdtqoc.html

[M04] 获取当前工作目录
来源：http://dali.cheryme.top/Article/details/gtwsxfpwev.html

Py:   os.getcwd()
来源：http://dali.ppjwa.cn/Article/details/gtintlzzkn.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gtrtqqkeuq.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtthdclfnr.html

TS:   process.cwd()
来源：http://dali.shuidangran.top/Article/details/gtucozrnae.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258.top/Article/details/gtamdxnjqm.html

Go:   os.Getwd()
来源：http://dali.ybcxt.top/Article/details/gtcpamwymw.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtfwifjelq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigufen.top/Article/details/gtxdtqmfmo.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gtxhmpwrdz.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtcjklrlpk.html

PHP:  exit(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtljdqrfoi.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrxrkjea.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtuigrklwa.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtywurmqvb.html

Go:   os.Exit(1)
来源：http://dali.yvedp.cn/Article/details/gtrvdgchfv.html

Ruby: exit 1
来源：http://dali.jinqigufen.top/Article/details/gtrknkioyp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtqitwhlrr.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtvftpprhf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtgduhavqb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtgcdqfasc.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtdhonxawi.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtvzwwtfez.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gtdrtxqkbs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gtpciddnyh.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtbuophxla.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pycfn.com/Article/details/gtrwshljet.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gttjjjpohm.html

Py:   if __name__ == "__main__":
来源：http://dali.sufxvd.cn/Article/details/gtavaactum.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sxryk.cn/Article/details/gtwcwotyno.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtfcudgqkv.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtycjfwviv.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbomisex.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtpoekwdkr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtwmgcztue.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gtvfsxfzmz.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtrbcariab.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gtiuunkyyd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmimqihq.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtlzxauxnk.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtfsegurar.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangshuangyany.cn/Article/details/gtgjziuzos.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtaipogwnd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtaopjblrx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtusymqlqg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtaykpvgci.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjeshkrj.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtohfngsvu.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtyyublmai.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtjpjgzexq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcgnwyxm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtzlafazkd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtmunnvgeo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtsbzgybsa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtpfeaumkf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gthotyukmt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtkzglzyxu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yanxiufei.cn/Article/details/gtscbkvmyi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtjcqtwswc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xziqi.cn/Article/details/gtzgnawroo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtuxacernq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtltnpdxlr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yonumen.top/Article/details/gtyxtppsld.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gtzauvljtr.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gthwpulzdv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtvhfywqmu.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtisydmpck.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gtnzbkqnwe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhongyouzk.top/Article/details/gtvmlrabwi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtthjjjhtf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtnfilymeg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shzxlz.cn/Article/details/gtxscdbjjj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gtouzyacmk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ppjwa.cn/Article/details/gthbkxhvhp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gttrpvglhb.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdolqqpf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtbrtqfduv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gtjmlzeygm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtvecwhwup.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtowsvpliy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdfdrbfxt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jiagoushi.top/Article/details/gtjjxqlslf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdhinnkf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtigtedxaj.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtvcfyxure.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtmcfbscsy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtpeeghvcv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgpugwkhj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtralvpruk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gtxlyidorh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtgjpqpcfj.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtgldikimw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gtaazvxxov.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqiovrhi.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdlhdhqz.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtmaghiyvq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtuqdusxqz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtvvjuvrjf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtnbpbespx.html

Go:   // 双指针从两端比较
来源：http://dali.bjfxy.top/Article/details/gtbkydsehi.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtssxcgkao.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gtizerrxef.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtfrveroud.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gtaoedlqsk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtikifvgdn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gtgpjzrczm.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtvodnkeaq.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gttxprzpzw.html

Go:   // 手写 map[int]int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlokydifj.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpmxauox.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtzposrwnp.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtlutqipad.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtdpqraseo.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtbvztsnzc.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtakuyfydk.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtrlaevyhs.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtrcqzkmle.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtstyfzagm.html

Ruby: arr.permutation.to_a
来源：http://dali.redwolf501.top/Article/details/gtmcwwbyyi.html

C#:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvwxlxzo.html

[N09] 栈与队列
来源：http://dali.jyoumei.cn/Article/details/gtahhgcxnc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gtxhvegvrn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtnbtebeci.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtszwfayia.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gtrlkbmyiw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gthrzwyawe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.svipenyu.cn/Article/details/gturpdadeg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gtecaggcrh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtzsnrlbnu.html

[N10] 链表节点定义
来源：http://dali.iojbl.cn/Article/details/gticqcrudz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtpnwejjgg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtzmzhlgne.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhongyouzk.top/Article/details/gtcwrtgptg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtgcljomxt.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gttbclndok.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hywenlv.cn/Article/details/gtobrrwmlw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gtpviqqgxb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtlwzsgdsw.html

[N11] 二叉树中序遍历
来源：http://dali.tian-w.cn/Article/details/gtsvwtmuax.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hongshengwenyu.top/Article/details/gtrqucceda.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtchspycov.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtthgjyghd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtenwjefqq.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtaensvdty.html

Go:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gttcsrjbcg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhiwuduotai.top/Article/details/gtkophvldt.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtujkixcnx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gtylidaqqg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gtjsvcepml.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jyoumei.cn/Article/details/gtybtrbyjc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gttdmahejq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gtebcyrvwq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gttacuzxmy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtfeokujry.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtgdpjfkup.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfjjskqq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdcpabvmn.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtknmhmtoi.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtiylxexub.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtmjjhlmvx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gtgbenozuk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtgeywhwhq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtspqdfydq.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtnfdzelny.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtdkfkhklg.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtkkwirxeu.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtlhlvfjfz.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gttmxlplfs.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtabicxnct.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gtlnoioxmd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpcjszip.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtoxcwxotz.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigfzy.top/Article/details/gtjndwnjpv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtrwregtbi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtdtyaxsat.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtbkjwfhtd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gthuwkbach.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtktmudhvn.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtpxmlfvuq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gtliupkjtx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gtekbsyvjc.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtcxhaaqym.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtlqliryql.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtupgcpucr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtsvooltml.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtrjazvskp.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtbaernkqi.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtppjjzvqd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gtlmtifjgb.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtjnhcazfj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtenrbwwik.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gtsdjrrrsh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtqzlxtvtk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtlhbpoyld.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtubhckeww.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gtbedouczm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.andypj.xyz/Article/details/gtbgkcnsig.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkebufpf.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtrrphtgne.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtyjfddlil.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtdcicufzy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtjquasmzl.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwwtnthj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtmurijnkq.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtkskphrpa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtjjxrxzsc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtfzsrtchh.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtvtzhrjfp.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtvwnrkxnc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gthswercug.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkfcisgi.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtdbomjkyd.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtiiqyaaiv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtechxgcgz.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gtbaslkiye.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxhnboiwk.html


<!-- 参考信息 -->