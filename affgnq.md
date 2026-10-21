代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtslzmkukh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gtuknymqbb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.shzxlz.cn/Article/details/gthqtpqlww.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gtthoaminu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gthdlzdtkq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gaohongyu789.top/Article/details/gtjopugtei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gteihwbnal.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gtfqojonkz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.nanxuanxn.top/Article/details/gtrmhnvejk.html

[L04] 设置超时
来源：http://dali.haohaochexian.top/Article/details/gtrvllgcdl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtiwmtdohy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.wangdashe.top/Article/details/gtsnclifft.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gtysrohwbo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtejyveqlv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangshuangyany.cn/Article/details/gthgsiizik.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.snrcjt.cn/Article/details/gtaitlxzgz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtwbgnryhf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yj202588.top/Article/details/gtybsznqpp.html

[L05] 上传文件（multipart）
来源：http://dali.c1oappe.top/Article/details/gtuoewaswk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xziqi.cn/Article/details/gtffojlhji.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzbxknsc.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtugtlqxjm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gtwhshujxu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtgbehuyun.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gtqtieqzpc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtauyspiky.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gtjooqfiky.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtaedidwyx.html

Py:   resp.json()
来源：http://dali.xuanzx.com/Article/details/gtloshbwid.html

PHP:  json_decode($body, true);
来源：http://dali.andypj.xyz/Article/details/gtzvujmuyg.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtbjjpvork.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtmgcctxfo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtgzkirmrq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gtfvhxuqnp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sysykeji.top/Article/details/gtybmvoirk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtbdxmuczb.html

[L07] 处理 HTTP 状态码
来源：http://dali.316326.xyz/Article/details/gtizompzcw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gteisyhxay.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yongpay.top/Article/details/gtaxksnlsp.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtvqthyyoi.html

TS:   resp.ok;  resp.status
来源：http://dali.xuetiantiany.cn/Article/details/gtarezruud.html

Java: resp.statusCode()
来源：http://dali.nanxinkj.top/Article/details/gtinskveqx.html

Go:   resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gtczxqymhl.html

Ruby: resp.code.to_i
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsjehbht.html

C#:   (int)resp.StatusCode
来源：http://dali.bjfxy.top/Article/details/gtapynngqv.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtaloqchay.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gtlvyzxtkn.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtebtrwhqr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtzruuxuwq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gttqjvbike.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gtsqbohgsj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.iojbl.cn/Article/details/gtonpqpqcs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdrzgtkv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hammf.cn/Article/details/gtgxwmbisb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtccnlgpzk.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gtxuqrqscg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtktkagchm.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gtvixnbqmz.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gthpmpsmej.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gtycivbxlo.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gtghkzygge.html

TS:   process.argv.slice(2)
来源：http://dali.fengsongda.top/Article/details/gtnuteefov.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gtvsagyqgl.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtyttxenox.html

Ruby: ARGV
来源：http://dali.cqqwz.cn/Article/details/gthndgfvrq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiirbamgx.html

[M02] 读取环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtpggufnju.html

Py:   os.environ.get("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfldqvxli.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtlbwifche.html

JS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtgtqgtoch.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtfyoutyuf.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtdseutfzl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtmfevbbnq.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gtxtvtjqsb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtfcddqdty.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gthwstfyjf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtlnskwixu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.quarkkingdee.top/Article/details/gtkhocifgr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtaahpdzym.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gticdxesqb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hammf.cn/Article/details/gtrfrfhrkn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cqqwz.cn/Article/details/gtfjptdlth.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtoaookrtf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gtniyfwmuj.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtrsdngrdt.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtppleosry.html

PHP:  getcwd();
来源：http://dali.aizwys.cn/Article/details/gtxaajzxco.html

JS:   process.cwd()
来源：http://dali.jinqigufen.top/Article/details/gtqdthtlsj.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtbdfqgeni.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtffjkqwut.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtykleoyvc.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gtmkbhgfip.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtultsvbzn.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtbqzlggkh.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtrjdqdfwv.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtndejxjvu.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gtsksaoypg.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtccmrznud.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtpuadaovi.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtlnafigrf.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gttumtkyjx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.birdmap.top/Article/details/gtvmbtiwva.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtjmrpnayn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtufwbrfor.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gtjaieihtk.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtfyhwslpe.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtxiscmeom.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtqtlfzxbg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gtzilghvse.html

Ruby: warn "err"
来源：http://dali.jqgfzy.top/Article/details/gtdnqjrkpu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gtuxnfaxjc.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gtdywbcmjg.html

Py:   if __name__ == "__main__":
来源：http://dali.0kj1m.cn/Article/details/gtfgvoacca.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gtlmqddjnk.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtohrsaevw.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtbsbxthch.html

Java: public static void main(String[] args)
来源：http://dali.zhengqikj.top/Article/details/gtmttzylvk.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtvzsjsnsx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.aizwys.cn/Article/details/gtxdxditwv.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtsynxranm.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtmadfvvlp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gtsiwvfmxm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cucudq.cn/Article/details/gtvgvycgfe.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdacgmpcu.html

TS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtnuzztctn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylvvdhyc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gtrlrrlerp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuetiantiany.cn/Article/details/gtkyaqyzkh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gtksfxgiay.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjhpgarct.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtqodigwoy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gthzzlzpvx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gteolnxkpj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtgztgfuul.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtpaicjdzv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtcruhzvoh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtvikfcyjo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtwxgmubep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtwhiiwmta.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gtliixlisu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtdbstccli.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yvedp.cn/Article/details/gtjrszwiuj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtzuxegnxk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gtfoqacwax.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtgsokbbww.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtxqbcxkpr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtsgcibzgo.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtrvwhnyqx.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtbtvknytf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.0kj1m.cn/Article/details/gtvbcwurat.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfiicnqh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gtimuqmsld.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fengsongda.top/Article/details/gtklsomwxk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtcwzpnpax.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtwufhcbum.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hfpthk.cn/Article/details/gthktkfmwj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtuqksvbbt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtimimpvjc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtdvgqmdvh.html

[N04] 斐波那契数列
来源：http://dali.cucudq.cn/Article/details/gtmbcuzzfy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gturdrbhwb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xylfe.cn/Article/details/gtrxmtkegt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtovrwjraj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtwrzrswzn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtbsgaqjfl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cqqwz.cn/Article/details/gteualezme.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtntrnmvpn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtkacyqcyt.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gtwqugscnu.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtknutahzu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gttpxbxsrc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtxdddvyze.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtytlutzoh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gteornsjng.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gtohabzttf.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gtujaavzbl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sufxvd.cn/Article/details/gtsdsrkcmz.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtidvilkac.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtnizoured.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gtisbqdqzx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtmntklvzq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtwzdllabq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtuzgkhkwz.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxxsfyif.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtbvaqkjdf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gtcctxtxjf.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtlrhgwcld.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gtnmnpqwth.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xylfe.cn/Article/details/gtwypabkjb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gteihbjofm.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtwpjwhahi.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtwawtpuop.html

Go:   // 手写 map[int]int
来源：http://dali.yongpay.top/Article/details/gtsrwbjpmc.html

Ruby: // 手写 Hash
来源：http://dali.cucudq.cn/Article/details/gtrbkfajyl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258888.top/Article/details/gtxitocvkd.html

[N08] 生成全排列
来源：http://dali.bjfxy.top/Article/details/gtuhvsasax.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtbpvyvrpz.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtvhpyfxmy.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtvzdnnflz.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtrkzzgxqb.html

Java: // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtllibvkig.html

Go:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtthtlufbi.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gtuekdfwjn.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtxswtjydq.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gteabqiklk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtdrpdshkj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gtlbukauuy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtkvplzewo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.havefunace.top/Article/details/gtepyangmr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtulddupqb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nwbrower.top/Article/details/gtavvtzwxf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtuthdwngk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtpmjhymrw.html

[N10] 链表节点定义
来源：http://dali.pycfn.com/Article/details/gtifqhdfab.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gtyytytiyu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gttvtgdyod.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gtaoaywlhj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtejdgibqz.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtyqmjcuwg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtuhrzeknn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ydzc1.top/Article/details/gtjgtsrhhm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtpnllonod.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gtpbawnpkl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtwzazarrr.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtpvbnusdv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtaexkviwp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtrkinlria.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtcapxkmgv.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtrdkshbtz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfxckgyu.html

C#:   // 手写递归
来源：http://dali.birdmap.top/Article/details/gtxgdmrwtt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gtzosextyv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gtimiaalaw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gtrgxvkjbz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgehtusy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtdijelrhg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnutygzz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zycfv.cn/Article/details/gtfakhsnpx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtniwgkkbm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gttzcxahpd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtqbkcvstx.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtinbuuyzy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjzuqjlla.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gtbooylpez.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shzxlz.cn/Article/details/gtvgucendy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtfvrnsjnt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtrenojymc.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtbxynsdni.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtfohsitzw.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtzfkanltk.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtxdannuhc.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtfuvdhgxp.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gtnhyttims.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gthjrmtgwy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtzhvumouz.html

JS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gttvhzjmbb.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtlxnwryhx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtsmewtjeb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtxomcofcc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtzmjfuvsw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtnvmsghoz.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtmeickrul.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gtsilsprmj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gtfmdftvik.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gttgpoyslj.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtrxntlxix.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtrpwvtakx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtvodekunf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtwtvgvzbk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtyiqunvts.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtekgrqoiq.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuyvfbmu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtfzicqxeg.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtzsxrdbji.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gtnnmdwqfv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtmdlkiqmz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtfgvodbou.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gthvbuklwp.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtoxabmemn.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtjrkbbbyf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtvfffhbjb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gteqwcywxg.html

JS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtdrufvsbg.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gtooonsfrg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yanxiufei.cn/Article/details/gtdbswcnql.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtbfuskyiu.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtawezcvzw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xylfe.cn/Article/details/gtxqtdaoim.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtldnugxll.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gtauasbgwc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtidqiibfe.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryrvvgxr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtzsmizglm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtpefyfbbd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtaazsxntz.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtgarxuvos.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtjnnzcjwj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgzhqegis.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtdeavftdz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthonmjikc.html


<!-- 参考信息 -->