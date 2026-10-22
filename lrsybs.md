代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.chenzaomai.com/Article/details/gt2lhucnoru.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jiagoushi.top/Article/details/gt2uuruibmu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hfpthk.cn/Article/details/gt2qfcfmchu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenjidiqi.icu/Article/details/gt2aysstpri.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhengqikj.top/Article/details/gt2mqpakrjt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sysykeji.top/Article/details/gt2ewxgdzmp.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oucivgga.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.snrcjt.cn/Article/details/gt2dqspdhms.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yuxming.cn/Article/details/gt2igcvglfj.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gt2fqywogzd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2zhektjxa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ybcxt.top/Article/details/gt2tfqqfrmq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jianghu66.top/Article/details/gt2kxsoaqjd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gt2blhosblo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gt2acsnhiiz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shuidangran.top/Article/details/gt2jmejcjjl.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gaohongyu789.top/Article/details/gt2xisongvk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gt2kjusjftn.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gt2ustnvuoc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yangfankeji.com/Article/details/gt2xbsxouzh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrpytqlf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cheryme.top/Article/details/gt2jwzctdrz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.quarkkingdee.top/Article/details/gt2ddcqugfq.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2npxunoow.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.vqdsnc.cn/Article/details/gt2gtkzpfwp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xziqi.cn/Article/details/gt2ufqxpmtr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygfxadtr.html

[L06] 解析响应为 JSON
来源：http://dali.redwolf501.top/Article/details/gt2kjncmage.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2vacfilde.html

PHP:  json_decode($body, true);
来源：http://dali.yvedp.cn/Article/details/gt2iobjmfvl.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2xwlhrrwu.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2wyxsjoab.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2wsuvdpyd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.pycfn.com/Article/details/gt2imiulshz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yangfankeji.com/Article/details/gt2mnqskgde.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2lmbaahcz.html

[L07] 处理 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gt2gbbtcchu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gt2lyfyslxb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnupephq.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gt2kegdezob.html

TS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2yepdiupl.html

Java: resp.statusCode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvijvcrw.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gt2ldlvpxep.html

Ruby: resp.code.to_i
来源：http://dali.zycfv.cn/Article/details/gt2hyukmeuv.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2qhzydpse.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbkscsxa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258.top/Article/details/gt2ewbymflo.html

PHP:  curl_multi_init() 系列
来源：http://dali.andypj.xyz/Article/details/gt2syibsdxw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ydzc1.top/Article/details/gt2yricojyj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2ddweqdun.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gt2qlxmqqbp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj202588.top/Article/details/gt2xekpckfe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2xhupxjqv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ehwqpu.com/Article/details/gt2luzmbdyv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2jvpttjzk.html

M. 命令行 / 进程 / 环境
来源：http://dali.ehwqpu.com/Article/details/gt2itawyqod.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2savehkqg.html

[M01] 读取命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2qwgdjmzk.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2baoteaoj.html

PHP:  $argv;  $argc;
来源：http://dali.smart0.xyz/Article/details/gt2kaokeenv.html

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2aiasnlwd.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2tfcwkjeb.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrtgsezv.html

Go:   os.Args[1:]
来源：http://dali.meibo888.top/Article/details/gt2kyuksclh.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2tkdxxsbk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2nmqkkzjq.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2rodcmnmd.html

Py:   os.environ.get("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2wsnmveew.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2dyheholm.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gt2ufmarlwq.html

TS:   process.env.HOME
来源：http://dali.haohaochexian.top/Article/details/gt2mlgwuviz.html

Java: System.getenv("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2hajjejyv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2kvqusabg.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gt2jvsiikmr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2bahuhuga.html

[M03] 执行外部命令
来源：http://dali.gzhubu.top/Article/details/gt2yojbckpz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sweek.top/Article/details/gt2stmxzlaj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.andypj.xyz/Article/details/gt2sokeoxzx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2mngnhzjm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xylfe.cn/Article/details/gt2eugcvfbe.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2yayznkao.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gt2viiiamha.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcqhetge.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gt2wgncubuk.html

[M04] 获取当前工作目录
来源：http://dali.dashuyun.cn/Article/details/gt2sgajavld.html

Py:   os.getcwd()
来源：http://dali.sysykeji.top/Article/details/gt2pijtablc.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gt2lolyxigc.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2adioluvx.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2tqlrvkqr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2iupgpjlg.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzmpgeob.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gt2pzozzefn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2hxzcgtnq.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qodohipq.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2zowavbja.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2hpsugryt.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stucvqdc.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2nafzumaf.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2dqhxfybk.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gt2qvvmgndy.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gt2pidnhzkv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gt2sjgwfgmd.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2duoacrlq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjfwbxpw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqlmdfdh.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2dajvwerp.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2qotevptw.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gt2qgtzpqgp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ydzc1.top/Article/details/gt2itauyvbj.html

Ruby: warn "err"
来源：http://dali.jlsjyb.cn/Article/details/gt2wjqezyhf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gt2uwnsmhqi.html

[M07] 判断是否为主入口
来源：http://dali.hysaishi.cn/Article/details/gt2ilzmxxiv.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aqlkjjjg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gt2xfothwip.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkxbelwi.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnrqjstx.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2gjuhpzxp.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gt2jsvlqdot.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2itsejhbk.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2ifiavalq.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2stiqllha.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2stnhdbko.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2mdkmupiq.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2lfuykrhw.html

TS:   process.platform;  process.version
来源：http://dali.wangdashe.top/Article/details/gt2zlutixeb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phgaqnxq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xylfe.cn/Article/details/gt2vdwddtau.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gt2rdjimhgs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2vfzeevhj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2fxgxuptj.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gt2ghmkqfww.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ormedngn.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gt2tgmxlgwd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2xzmlowam.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2mxpphdus.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gt2zsryrwee.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2uouvcsan.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2cfkqkvnw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ujhjlktk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gt2ivcilgso.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2iqvwdfyw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgfzy.top/Article/details/gt2szuhegzu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gt2ovxwbosh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gt2nbdkjala.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2iflkhjgg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2aqflonip.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdrnkgnm.html

Go:   slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2hahwrofq.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmocpzpz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fguvawxd.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gt2slliadvp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gt2cizucsju.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gt2pgrcqula.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gt2wnzhapxn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2dqhopclx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dianchejie.cn/Article/details/gt2udfpdzuv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gt2chtvefzi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ecifnmqt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gt2ubeeaane.html

[N04] 斐波那契数列
来源：http://dali.zycfv.cn/Article/details/gt2qsxnkvdz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2sddhjfbw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2kvodpepk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2emnfnrpq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clhemwga.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gt2qoqznjmy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybjtffio.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2btjsfxoj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2rifaibgq.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gt2jgehduyi.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258.top/Article/details/gt2qtfbfzak.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2txgajlur.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2jxovmnmt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2ttzxozpm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gt2qfgdkeka.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gt2zfeyrzpl.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2wzohtxkl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gt2inbaucjp.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phvuajcd.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kaprwrvk.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2ogvfyfao.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2yixqggsw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2plijyejp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.daxiang520.top/Article/details/gt2whbzvjvf.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gt2crndzhmp.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gt2xvslepuo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2ckxbspss.html

[N07] 两数之和（返回下标）
来源：http://dali.gotoacloud.top/Article/details/gt2lgbobemq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gt2sdujejpl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yanxiufei.cn/Article/details/gt2wzjlsajn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gt2ictfwgpp.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2xcdupjpw.html

Java: // 手写 HashMap
来源：http://dali.tian-w.cn/Article/details/gt2xjayjihz.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gt2iguwtsym.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2hktbvdsw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gt2hodhiknw.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gt2dshsrwex.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cbykrzds.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gt2xgemzjix.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2dptlvwya.html

TS:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2bbshphzt.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2kymaboqj.html

Go:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2tehuzydn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gt2swuaakqd.html

C#:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2glzzbjrt.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2kyxrmfur.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.iojbl.cn/Article/details/gt2kevszidb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tian-w.cn/Article/details/gt2kxngeoyh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2mkxdypja.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gt2xgvsaizl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2uxmpvccn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gt2mkdeoxlv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2kjrdwbyy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gt2nkminacv.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gt2krxtxgrp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gt2rxaefxdi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mtowkkmj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aezrogon.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gt2rxpsysgv.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gt2afczgbsg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gt2pbccnhfd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gt2ndubviel.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nlfneqaf.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kslqhgru.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gt2uuhffbez.html

PHP:  // 手写递归函数
来源：http://dali.hnqzz.top/Article/details/gt2fuvyisqc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2agufwtdw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2cihnpoga.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gt2gnnhcaja.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gt2lgycfrfs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gt2ocfaojzj.html

C#:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2xaunjikf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gt2yfcypdzk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.guannengcc.top/Article/details/gt2dufhtnml.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gt2gkfjipoo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gt2wyyqqcww.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2lbpjnyoj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gt2afcmtnjr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2cqencqta.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2gvsiphjv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2trdiiboq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mxoetxve.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2yxlughkl.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vdacustg.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gt2sksknpmr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gt2hsdrgiuk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gt2svmterzu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xziqi.cn/Article/details/gt2jkkmjzvc.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gt2sastxtgm.html

Java: new Thread(() -> f()).start()
来源：http://dali.gzhubu.top/Article/details/gt2jwidvapz.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gt2qgmdnyih.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gt2bedgnzke.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gt2mpebcjfe.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gt2zogxnkpq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxfhnhzu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gt2swmllrhs.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2murpqatm.html

TS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2gdssrwym.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gt2bwkfgnsl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gt2zhsxrilj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gt2badukwyv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trwjgjqv.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gt2eaqipsdy.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gt2fxeilgcs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gt2jvwywkxr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gt2aztxadij.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2xwwyrhjb.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2pyteqlpy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gt2dhljhoap.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2extezbya.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gt2ecjwdmkm.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2htzolnoa.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gt2qcukkkzw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gt2izyfgldz.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ubggliak.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2wzviqyxc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2unpbrjip.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gt2hqjnjfus.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2ikqlzmyw.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gt2eqsxopyl.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gt2mpnjuqpy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gt2qjbcnewy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gt2qevrvrei.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2xckchbrd.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2chxdgqdj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gt2fpovfhkb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gt2ugyontqs.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gt2dnqtpdra.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gt2laptaffd.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gt2bheuzybs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gt2miagwnni.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gt2tdundhva.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2sazvfeki.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2lcaeasjt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2ezmlcdfg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2eqbwefwo.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gt2enoabisg.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2jejspacr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kavkfozc.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gt2mzawjifo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2pigozdnm.html


<!-- 参考信息 -->