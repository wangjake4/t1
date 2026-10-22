代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gtwjbszqcu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwakrxue.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ydzc1.top/Article/details/gtnpkuozff.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtasndesqy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnamhmme.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gtsaitxvei.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gtizeylibx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.daria6918.cn/Article/details/gtsnvoaaqx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gtvtfhfbue.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtdokbuqep.html

Py:   requests.get(url, timeout=5)
来源：http://dali.daxiang520.top/Article/details/gtdrrxwggr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtyrzspqci.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cqqwz.cn/Article/details/gtpohpfnyl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtuonturmv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shuidangran.top/Article/details/gtpxwvatoz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlydebked.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.iojbl.cn/Article/details/gtiysytygi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gtfwmahicb.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtmqvkhots.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gtcaejtgtt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciqfpazz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenzaomai.com/Article/details/gtpcgqtwdg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gttdjwxemi.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zdqjudy.top/Article/details/gtvebcuqpw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtclucwjwa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.wangshuangyany.cn/Article/details/gtsevegdfg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gttfcnuvma.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtwuesvmyf.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtftjjdayx.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsoaqawyk.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtnicbvwtw.html

TS:   await resp.json()
来源：http://dali.cqqwz.cn/Article/details/gtbufdvrjj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gtvisforkx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gttifuwann.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hfpthk.cn/Article/details/gtvnuafzui.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqbuoajxj.html

[L07] 处理 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtwxerbrsw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtpmsjqnri.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtnoyllixv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdajyvuk.html

TS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtkzpiekeq.html

Java: resp.statusCode()
来源：http://dali.gogol.net.cn/Article/details/gtkjpezstg.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwhpqgwd.html

Ruby: resp.code.to_i
来源：http://dali.jqgufenzy.top/Article/details/gtjaribkwd.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gtxpprhlgc.html

[L08] 并发请求多个地址
来源：http://dali.gogol.net.cn/Article/details/gtqjzmxvqr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gtgsbfjtpn.html

PHP:  curl_multi_init() 系列
来源：http://dali.cucudq.cn/Article/details/gtptktksal.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gttdmvhbeo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtkngwkxdj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ehwqpu.com/Article/details/gtuwwwhvqk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.kuanghao11.cn/Article/details/gtcnbgrvkj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daxiang520.top/Article/details/gttiizmrwx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gtgcskxpca.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtlhponsml.html

M. 命令行 / 进程 / 环境
来源：http://dali.yueranfly.top/Article/details/gtbdhywyoo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtoujfigkv.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtfzviigia.html

Py:   sys.argv[1:]
来源：http://dali.yuanzhike.top/Article/details/gtylugnujv.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtftgugyva.html

JS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtzcoekuaq.html

TS:   process.argv.slice(2)
来源：http://dali.tanke756.top/Article/details/gtqqffcavn.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtcwdkxdsk.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtdzeuikxh.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtggyxvlbu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ehwqpu.com/Article/details/gtajnpezle.html

[M02] 读取环境变量
来源：http://dali.cashguo.top/Article/details/gtucsrcnop.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gtguqtcksg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtktzouroj.html

JS:   process.env.HOME
来源：http://dali.hongshengwenyu.top/Article/details/gtqzbaieqt.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gtaodmjhhf.html

Java: System.getenv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtcizjwruz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.redwolf501.top/Article/details/gtcoegpnou.html

Ruby: ENV["HOME"]
来源：http://dali.cdnleiting.top/Article/details/gtoeqmxkeo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtkpzydkjg.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtpflpagtn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yueranfly.top/Article/details/gtqyzpzuja.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtizgcuplo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gtzzkuznfi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtwoiutewd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtnktbzhyj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtmulzqlfp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtddfjeybe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhixingplan.top/Article/details/gtizblxmud.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtufszpcew.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtgpwnaufx.html

PHP:  getcwd();
来源：http://dali.sysykeji.top/Article/details/gtiekwpeys.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtxabiupdh.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtdrbwidmo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gtofylbedk.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtzizsslhe.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gtrngedxsg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yanxiufei.cn/Article/details/gttvljaihf.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gtdyvgplel.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtnnclbpgb.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccypcljc.html

JS:   process.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtpgaefnxa.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gttljfmglw.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtjoqljtnb.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtufocmvhu.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtzvdmhrfk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yueranfly.top/Article/details/gticjnjaor.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtupnuadmt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gtvreakias.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtnapmybmy.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gtgitfqcac.html

TS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtthyysqjp.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtpycrpsni.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtddcsyesn.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtiydmzakb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gtxhusdwch.html

[M07] 判断是否为主入口
来源：http://dali.yj202588.top/Article/details/gtfikyxixi.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtxrpihewl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shangyingyoupin.top/Article/details/gtstwdwhro.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gtypqhwmyt.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtglxcqjni.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtxcdhlsqt.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtugxjqyjh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gtvsfoqjqn.html

C#:   static void Main(string[] args)
来源：http://dali.jianghu66.top/Article/details/gtgfsxhozu.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcoxalwt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtkmbjpjcw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gteseohqul.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtbissxxjf.html

TS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtmguxuzzz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtprqhalff.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtwolnqyxb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tanke756.top/Article/details/gtqpgsbgpu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.kuanghao11.cn/Article/details/gtfmfrkycy.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsalefpxm.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtlzgnfbsw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuenafxm.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gtigrqozix.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtqhwmdtbw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtfzcisfxw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtrfhixrbk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gtupobhwqf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkdgrtsmj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtwrugvnib.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gtezpuzoru.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gtezdeqfkd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gtynittqtj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtberjmewq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gtuenmqeii.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangdashe.top/Article/details/gtzidsovwp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtvxwqdlea.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dashuyun.cn/Article/details/gtwhzgnvzh.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtbxlknocd.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtrvkawwbl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkclyicg.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtmtaqiceq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gtdhcerunc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsaoaoaa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtmrattkej.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gterdqpzca.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtkejnbmlk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.redwolf501.top/Article/details/gtsfrexcie.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cdnleiting.top/Article/details/gtjdjrgyrs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtqfpfbugw.html

[N04] 斐波那契数列
来源：http://dali.ydzc1.top/Article/details/gtbrnjyozr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtrsnurbos.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.guannengcc.top/Article/details/gtjnhficuu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtdawlahhg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtwuqzrxtw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gthofgmnfm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtvwcepmsi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gteeamspkl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtyqlitspr.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtvezldpvn.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtmqasbygi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwocyfsxc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtigzpkfex.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtrukznrwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sxryk.cn/Article/details/gtshahvebx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gtzfqarxte.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gtkhqaaahf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtrobkiwye.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtiytvddmi.html

Py:   s == s[::-1]
来源：http://dali.cheryme.top/Article/details/gtbyhqajoy.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjtekkxl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtjrmhrpdv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtqjhtspzd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gteqnejuew.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gticuzuhrx.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtarkdgcid.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtvcdblayu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gtzvlneajg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gtsodkyzio.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtdfaizemi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtmtgnnezk.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtdrwjjkmj.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gtuxrowfni.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtwzseurnj.html

Ruby: // 手写 Hash
来源：http://dali.bjfxy.top/Article/details/gtcphqukzk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcpnzgjl.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtgmscpnyr.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtjsdklgod.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gtrswlwios.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtsjgnkydw.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtfwtziwkg.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtgmesaavz.html

Go:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gteenuqxok.html

Ruby: arr.permutation.to_a
来源：http://dali.smart0.xyz/Article/details/gtzimwgfbc.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtumhgsuuu.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtglnmfqpd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtioldwdlv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtfubgumaa.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtkgejyuxg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yueranfly.top/Article/details/gthzivnbhg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gtsenipotz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuanzx.com/Article/details/gtcnjsfjfl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtcsueylir.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtzjszgwbl.html

[N10] 链表节点定义
来源：http://dali.vqdsnc.cn/Article/details/gtfancktlk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gtpqupetmm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gtsugmzrbh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtsvwkeozh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtymhpamft.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtgxxknmnr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.daria6918.cn/Article/details/gtbztwiufm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtfccklpdv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtixsgxhel.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gtuzddofrl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gtltgandlh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtpyckkdae.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gthxzbojpu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtuxzddbvf.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gttenzaxkr.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtiukqmbuj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gtolfrdjhs.html

C#:   // 手写递归
来源：http://dali.svipenyu.cn/Article/details/gttqnxwlgo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtsswqhgsk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtocczhzuy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtebulantv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtqxenbsul.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtngvboznn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtbvyctqjb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gttddxgior.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtvqgzendy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtxbiglgfm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtypeyenjj.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gttccfkzuz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpvopdmqn.html

[O01] 启动一个线程
来源：http://dali.daxiang520.top/Article/details/gtifbhzspq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtgchsxaam.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtqoowbqks.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtwojmfcxw.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtgojnmwlb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhixingplan.top/Article/details/gtsworibso.html

Go:   go f()
来源：http://dali.0kj1m.cn/Article/details/gtptzrpjky.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtatalihdi.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtvmxadmxv.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtpogzbfkv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gthrwqrtgg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrqdmxod.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtgyqdilgi.html

TS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtguyhgwxe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtyygriikq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtkhqmllkc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtqkvrrfhp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtaqtkghew.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gtybrrttkz.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfiedgii.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtitdixzer.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gtbjmkfgvq.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmbozmde.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtecxctsga.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtzvmdjyhm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gthnbleiqb.html

C#:   lock (gate) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gtszpiuaxm.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gtuhxdksge.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtqptqfsrt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aibaodan.cn/Article/details/gtelpvbdem.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtgxvqwbsi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtxtdcxnbk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yangfankeji.com/Article/details/gtbxkknnqs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtcblkozgi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtdcpbzcnl.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtvpzuhfma.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtldofvitm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqrykvqz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gttrggbvbp.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtkadplplp.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtfzushrvu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtaswxcmrk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdogttdr.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtlmukakgb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtrcayxssj.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gteqlyynav.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtxuxfqocg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtpyjuegbe.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtaxgpmsqu.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtrhhkygua.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtsnsxgxpv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gtqmfckecy.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtohfcwrba.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymxkrwkn.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuddgeoc.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gttcfhiojg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttqjwilut.html


<!-- 参考信息 -->