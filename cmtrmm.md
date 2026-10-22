代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xuanzx.com/Article/details/gtgigrdxqt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.cucudq.cn/Article/details/gtojsolbxk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gthuyvgluz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gtwtxcjfno.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.wangdashe.top/Article/details/gtoxdjjdbe.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sweek.top/Article/details/gtikaqhikl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnqzz.top/Article/details/gtadoxkdlk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gtgsukliye.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtrukonbqs.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gaohongyu789.top/Article/details/gtddibrdrk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtqlsqffxt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangshuangyany.cn/Article/details/gtwsyarnar.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtituyvckn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gtotgbmcrf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gthpedzzzg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtzxwmvlzi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guowangkeji.top/Article/details/gtavqpjfsk.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gthzshjygl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ybcxt.top/Article/details/gtejwqaokd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gtnysnnozd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtdsgckxfd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtgtxxjxqu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.dianchejie.cn/Article/details/gtgpyccwmg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtmnamqylm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtwpovashq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtrzwbnhkw.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtmmgprrmj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ivvv.top/Article/details/gtuuonqjdz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtxvmriorw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hywenlv.cn/Article/details/gtsectxeja.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.feifeiyinyue.top/Article/details/gtosezjkbb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtddsbtddt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gtyfzddmtc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtlawteyvu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.316326.xyz/Article/details/gtsfbinhle.html

[L06] 解析响应为 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabhzxour.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gttmzytgjo.html

PHP:  json_decode($body, true);
来源：http://dali.hywenlv.cn/Article/details/gtsnlspmgq.html

JS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gtepvnfoyt.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gteognlffe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.9152youxi.cn/Article/details/gtjefghmap.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yuanzhike.top/Article/details/gtyivzunxo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjavvvxk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtqlvkyjyx.html

[L07] 处理 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtphgldeal.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangtech.top/Article/details/gtedxnduny.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtnqulkond.html

JS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gtzrnnohzh.html

TS:   resp.ok;  resp.status
来源：http://dali.havefunace.top/Article/details/gtimyevkds.html

Java: resp.statusCode()
来源：http://dali.zhongyouzk.top/Article/details/gtxacfaazw.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gtayhqihnz.html

Ruby: resp.code.to_i
来源：http://dali.kuanghao11.cn/Article/details/gteyllzfdu.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtmmsgaudg.html

[L08] 并发请求多个地址
来源：http://dali.aizwys.cn/Article/details/gtcuwtyfxu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtbdkmgdli.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtlmbdnsof.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtmrjiluuu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtfrkcotbw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtdnriujbk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gthenhjrca.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtkkhgieon.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gtyyughxlw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjwutupdr.html

M. 命令行 / 进程 / 环境
来源：http://dali.shangyingyoupin.top/Article/details/gtzxpjgvri.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuyluusix.html

[M01] 读取命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbtvxzgm.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtorofnzco.html

PHP:  $argv;  $argc;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqqbxiaw.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gtwwjogfrk.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gtmfmtcdbg.html

Java: args 数组（main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gtkmvfdlqb.html

Go:   os.Args[1:]
来源：http://dali.daria6918.cn/Article/details/gtllfbchbi.html

Ruby: ARGV
来源：http://dali.yangfankeji.com/Article/details/gtkdmrdqnq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtxhjjuqrf.html

[M02] 读取环境变量
来源：http://dali.daria6918.cn/Article/details/gtyloqevli.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtfrpbyuge.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtshrtpxok.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtcbjtlyyh.html

TS:   process.env.HOME
来源：http://dali.jlsjyb.cn/Article/details/gtwjteyzta.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gthmwosoil.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gtyncqhytm.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gtftcqrxid.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sysykeji.top/Article/details/gtxfydaeyc.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtevnkkuvz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yvedp.cn/Article/details/gthgohfost.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdogotnxj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gteoyggvqr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtximcxeus.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtosvgwbqc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gaohongyu789.top/Article/details/gtqcvwqftw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuxming.cn/Article/details/gtlozzzpdu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258.top/Article/details/gtunxrijzm.html

[M04] 获取当前工作目录
来源：http://dali.9152youxi.cn/Article/details/gtauikpxlp.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gtnesfhmbr.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gtuutxmcvi.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtnovaymby.html

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtescskatb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtmuahzhaw.html

Go:   os.Getwd()
来源：http://dali.cashguo.top/Article/details/gttracomcu.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtvdhfjusb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnepzpbl.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gtohjdfhlc.html

Py:   sys.exit(1)
来源：http://dali.jianghu66.top/Article/details/gtoeobiuzx.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtwfjvpmgg.html

JS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gttkkfpfte.html

TS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtfdjmmzkb.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtcywkfmkv.html

Go:   os.Exit(1)
来源：http://dali.zhengqikj.top/Article/details/gthoxqtpjf.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtbtrljrfx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtyrhbflxi.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gtnosztvhh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtkdsccnok.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.smart0.xyz/Article/details/gtnppokucw.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtqqwxwcko.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtdlggqibm.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtlyusixqj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gtahynnirm.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtkknizdne.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.fengsongda.top/Article/details/gtufehhjmu.html

[M07] 判断是否为主入口
来源：http://dali.shuidangran.top/Article/details/gtyjrmxawv.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gthzyylzdf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtoffjyled.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtpyqcjcff.html

TS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtvuafmgut.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtjvfthoca.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtxadfiioj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gtwolqyxob.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtoioyuvie.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtuoqseozq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstffkohr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxuanxn.top/Article/details/gtlpkjepmj.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtbccfvwpy.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gtgktyqsdp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtdtnbzgwz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtanzmhucu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenjidiqi.icu/Article/details/gttcplzwir.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtbsbnevee.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gttuytxdpw.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtfjjadzuv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfprcaowb.html

[N01] 二分查找（有序数组）
来源：http://dali.daria6918.cn/Article/details/gtajavpzyq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtoselkaqe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtwhqtfuaw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yueranfly.top/Article/details/gtlhflzgmg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtzsxbxodq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtoxmlaasb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtaihucdco.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gtqylhabzx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yongpay.top/Article/details/gtjiiphpik.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtjjhagubg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtzeywcsku.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtdujuqrrf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtfroeeiyo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gthazbffsn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtmznggluk.html

Go:   slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtyzxfycng.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtnumjbjrv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtejftbltg.html

[N03] 快速排序（分治示例）
来源：http://dali.hfpthk.cn/Article/details/gtjvrqttur.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtovszvzbl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zycfv.cn/Article/details/gtvffegxgc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtytxinkya.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtnanppeor.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gtdnwxocju.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtgmovsfjx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gtviehgmxk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.0kj1m.cn/Article/details/gttpgnfpcb.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gtfuuunybb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gttojgeouu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtkxnovhat.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtpnvtbtvb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjfeqqjz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yongpay.top/Article/details/gtmiylvklg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.svipenyu.cn/Article/details/gtafomnnij.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtnhjexpid.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtqeeselhq.html

[N05] 最大公约数
来源：http://dali.cucudq.cn/Article/details/gtdfnruwgt.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtbbuxnmdp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtibaxczxg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtglohlzwh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gtfibxehqg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.0kj1m.cn/Article/details/gteorbxitd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgfzy.top/Article/details/gtkhcdcmxb.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gtuwbxhzjy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtwcdjxlpb.html

[N06] 判断回文字符串
来源：http://dali.hnqzz.top/Article/details/gtabzjufyo.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtlkrtbqwm.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtwapikhfl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtguaiavly.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtllnfvehr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqorqbotc.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gtnfhqokvw.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtinwrpkfn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gthssdhuoz.html

[N07] 两数之和（返回下标）
来源：http://dali.feifeiyinyue.top/Article/details/gtjqyodjsz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gtwvaxwiik.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.pycfn.com/Article/details/gtzipmisvb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.chenlongwang.top/Article/details/gternpcctr.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gtzvwlmzmk.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtexzfwnlk.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtmuljbmop.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gtvljwnqxy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhengqikj.top/Article/details/gtnwkykcao.html

[N08] 生成全排列
来源：http://dali.jiagoushi.top/Article/details/gtrfdmopki.html

Py:   itertools.permutations(arr)
来源：http://dali.gogol.net.cn/Article/details/gteeyttbqu.html

PHP:  // 手写递归交换
来源：http://dali.jianghu66.top/Article/details/gtjibfrwil.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtibavtazc.html

TS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtmjcltckh.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtzehdzgvv.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuslyyab.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gtnxynebfe.html

C#:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtwgcyrdfg.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtfiszjzcf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gtfumwbfpy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtxtzqprbw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtbkjycblu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gtsrvjcqvb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtecvraaey.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gtcosooajl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtxjqqmsge.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnmmnhip.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gttouiefzh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtyukfqfxi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.haohaochexian.top/Article/details/gtwmfxvzfy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guannengcc.top/Article/details/gttvabzcsy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtlgloffww.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtwtpgvtxv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtgcdiewuh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtfwzdennk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gteigwibnu.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtzhlxqmtl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtwqjqsarw.html

PHP:  // 手写递归函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwvpuezft.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtxbmpcuen.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtcearirbl.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvbhywrh.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtjqrzjdmu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtnbwkyfsb.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtdpjkdopb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gtdycogsln.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtcyerzfiq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gtckrvyafm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtshqqflsg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gthmwrelbb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtcafiyaer.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtcektkvaq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gtvcysvhpv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtzkzcrmwu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcyzmffpb.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtczgjrnmt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpogtflch.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsnfxtyq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gthtbogrpr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtekmrefds.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtmussxnng.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtlctbjcaa.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtcbknksdm.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gttabvijih.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtcbqtviht.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gtevsiijiz.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtvuapntvn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtidncmabh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjkmnvna.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtsunvzmuh.html

TS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gteahlgvcn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gtknbaesja.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcknvsbna.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gtcrxowmrr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtdaecgnni.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gtvvbpxljj.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtbxunbvjp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gtrvyovhsa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtelkpfaax.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtazmoyrki.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gtavlaxzgb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtwkpuyluc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtunqvxmjn.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtjslxeuud.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtcjxzioys.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtksmrrxwb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtoijeprof.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtblfvlzou.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtrknywcgg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gttxuzohgo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fzhhl.top/Article/details/gtrlzxvtgu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gttybplfdl.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtxfbphfwv.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtjacqedsw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmngcowh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtvjrmqwry.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtigosmevv.html

TS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtbpbeynvg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtpourlvwe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gttosghtgn.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gtztvpnxgb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gtlmwgydip.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtawgeprwc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtqrfuevpu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtpsuscnuw.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtuznlnikv.html


<!-- 参考信息 -->