代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.kuanghao11.cn/Article/details/gtfbzgkdpy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gtgpgekawh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guowangkeji.top/Article/details/gttoxsxrsu.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gthjowlrzz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.wangdashe.top/Article/details/gtwdcazijj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hysaishi.cn/Article/details/gthbpdosuu.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gtkbxenwia.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gtsnzrjgtf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sxryk.cn/Article/details/gtvjbkrxyl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.redwolf501.top/Article/details/gtedcfubrf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.vqdsnc.cn/Article/details/gtjlvztchq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gttjokbfoy.html

[L03] 设置自定义请求头
来源：http://dali.cashguo.top/Article/details/gtpplxjoyh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhixingplan.top/Article/details/gtyapwusrw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guowangkeji.top/Article/details/gthsxkznfk.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gtvamqycas.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtirmdwvwl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.iojbl.cn/Article/details/gtrvllnjmq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gtecblnliu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.smart0.xyz/Article/details/gtuqssgjyz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daria6918.cn/Article/details/gtijyeutnl.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gtkvfygdoi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gthsqwknpj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtqwghciwc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtvgxpbhmn.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gthcnbzapn.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.daxiang520.top/Article/details/gtzwqdempl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj20258888.top/Article/details/gtfehteyzj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtvelqhrsu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfszfvzq.html

[L05] 上传文件（multipart）
来源：http://dali.guowangkeji.top/Article/details/gtvuhoocwz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zycfv.cn/Article/details/gtiysjghwm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hongshengwenyu.top/Article/details/gtjdklqhau.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtdxweangm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gthjfjtxhs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtfyupcbaa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gtjqyuubas.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gaohongyu789.top/Article/details/gtojomzzsz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtgcajrxfv.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gtwpibjvls.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtmmbpsbvc.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gtjqqidusx.html

JS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gthzzishwh.html

TS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtfhkzzbus.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtdxcummbu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfxonpcz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jiagoushi.top/Article/details/gtzsovjnsv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tian-w.cn/Article/details/gtzhprbdqe.html

[L07] 处理 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtmcxfddul.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtjxzslizs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigufen.top/Article/details/gtwumipngm.html

JS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtyehtkmpj.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gttfiwsczc.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtlqzshbxb.html

Go:   resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gtdnjbfcjb.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtibfakjfl.html

C#:   (int)resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtolzmgvlk.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtdqugqimx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gttpelmomn.html

PHP:  curl_multi_init() 系列
来源：http://dali.yvedp.cn/Article/details/gttyhchlcg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtdkpusjvc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gthktbczwj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cdnleiting.top/Article/details/gtomfxeacx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258888.top/Article/details/gtrccmobyr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqtkbiwm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtscstlpom.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyezlihcq.html

M. 命令行 / 进程 / 环境
来源：http://dali.fengsongda.top/Article/details/gtsrvnqrmb.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgqsxypgn.html

[M01] 读取命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtimpccotj.html

Py:   sys.argv[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwpyioszw.html

PHP:  $argv;  $argc;
来源：http://dali.havefunace.top/Article/details/gtjocdqsei.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtsiqrotvb.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gterjmxmrd.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtyqwjxoqw.html

Go:   os.Args[1:]
来源：http://dali.gogol.net.cn/Article/details/gtngrphrqt.html

Ruby: ARGV
来源：http://dali.jinghuilouyu.cn/Article/details/gtfscrxudi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtdythvrjc.html

[M02] 读取环境变量
来源：http://dali.iojbl.cn/Article/details/gtpqgnxrbc.html

Py:   os.environ.get("HOME")
来源：http://dali.redwolf501.top/Article/details/gtnzxsimsc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtnxxjegen.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtljshpsju.html

TS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtutikeksp.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtgyyhyybu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gttycrqlyk.html

Ruby: ENV["HOME"]
来源：http://dali.cucudq.cn/Article/details/gtuvwbowpg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gtylmadtyy.html

[M03] 执行外部命令
来源：http://dali.tian-w.cn/Article/details/gtkkvtorml.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtsynjqzda.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jyoumei.cn/Article/details/gtpfwtspmn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtartmutto.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtbinkpvjm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtyfinkonh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gtzizpotol.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gtzrqlgrjm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtkxyrfpwj.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gtnigxaflt.html

Py:   os.getcwd()
来源：http://dali.shangyingyoupin.top/Article/details/gtkvqphlzh.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtlcmvcjba.html

JS:   process.cwd()
来源：http://dali.yuxming.cn/Article/details/gtbimnsmoj.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtwgovsolb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtrzqdxvut.html

Go:   os.Getwd()
来源：http://dali.sysykeji.top/Article/details/gtwqlprzsf.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtfmpoqcdo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gtfvlvbdge.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtapzgynds.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkkprclj.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gtilokurzi.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtxucekmyi.html

TS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gteyfswxvw.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gthzlsbkus.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gtcfkkvsaf.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtjejcnmcb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gogol.net.cn/Article/details/gtjpstjdmk.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangtech.top/Article/details/gttczrifjw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtfnwdlrjp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtbyjkgqhg.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtkkinjkdt.html

TS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtedsaezzy.html

Java: System.err.println("err")
来源：http://dali.xuanzx.com/Article/details/gtdiehegkm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtjoebrvlf.html

Ruby: warn "err"
来源：http://dali.sweek.top/Article/details/gtefwarnsn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yongpay.top/Article/details/gtarjxwsxm.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtrrhcqeca.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gtuiyikzvs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtocbgmbon.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtwiylrgwg.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtdpiyslgl.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtsueicoku.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gtdizaghss.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtcdeiuszu.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtdwsqxuru.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtlrrjqepd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gtjbownzrx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cheryme.top/Article/details/gtzkwwxkvv.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtvfpomjpy.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtiwhynoxu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtfvinwmyt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtanpioxls.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtsceevyjz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shzxlz.cn/Article/details/gtduzzeugp.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtfcsinijb.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gtglrblvrw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjmehemuc.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqfsrqtbl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtqyaagqhr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtwocqsehi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtveatrdim.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtywepnoqe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtititanhd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gtxxkgxupm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtnqvspfbf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtdmtpsesf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gthklnrgcd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtznntevpk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gthvppcgpo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.andypj.xyz/Article/details/gtsnflabdm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gthmyqzhma.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtpuqhkejc.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtxycpxfws.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtjqablwts.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtkuocbrqz.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtdyhfpqgu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtmcnnupnd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.vqdsnc.cn/Article/details/gtiypldnis.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtflchdwmm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtbcpqcvsb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtouawnjne.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gtiunsqufi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gtfhtawglj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gotoacloud.top/Article/details/gtublzurfk.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gthcjgrdvj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangdashe.top/Article/details/gtryewkzgj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtnlqkumfc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtpurzrlyt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtugddgrnt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gtzrvwezpi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtztvrzcjj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtckcwsytz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtazpuunbi.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtrtjlfkyh.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gttvhymisr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtppeabpim.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbieaaydc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtlhecryye.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtuhxdnrmu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtfhszgcst.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqbokplj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gtkazqxcxw.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtsulyrlrc.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtffqiqrxv.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtonmtqipk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtcpxqbawi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtornaiyue.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sufxvd.cn/Article/details/gtjdxxyzyk.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gtpekamejd.html

Ruby: s == s.reverse
来源：http://dali.meibo888.top/Article/details/gtpnnetbzl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtidgkpdcj.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtypwbmsou.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gteqmelygh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gtkegqlqxw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtjjrotnga.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqycuovw.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtzqlkgqdh.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtxwwxetmz.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtschebrzq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gtayporwjj.html

[N08] 生成全排列
来源：http://dali.sufxvd.cn/Article/details/gtsnkcrppn.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtgbutwilg.html

PHP:  // 手写递归交换
来源：http://dali.hnxiangtu.top/Article/details/gtedbwefcl.html

JS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtcnhdebyg.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtfjceusdf.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtshvxmjkg.html

Go:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtizukyorj.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtugxbsqci.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtszsamdrk.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtemngalhn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gtaxjqkzpt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtpelrfxyi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtaenbvbgk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmtzxoun.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fzhhl.top/Article/details/gtsyfbzmif.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gttuqzwgbg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtmuclykbv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gtafpldxet.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gtrgvzrglf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuanzhike.top/Article/details/gthhafbwof.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtiuqkkxzp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtrwbdgqwz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ydzc1.top/Article/details/gtbmmylfuz.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtayigxrdg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hysaishi.cn/Article/details/gtudbclnsc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gtovumotsp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gtyvtkpzlb.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gtfhxotzxz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gtphyjxhkb.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtmmnavxue.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gtmhzoeemh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gtnppkmqbz.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtotbnfjdp.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtrgunccdu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gtbmspvgkb.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtmkutuywu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtnwrokpys.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenjidiqi.icu/Article/details/gtaruhgddi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtygcyivum.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pengpengdd.cyou/Article/details/gtyfgszlqw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtugojaubu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gttfskgtbd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtdzdsnjah.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gtwcksussl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtmyzzogpr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gturayfway.html

O. 并发与异步
来源：http://dali.dianchejie.cn/Article/details/gtxgmhatwn.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvkaiptej.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtvullkank.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtysimbvmn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtikgjqxmf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtjhpybfoj.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtdiwhdciz.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gtdwuawlnn.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gtbmihxqmo.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gtspbndevm.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtwnmwbvuj.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtbfxvzmum.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtlfwenkda.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gttospkvtd.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtohbjiwed.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtxtzounsv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzeuscvv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtmdvxenlk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.birdmap.top/Article/details/gtrnbpesim.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtiqgebzhq.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gthzijqxgm.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gtvhnyqfou.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwddlukv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtalzwvqzt.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtgerkswsz.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtiqorrazi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtwhjjrxsi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtwqibpomr.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtuzpsfyfz.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtadpymaro.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gtvpazydta.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hysaishi.cn/Article/details/gtquazmrvl.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtypcmgwss.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtrarmrmro.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtfqproazq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gtscwvwepi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtwjercjcg.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gttkvjjoxo.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gteviexhbf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gthtxpmucs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtbtibugrs.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtvligrouf.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtqhpigyuy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gtllwwahyo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtexfbhrjw.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtetkdajbe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtuugugkpz.html


<!-- 参考信息 -->