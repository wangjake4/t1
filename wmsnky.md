代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.guowangkeji.top/Article/details/gtfpgzvwgn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtotvlphvu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.fengsongda.top/Article/details/gtzclqlipi.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aibaodan.cn/Article/details/gtdduhktcp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtaezjferf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtiwdryhvo.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtealmoceu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangdashe.top/Article/details/gtrcxyasrl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtlzatwghu.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gtptdmbayu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jqgfzy.top/Article/details/gtihzniham.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnqzz.top/Article/details/gtefrqogww.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gtgaotjnpj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.haohaochexian.top/Article/details/gtboubuakc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gtqkvgikaq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtdgcjtlqw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nwbrower.top/Article/details/gtkjcdtkam.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhiwuduotai.top/Article/details/gtcbmvmqvq.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gtuyxpvvhq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gtofczppiw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtijocnowm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gtafgrjbqv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtdzgfrqls.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cqqwz.cn/Article/details/gtnlwkikyz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gtzhinlrau.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258.top/Article/details/gtohaeeyfr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtsuxnonlt.html

[L06] 解析响应为 JSON
来源：http://dali.dashuyun.cn/Article/details/gtxtzfweln.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gtwbkibooh.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtkdeouvgm.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtnqtebalt.html

TS:   await resp.json()
来源：http://dali.jinghuilouyu.cn/Article/details/gttigpbxbl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtyidiroas.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gtqqgraysl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.smart0.xyz/Article/details/gtliqdsddt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gotoacloud.top/Article/details/gtchauwpoi.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gtaqzswmwt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aibaodan.cn/Article/details/gtiktpfuob.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinqigfzy.top/Article/details/gtdimhnhib.html

JS:   resp.ok;  resp.status
来源：http://dali.fzhhl.top/Article/details/gtcsfctftt.html

TS:   resp.ok;  resp.status
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrbwkuia.html

Java: resp.statusCode()
来源：http://dali.aizwys.cn/Article/details/gtvtfvisus.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtrbrqwarm.html

Ruby: resp.code.to_i
来源：http://dali.hysaishi.cn/Article/details/gtjikxszrs.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gttimywsfe.html

[L08] 并发请求多个地址
来源：http://dali.yanxiufei.cn/Article/details/gttyzpqmfw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ppjwa.cn/Article/details/gtbrncuhkm.html

PHP:  curl_multi_init() 系列
来源：http://dali.gzhubu.top/Article/details/gttchhzzhg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtacohepuf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtigzgitwo.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gtqnuzweqj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtnbrzrzhk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gthdvxbuxv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhixingplan.top/Article/details/gtxzswsqhe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthtspqccl.html

M. 命令行 / 进程 / 环境
来源：http://dali.nwbrower.top/Article/details/gtzwdwgmmb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtydnneqcb.html

[M01] 读取命令行参数
来源：http://dali.sysykeji.top/Article/details/gtgvjmnsnu.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtkrlrdbfg.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gtlmpwtgfl.html

JS:   process.argv.slice(2)
来源：http://dali.dashuyun.cn/Article/details/gtldxjlmbg.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gterhcdolo.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtmwghqjan.html

Go:   os.Args[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gtwihyqxkd.html

Ruby: ARGV
来源：http://dali.guannengcc.top/Article/details/gtdcbgiyos.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtdfubravx.html

[M02] 读取环境变量
来源：http://dali.aizwys.cn/Article/details/gtjmbylqkc.html

Py:   os.environ.get("HOME")
来源：http://dali.gzhubu.top/Article/details/gtuconycxm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.tian-w.cn/Article/details/gtsrdtdzya.html

JS:   process.env.HOME
来源：http://dali.ivvv.top/Article/details/gtoppabwcb.html

TS:   process.env.HOME
来源：http://dali.feifeiyinyue.top/Article/details/gtarrjjahs.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gttnkpnkqu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.pycfn.com/Article/details/gtymzobkbb.html

Ruby: ENV["HOME"]
来源：http://dali.yuanzhike.top/Article/details/gtdvnkvzlo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtczkffbjd.html

[M03] 执行外部命令
来源：http://dali.wangshuangyany.cn/Article/details/gtftbkdrca.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nwbrower.top/Article/details/gtkjwvfzpe.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.mhx1999.top/Article/details/gtznlkiymg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gttbiucapg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gtsgooutfx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.smart0.xyz/Article/details/gtwldqowxt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsoqsiyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gthptoqisc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gtovuetgay.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gtowpvdjre.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gtkuhlsdme.html

PHP:  getcwd();
来源：http://dali.gotoacloud.top/Article/details/gtwcftsoee.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gtcrhkydro.html

TS:   process.cwd()
来源：http://dali.yueranfly.top/Article/details/gtnxxtozed.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvamtznhf.html

Go:   os.Getwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkonmpjd.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gttxgirajx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gtanhntynk.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gtgxdtbnbz.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtpzftword.html

PHP:  exit(1);
来源：http://dali.cashguo.top/Article/details/gtifnmchzp.html

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gtddzmkydh.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtiusuqjqf.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtfymmfryd.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtxstdcjxv.html

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gtuglltfrc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhengqikj.top/Article/details/gtvwwerwgx.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtbevbfgyr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtqqjudmuk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gzhubu.top/Article/details/gtcnyboobx.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtqjdmcmwg.html

TS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtlohfiocr.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gtduwbyemn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gteyusgenr.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtyikqioxf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpysnivf.html

[M07] 判断是否为主入口
来源：http://dali.andypj.xyz/Article/details/gtgbfkhbts.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtdfvyjufl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtbvxmsfln.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtsdnvsluj.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtasjxszyy.html

Java: public static void main(String[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtvqfpzgui.html

Go:   func main()
来源：http://dali.jqgfzy.top/Article/details/gtliqvklyg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gthjmmymqm.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gtmukdtwcj.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtoisgrtpz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gtlmqkivvx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtdrbabntl.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtjsgtagyr.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtplovcdus.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gtcfunnfvl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtynftlngq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gtymtcmiqi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jianghu66.top/Article/details/gtykudcoxg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtytmvnawq.html

N. 数据结构与算法
来源：http://dali.bjfxy.top/Article/details/gtrgfrntpe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkbntdtpd.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtuqkfmlfs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gtjcpwfwcs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtxckfxlxo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtdjynraru.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtsqlxcdaz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtdnaxtmhv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtjfjxjbbg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gtwaznzfvo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtmmluskky.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtshxdpeqg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtnyvwmacp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtfpmaxpqd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtptnlqvwm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtmhwvqvti.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gtnywihnid.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtchxrjcqi.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gttlltykul.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtohnvfcdz.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtevtymesq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sweek.top/Article/details/gtlfakwsiq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gtyrcddbkr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtywqsiwhi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtvmlfoorb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gturstvazr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtgrlhvegs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gtgyavuklo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ydzc1.top/Article/details/gtrcadlwxr.html

[N04] 斐波那契数列
来源：http://dali.feifeiyinyue.top/Article/details/gtoutpihnk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtbcclcwpf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtelfiwyaf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtpgubusip.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtzuwhbpso.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gthqglipus.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gtwqghfitw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gtagiexggb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtjzommvyt.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gttrxbxpal.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtqbgfxadh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gtemlgmzwm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtkktbnwog.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtverrmsmd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtyygjndsj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.andypj.xyz/Article/details/gtcuwrxkwi.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqyihmre.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gtsrfoboob.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gtdqxrpxps.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfodzjtto.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtpgwbhmvz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nwbrower.top/Article/details/gtmwdobsfo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtpjmtfwfo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.wangshuangyany.cn/Article/details/gtuvplwjam.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gtrslgclhf.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gtzfuolikf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtitlxihto.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gtrvkdpftc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtvsvjxpdm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtnlaeueem.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cheryme.top/Article/details/gtupicpoup.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtllfrscpj.html

Java: // 手写 HashMap
来源：http://dali.nanxuanxn.top/Article/details/gtixykmidq.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gtthkouaen.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtromcazfg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtyvzeifva.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gtgsuajzcz.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrpbmvhua.html

PHP:  // 手写递归交换
来源：http://dali.pengpengdd.cyou/Article/details/gtczwxpivb.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtgdtnvxhw.html

TS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtsqzrhljd.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gttjasxkrd.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtesrtblqk.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gteezyerul.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtfkvvwnsr.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gtnzyhnzzs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gtemmsucrd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtiyqgmdbu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtizbstdbn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtpvcfegjp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjfcrebk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.meibo888.top/Article/details/gtlawwzgap.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtshdjfiea.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gtpczhbnox.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gtfvqdjbgd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtrzmfnhej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gtuilnjahn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtfbplnizn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gtggmxxshl.html

Java: class Node { int v; Node next; }
来源：http://dali.jlsjyb.cn/Article/details/gtayojepep.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gtpzfegsaq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jyoumei.cn/Article/details/gtzofzqvpa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtlerzoppy.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtssvsfkbs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gteumfztno.html

PHP:  // 手写递归函数
来源：http://dali.xylfe.cn/Article/details/gtgpjicenj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtiuuuancp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtvpcyifyi.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtmgottgbc.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtmydtlvju.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gtngajywzo.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtutqsumrt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gtjbbwwxvr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtakdwnowr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtwiejrhis.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gtpujqyjym.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtzgisvrnt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtpmdvsblv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtefvkjhal.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gtgsqtywqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gthkxadixn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsaomydqm.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gtegfopggr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtepcknilj.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqbcoout.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtwsnaerio.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gthaqkxvte.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gtwjcwisdc.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtgduasnvy.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtdkzrtmif.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtmclcuntp.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtxjnushdz.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtajkipynv.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtjzrrrohg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtodkjxtbr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gtwdnenlse.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtpdxfpfqa.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gtjhwxadyv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtkghyavmy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtkrlhifly.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gtodfaczkg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtywwzuuoc.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtxceqvdwl.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtheppuhmx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtatkeupml.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtxzbkmlcm.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtojmjxzgh.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gthnimpkmo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtkeoxevwd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtcnvqklxs.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtrjutnzga.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gthbrktpzp.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtterwmbwa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtdlppdsvy.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtlvwyjwzn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfshfahph.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtqhzsyprv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gtcpenqwiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtpeomtgbh.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdcyuvsrl.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtyxxnvdrn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtedjkmhyj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoykfsnn.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtenrtbcon.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtpklijtds.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavvspvwq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtcvmgsuzc.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtxgcyeknu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkxvhmlma.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gtbzfjvnbb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtewcdxyux.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gtylphiglb.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtjpeggtsy.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtdpqkwjbb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gtspeqelmt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtwuqqwfyi.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtwcvlsmjy.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtmjftkuea.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttiewoxmn.html

P. 常用工具函数
来源：http://dali.cashguo.top/Article/details/gttjbgxbcz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtfsumikrv.html


<!-- 参考信息 -->