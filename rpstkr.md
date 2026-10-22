代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.tian-w.cn/Article/details/gtxxivkqyr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gttyxzzubf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuanzx.com/Article/details/gtischbdhc.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhiwuduotai.top/Article/details/gtnwresfwx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtjvysvvsn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnycfhimf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtafepqgvt.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtwevfclyx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gtyjsnzfga.html

[L04] 设置超时
来源：http://dali.tianlin.xyz/Article/details/gthdvrwpel.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dianchejie.cn/Article/details/gtvttxwvlv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guowangkeji.top/Article/details/gtnebugxry.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtgaaktkfo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtwdcnuhie.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gtmvbfrqgd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gtxqtmccbq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gtfdtttjka.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gtnctzmuxp.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gtqksmdefm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.birdmap.top/Article/details/gtxkjcwnji.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenzaomai.com/Article/details/gtqcpanxno.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtitmwmkaq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnygmnqhb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jqgfzy.top/Article/details/gttqqozwwg.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtopevzvch.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtrqffwwim.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtrzkxueos.html

[L06] 解析响应为 JSON
来源：http://dali.hammf.cn/Article/details/gtndjuiqhd.html

Py:   resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtoqddpczr.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gttlwazyna.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gttftctryw.html

TS:   await resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvbiedfe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnqzz.top/Article/details/gtoswtqpmc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gtfexjkwie.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hammf.cn/Article/details/gtmftfvwrb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shzxlz.cn/Article/details/gtdgfuzrlf.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gtgkshapzo.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpyxqufk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shuidangran.top/Article/details/gtkkfthqzk.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtehltzuhk.html

TS:   resp.ok;  resp.status
来源：http://dali.yueranfly.top/Article/details/gtgyrsesgh.html

Java: resp.statusCode()
来源：http://dali.nanxuanxn.top/Article/details/gtwnewwbva.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtfslafzhw.html

Ruby: resp.code.to_i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeqpbdzl.html

C#:   (int)resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtiodtxjvc.html

[L08] 并发请求多个地址
来源：http://dali.ehwqpu.com/Article/details/gtlsilqhup.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gtuknxbdeu.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gtrkxbaffs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtiodbbgym.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtpfxpswiw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shangyingyoupin.top/Article/details/gtzfbhtvwp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cdnleiting.top/Article/details/gtqkgzrbbq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuxming.cn/Article/details/gtgyyspxfd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtyqgsmtqr.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnyzidybe.html

M. 命令行 / 进程 / 环境
来源：http://dali.gaohongyu789.top/Article/details/gtmqbnkfzc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmapeqcsh.html

[M01] 读取命令行参数
来源：http://dali.c1oappe.top/Article/details/gthisyqoxo.html

Py:   sys.argv[1:]
来源：http://dali.zycfv.cn/Article/details/gtcaemmkie.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwinjlwpc.html

JS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtanhjqodl.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtxfnwthxa.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gtbjbasttc.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gtwzgxdloy.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtkihkidlx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovjlyaai.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gtgqrxgode.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtfmpvceeb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtpmebohkb.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtgbjitgbn.html

TS:   process.env.HOME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrkjnuzs.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtyfagstgk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtnwbgacfr.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtlrmxdeyh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ydzc1.top/Article/details/gtewiguofn.html

[M03] 执行外部命令
来源：http://dali.sweek.top/Article/details/gtdinmvcui.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daria6918.cn/Article/details/gtowyoascj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.bjfxy.top/Article/details/gteywslhsc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gtxfaonbhi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtclvbxzix.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtvpuztifm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jlsjyb.cn/Article/details/gtkdyzhimt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gtadmuqpan.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtvsdsqtiv.html

[M04] 获取当前工作目录
来源：http://dali.guowangkeji.top/Article/details/gtncoxfvhd.html

Py:   os.getcwd()
来源：http://dali.yj20258.top/Article/details/gtjvsueonf.html

PHP:  getcwd();
来源：http://dali.haohaochexian.top/Article/details/gtllmjzfkc.html

JS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gtkvvawfkp.html

TS:   process.cwd()
来源：http://dali.jianghu66.top/Article/details/gtrzhmbbdm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtchlbevos.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfdsoxjf.html

Ruby: Dir.pwd
来源：http://dali.ivvv.top/Article/details/gtjwvmvsus.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtqfzkivzv.html

[M05] 设置退出码
来源：http://dali.cucudq.cn/Article/details/gtbwlnuszq.html

Py:   sys.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtausljdoz.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gtghywxrru.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtaydxofla.html

TS:   process.exit(1)
来源：http://dali.sweek.top/Article/details/gtxjtlicbe.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtrhrclofu.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gtirgiblji.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtbhhafhiu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtyrrvotyc.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtjqctxerk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtuhysxdlm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gtyfrnnmvy.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtvrvnmyrv.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtxqbsplkq.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtdlzyompo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gtxrnefzmi.html

Ruby: warn "err"
来源：http://dali.hnxiangtu.top/Article/details/gtjtuufbpm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtgojbklqw.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtaradojqz.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gtoskmrpsy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnqzz.top/Article/details/gtaeiydvwc.html

JS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlveiqpld.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtqhrolmyb.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtzqajssib.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gthvyxjuaz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gtvxszetbd.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gtiixdwoam.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtfsoqikgu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gtsxbkvrmv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtuhvghawh.html

JS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtehxpvgou.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsffthny.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtwevdilzl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtbmkmonkm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtrceffxdp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tian-w.cn/Article/details/gtbgusjsrl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttxvwwwsg.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtrdvhmeat.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbxaybbfg.html

[N01] 二分查找（有序数组）
来源：http://dali.jlsjyb.cn/Article/details/gtobnfwojf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gttxdijiyk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gtinynqagh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gtewcatfui.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtiixbcqjc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtxoqqfvht.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtbdkddevz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkxmoqsw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtabgcuyev.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhwyrxul.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gtiztydliv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtkpxrbksb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtdmjvckgf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtddgnvxtc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtchmhkgxa.html

Go:   slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtrubalisv.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhvssyzj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jianghu66.top/Article/details/gtijpywusw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhoulong.xyz/Article/details/gtfatrcvxr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtpbiklmoi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtktyvycyy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtxiazpbdm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtwqzbjpvr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.iojbl.cn/Article/details/gtmsuaiehx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtbbyvbtqg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtfovirzec.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtdlngdjtr.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtnfxreftj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtkozmmftd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtqwkzopmo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtnrsodgyn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtfwisgknp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtzamdmkne.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.iojbl.cn/Article/details/gtittaxylp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuiwiahv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtxkjlqtep.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtfdhxixlu.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gtikyrnzmf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjiyzobc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtzqcbolps.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hfpthk.cn/Article/details/gtdifnwbof.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtblfforlj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gthvnkjcus.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtfgzltfym.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhengqikj.top/Article/details/gtbepqrnel.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtvungsien.html

Py:   s == s[::-1]
来源：http://dali.yueranfly.top/Article/details/gtjmbjnrfc.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtweqynjvr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtivddxerm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtnffhqzff.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtaerdivjw.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtrqpxqbxn.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtkolglawd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gtacgzftrm.html

[N07] 两数之和（返回下标）
来源：http://dali.cucudq.cn/Article/details/gtqkznemid.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtyrusxavc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtgzqgvbhv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gturhqzgna.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtgzvsvcrp.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gtbqlgbyfj.html

Go:   // 手写 map[int]int
来源：http://dali.xziqi.cn/Article/details/gtpusofdla.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangtech.top/Article/details/gtndqufmkk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hfpthk.cn/Article/details/gtwpgupjus.html

[N08] 生成全排列
来源：http://dali.ydzc1.top/Article/details/gtyiajluux.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtkwcawqvb.html

PHP:  // 手写递归交换
来源：http://dali.hnqzz.top/Article/details/gtzozhuufk.html

JS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtfqejvlyw.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtobaejija.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtuhvjwxar.html

Go:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtdkfzywlo.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtsrbsjuzq.html

C#:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtpznjtkbr.html

[N09] 栈与队列
来源：http://dali.iojbl.cn/Article/details/gtqblyjcpi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gtugcndpii.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtajbktyet.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtsovcesug.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gtdjdnjlqs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtbzjtdxip.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fzhhl.top/Article/details/gtkpxrqycz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtdaklbrul.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuanzhike.top/Article/details/gtgljhwslv.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtiwecsoet.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gtltepkpte.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtpoxizbrv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gtlibkiypp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtfjckpequ.html

Java: class Node { int v; Node next; }
来源：http://dali.svipenyu.cn/Article/details/gtdgkmxuwa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtkxawomjl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hysaishi.cn/Article/details/gtclfnljgr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtrmokiguj.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtxekigcmp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtjgfxpqpt.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtpunhmtgk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtbuoctvwb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtaiqmxeoh.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtcvgaayqa.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtngbbdths.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gtdxhshzjp.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtrzycmqrk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtzuplncnl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtdxpajkip.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yonumen.top/Article/details/gtutvxgyhm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtkcezuqtv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdmbslcb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtzwfspqlj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrhcntcy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiqwzpou.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtcypfjrcj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmoafvmqq.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gtvuyfbgtl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmwodmmfp.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtohkprglu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtypmqnmuw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtumnhmlij.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gthybdfbyv.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gterygneho.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtoflwocxi.html

Go:   go f()
来源：http://dali.zhixingplan.top/Article/details/gtslfvvhcj.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtvfomxebn.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtvbedtgyu.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtepgbcbvb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtxzxwrmhx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtomluswcl.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gtclwxjjxh.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gtpdvebojo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gtkrhlcinl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gtfncmvlkh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gttcirghvj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtajprzsed.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gtbonxvpgk.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gtstdiroho.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtgmlzqoxs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtltjxxoth.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtzdutotvd.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtgskfrkee.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gtgbnsguad.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtbdervkoo.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gtpenwuwex.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtxguoeufs.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtbzllxuil.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtobpmxfji.html

JS:   async function f() { await g(); }
来源：http://dali.pycfn.com/Article/details/gtnnhcckhc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmahsxhkj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtdggujggx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtqzvkzhaq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvhsbtip.html

C#:   async Task F() { await G(); }
来源：http://dali.vqdsnc.cn/Article/details/gttiiluecl.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtufdfmoyt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gtysgeiday.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtbzumjnhg.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtnjrswdfm.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtarbcynmp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gtxxxmcorh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtoqzoiikp.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtblwqklbh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtcmfiklkk.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gtenxwdfdg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gzhubu.top/Article/details/gtqoykokzp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.meibo888.top/Article/details/gtaunuvyxk.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtaqxqshjs.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtiurycgne.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtvewyeznv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtinujaeeo.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gtfnyizefl.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gtuzagvitk.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwyzwtddi.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtzvmnqapi.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtbooqzuxw.html


<!-- 参考信息 -->