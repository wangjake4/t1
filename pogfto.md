代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gteyshztng.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtexoboluk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtckokyxjh.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtwdfbzqop.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ppjwa.cn/Article/details/gtbfequsyo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtyvrmczap.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtdopcesjc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.c1oappe.top/Article/details/gtcxrizpwo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gtjjiaiqql.html

[L04] 设置超时
来源：http://dali.shzxlz.cn/Article/details/gtlzaoaryb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hammf.cn/Article/details/gtkpemwrng.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtywrnzpzn.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gtzqipxrkb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gtaqjnnvkm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtdvbzglpv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gtycikpffg.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yongpay.top/Article/details/gtnswsoxqb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gtkccygjrr.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtvahkrgce.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.guowangkeji.top/Article/details/gtkaqvwfrk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258.top/Article/details/gtfrqibtlw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sysykeji.top/Article/details/gtpgytiiqs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtrwxfzksu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtjslmwelt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.hammf.cn/Article/details/gtbxntrzwo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gtpzgqizff.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtcakudfvb.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtcwyyvlqb.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtydneosyy.html

PHP:  json_decode($body, true);
来源：http://dali.birdmap.top/Article/details/gtrbzalbtf.html

JS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtfygfgwno.html

TS:   await resp.json()
来源：http://dali.guowangkeji.top/Article/details/gtfygnvtqv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gogol.net.cn/Article/details/gtcppwuehk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.0kj1m.cn/Article/details/gtgurugjlj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sxryk.cn/Article/details/gtnbqnzqax.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlwbkmmh.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtzdprxule.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fzhhl.top/Article/details/gtzqurqodg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.mhx1999.top/Article/details/gtkqtqfwyj.html

JS:   resp.ok;  resp.status
来源：http://dali.zhongyouzk.top/Article/details/gtxtctdnrj.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gtxiycnrkd.html

Java: resp.statusCode()
来源：http://dali.9152youxi.cn/Article/details/gtjspwmmme.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtemwtjusn.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gtspbhplnk.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtwvgywiup.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzdjskwy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jyoumei.cn/Article/details/gtezbjgfut.html

PHP:  curl_multi_init() 系列
来源：http://dali.hammf.cn/Article/details/gtnzmrzlby.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtefjqaboj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhbolioe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jlsjyb.cn/Article/details/gtdcixadhz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gtnzsrcptt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pengpengdd.cyou/Article/details/gtnzjoqqho.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtvbneowhb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvokitjxk.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinqigfzy.top/Article/details/gtcasehxzg.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvtadsnju.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtrpmazbjt.html

Py:   sys.argv[1:]
来源：http://dali.pycfn.com/Article/details/gtlgwwnblu.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtsjpvjwjv.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtiqqhkswg.html

TS:   process.argv.slice(2)
来源：http://dali.bjfxy.top/Article/details/gtfrrqaasi.html

Java: args 数组（main 方法参数）
来源：http://dali.snrcjt.cn/Article/details/gtrabsaiap.html

Go:   os.Args[1:]
来源：http://dali.jinqigufen.top/Article/details/gtwxzddiqm.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gtjnggomxp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtjbyqvbny.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gtdxzlavnr.html

Py:   os.environ.get("HOME")
来源：http://dali.yuxming.cn/Article/details/gtxcufyvtx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtlyjugrdu.html

JS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gtbqhukgpa.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtygjxojie.html

Java: System.getenv("HOME")
来源：http://dali.c1oappe.top/Article/details/gtedbgnfze.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gtcvddowcj.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gtvbfhksel.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gtfotkjdvy.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gtynwjyhou.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj20258.top/Article/details/gthksxlwxv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xylfe.cn/Article/details/gtgodsknvx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtatsuvyzg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gthkausdov.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhongyouzk.top/Article/details/gtsasykoxu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.9152youxi.cn/Article/details/gtknugenfg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtvonybijl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtvmkinmjw.html

[M04] 获取当前工作目录
来源：http://dali.snrcjt.cn/Article/details/gtxeajfasi.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtsksheggc.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtfjqxbzpn.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdfvukcw.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtbpcmmayo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtymorexng.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlinteubk.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gtlhibdnvc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtwowbzoex.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gttwlbuqkk.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtnqkzorcg.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtkroklarw.html

JS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtihqnhonb.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtgjocvgni.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtwxggajgg.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gtfmtdnjdv.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtmzpixutc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.0kj1m.cn/Article/details/gtpqsgnpsi.html

[M06] 向标准错误输出
来源：http://dali.hysaishi.cn/Article/details/gtvvshlkpk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtjwxjcfbf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtilhpurxv.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtiszsadhf.html

TS:   console.error("err")
来源：http://dali.yueranfly.top/Article/details/gtlpioxjyb.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtkqhpldiq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gtduzfbggv.html

Ruby: warn "err"
来源：http://dali.snrcjt.cn/Article/details/gtvgrfmmou.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gtfkecaswi.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtlsmpkolx.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtbwhfmmrx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtwdfwdrgv.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtkbjwwctn.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtwejnotne.html

Java: public static void main(String[] args)
来源：http://dali.ybcxt.top/Article/details/gttkhimhac.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gttrvnpntk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gtcfrmaxrb.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtepuxojch.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtlburkhzc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.vqdsnc.cn/Article/details/gtrhypscxz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtpdmzekcn.html

JS:   process.platform;  process.version
来源：http://dali.hongshengwenyu.top/Article/details/gtqhcdajtw.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gtvhjnqwoy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tanke756.top/Article/details/gtencjtcfw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtlvbsmdzp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cucudq.cn/Article/details/gtahttbbap.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtdsjufppu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthnkutsxm.html

N. 数据结构与算法
来源：http://dali.zhixingplan.top/Article/details/gtkruvsqtr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmvyxrgjq.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtfjqskvkr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtsnxsfnqg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtsrmnavxp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtngtbdxbk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtdqthvssd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtktgeggxt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtgybysrjp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hammf.cn/Article/details/gtrgzolmzf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwltkkfrc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigfzy.top/Article/details/gtvcwmazjx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjmjibcq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtfbclgbco.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtkhusvxld.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gtrltbrsuh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtdrfqefpy.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtjjcgmxgm.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtrjsqkpla.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtttcybmgl.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gtgqwlozru.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtcelnfcbl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtrrkhhhij.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtrbzsygey.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtnqsilobz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gtqfvlcxdl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtlbxaqvmh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fzhhl.top/Article/details/gtkueslnly.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtnbmepbtf.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtobzvwysc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtdkhxqrrq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tanke756.top/Article/details/gtvgyjpuai.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtltphfvsa.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtxldcicco.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtwkugjtzw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gthwpnzdoo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtpgeurrmz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtacdfsnyx.html

[N05] 最大公约数
来源：http://dali.yj20258888.top/Article/details/gtsrkursvt.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtznuxrwet.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtszrcmmlw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtakbsgylv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yongpay.top/Article/details/gtgyvzeacx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gtmmvdombf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsxfmfse.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gtvaxjxtpu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gthhsxrbki.html

[N06] 判断回文字符串
来源：http://dali.chenzaomai.com/Article/details/gtkxoxflvu.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtazoztacb.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtjuhgayia.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtazkntpqv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtwanaobux.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtdqzyqfut.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtjatvhfel.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gtuilonopg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtzwwxzuwi.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gtkvzibuce.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtmfmyjbhc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtwoiejwbt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdaaidyo.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhengqikj.top/Article/details/gtopfxjutq.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtbnzjekgs.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gtaxffaqsh.html

Ruby: // 手写 Hash
来源：http://dali.xylfe.cn/Article/details/gtvexuniip.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.wangdashe.top/Article/details/gtdiwazfep.html

[N08] 生成全排列
来源：http://dali.xinyue.icu/Article/details/gtrwopjlwc.html

Py:   itertools.permutations(arr)
来源：http://dali.svipenyu.cn/Article/details/gtxmwgszjx.html

PHP:  // 手写递归交换
来源：http://dali.jqgufenzy.top/Article/details/gtrspsbhzy.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtgkxshgrw.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtsetixuva.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtcamxyios.html

Go:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtpsvxmmdh.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gtcyknzwnm.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtutnisxzd.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtexjkpkbp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtufgkfuqd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtbcrtgjwg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtjzipkmmo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tian-w.cn/Article/details/gtaobsmoyk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtkjjiracx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gtvvjjqnso.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtmsonvyyj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gtwzkgndvf.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtyisdnkbe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gttiytlpwm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtnhnqfnix.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yangfankeji.com/Article/details/gtpwqgfmms.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gtoxjllzbs.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtesydsris.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.0kj1m.cn/Article/details/gtijirmmiz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtlrigfsot.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gtwxqghhyi.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtompoxxhd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpnqtgmz.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtbgwjzntu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtkktorbfz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gthhkzuagw.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtlfahfxen.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtqglatdbl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gteztdcarh.html

C#:   // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtbqzzfrjy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gtomqqkrof.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gthaenufeh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258.top/Article/details/gtlvueilor.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtpqbnfiyy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtbqlgxdpm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtfkutppan.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtvihdfgau.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gtyemjmapx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtcylhdygp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtruasrxsu.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gtnjpgrorj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgewlwalb.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtcrlcrscm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gtuofdsxsm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtnrrfibsp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtvneifdet.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtafotetok.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtdinoimqg.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyttwhhgs.html

Ruby: Thread.new { f }
来源：http://dali.fzhhl.top/Article/details/gtnsgjprvh.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtpobqtcny.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgtrfihp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtbvhnolja.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtdwlkkvcg.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtakcxyhuy.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtywbmlcxo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtudxnogvd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtqrdszsrh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtzsqtseor.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtvhnfjvjb.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtmfxwqheu.html

Py:   with lock: shared += 1
来源：http://dali.nwbrower.top/Article/details/gtonlmvnvd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtkckoztmb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gtzyyrklzt.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtfbqnnpsz.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtcmlndcax.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwltwlwsp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gtgawtwukx.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuqhhuqb.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gtyuqxmyas.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtzvdknckh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnxiangtu.top/Article/details/gtjkokqgep.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtgdnnrzyq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtvtzvsobd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gtcdtxkmdi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtdvslmmwk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtcqhyfyfg.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtrsyfwlez.html

[O05] 并发执行并等待全部完成
来源：http://dali.quarkkingdee.top/Article/details/gtkycgafco.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwoxwaroy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtsennwiuq.html

JS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtxaggqymy.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtnzxhkrer.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aibaodan.cn/Article/details/gtvpjhqsna.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnsicajy.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtbzavohhx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvqrmmhlp.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtnvxaxiho.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtvzcuwbth.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtrlqbtqwb.html

JS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gtkwpydffe.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtcgsdwnwy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gaohongyu789.top/Article/details/gtxgwesysm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtfzzjsjin.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gtorolrqtk.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtypdxpvlw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmrnonqex.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtdyrwpico.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwjjbqcj.html


<!-- 参考信息 -->