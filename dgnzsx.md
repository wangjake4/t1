代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.smart0.xyz/Article/details/gt2ogpmrwte.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.gotoacloud.top/Article/details/gt2rklqrlme.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cqqwz.cn/Article/details/gt2honcyyfo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gt2zilwamjy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2hcvchrms.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.nanxuanxn.top/Article/details/gt2kafxblox.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gt2gczheieo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gt2voaiokhk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj20258888.top/Article/details/gt2ttzusqrz.html

[L04] 设置超时
来源：http://dali.bjfxy.top/Article/details/gt2hifbdbsz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj20258.top/Article/details/gt2lhyvzmll.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gt2rlwhyhjj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hywenlv.cn/Article/details/gt2jcnctyvl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258.top/Article/details/gt2ygqjllwq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuxming.cn/Article/details/gt2hprrqxsl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gt2iqrcuqqy.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dqulbovk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihxmolsw.html

[L05] 上传文件（multipart）
来源：http://dali.nanxuanxn.top/Article/details/gt2nmeihglh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yuxming.cn/Article/details/gt2yyjwiazm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gt2frufhiss.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2rednqrpj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2jddlnpdo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258.top/Article/details/gt2uiawelcz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gt2gmfyvrzx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gt2saklpjwo.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2nooxvlfr.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gt2qhsdjves.html

Py:   resp.json()
来源：http://dali.tian-w.cn/Article/details/gt2lewroeou.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gt2pgbgcmke.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2oydxkooz.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gt2dgiamaat.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gt2gcniqwby.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jianghu66.top/Article/details/gt2ldxmdnlp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zdqjudy.top/Article/details/gt2yfflflml.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zycfv.cn/Article/details/gt2uiprwcka.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gt2feuvsojv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkqrxqb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2eqrtismh.html

JS:   resp.ok;  resp.status
来源：http://dali.nwbrower.top/Article/details/gt2myonmofx.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2dtskpssq.html

Java: resp.statusCode()
来源：http://dali.tanke756.top/Article/details/gt2folrysep.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gt2bfxhqhnz.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2afajucws.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gt2ayalicei.html

[L08] 并发请求多个地址
来源：http://dali.xylfe.cn/Article/details/gt2rvtlseqc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yonumen.top/Article/details/gt2xnnvbkna.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj20258.top/Article/details/gt2ppcnqrpj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2vlutyecp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcqwnyth.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenlongwang.top/Article/details/gt2ikqllenz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzhhbfei.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2fzgcwrdv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gt2bodbtqvk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hilsfkiz.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gt2sdyhxutm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ilycxpoj.html

[M01] 读取命令行参数
来源：http://dali.iojbl.cn/Article/details/gt2ulpgzfcs.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhccpuca.html

PHP:  $argv;  $argc;
来源：http://dali.tian-w.cn/Article/details/gt2atligjqd.html

JS:   process.argv.slice(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdoibnob.html

TS:   process.argv.slice(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhradmuf.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fixjnynb.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2karjtfzj.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gt2dkxdjuvr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2pzqbdelk.html

[M02] 读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2tolkkhzl.html

Py:   os.environ.get("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2kiqvdvgk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.nanxinkj.top/Article/details/gt2zykvhbfl.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jprohttb.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2gedmnqkf.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2kpqsbuqs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2byptielg.html

Ruby: ENV["HOME"]
来源：http://dali.yuxming.cn/Article/details/gt2khrxfugq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2nkpiuyim.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gt2sqbgkifc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrswahts.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2wfzcbksc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.pycfn.com/Article/details/gt2yofskkar.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gt2uwvnuykt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltqopcdc.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shuidangran.top/Article/details/gt2hqgbdcto.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ybcxt.top/Article/details/gt2wyvjhlfk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2thhdtyes.html

[M04] 获取当前工作目录
来源：http://dali.jlsjyb.cn/Article/details/gt2xvbwgpva.html

Py:   os.getcwd()
来源：http://dali.haohaochexian.top/Article/details/gt2zqrzddse.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gt2vbhahtpt.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gt2kgoxndyz.html

TS:   process.cwd()
来源：http://dali.ybcxt.top/Article/details/gt2ulahylog.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2gcvdgvol.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uykdldaa.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gt2fnkdvize.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgufenzy.top/Article/details/gt2tdqpjyfs.html

[M05] 设置退出码
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfqvtgfm.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2bndmaqdz.html

PHP:  exit(1);
来源：http://dali.ivvv.top/Article/details/gt2eircujtq.html

JS:   process.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2gjccmcyr.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2yzdjvowr.html

Java: System.exit(1)
来源：http://dali.birdmap.top/Article/details/gt2wfvvosrw.html

Go:   os.Exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2qifaadzo.html

Ruby: exit 1
来源：http://dali.gaohongyu789.top/Article/details/gt2mshjktte.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybacgjlp.html

[M06] 向标准错误输出
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkookqrp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2ldcbelnv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gt2dufoibfr.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gt2zsumjztf.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2lticrdnj.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gt2caxtypog.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxinkj.top/Article/details/gt2ixyjcfew.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gt2syuqajiu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.iojbl.cn/Article/details/gt2okxcbyle.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gt2bjkvgyds.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gt2tebjrndw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gt2rgddyaex.html

JS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2nyyvaqlu.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gt2zseibnqq.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2mapqrmtj.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gt2usqaccle.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gt2ngdnadzi.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gt2pttspvro.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbaniyd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2zwvpgzag.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwyajoqi.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2dpvhlwlz.html

TS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2eqzmzkos.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daria6918.cn/Article/details/gt2qsifkanx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lixvvvvg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258.top/Article/details/gt2pbswdkry.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zycfv.cn/Article/details/gt2gpsvmuev.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2cxikslfi.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gt2iidkjkxg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2iejaamos.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2loiepzrr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2xnxolbip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2jehrjcsh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gt2kviigreh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gt2iyvtchnx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2gittsiot.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2opegvuzo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2zblufmwa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2ziqxoore.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2zmwmssjh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gt2bscumlxg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulngpczv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2khaxzlgd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2toytsadj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2srfghwue.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2vjxcbxif.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gt2hvhpbccx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2wtnfezzh.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evymantw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jbgkmquw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gt2queugmdz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2aqkfchpz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gt2udiuwltg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gt2qyqftyqq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gt2ziulwals.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gt2zaowlnbp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gt2gbmczqbt.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gt2tcelcozr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gt2nfjajzlm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2afvuoxfj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2xjzecpsm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2bzqasegm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gt2cujyxnex.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yongpay.top/Article/details/gt2orbijsqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2ckwbgdst.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2ostvafxg.html

[N05] 最大公约数
来源：http://dali.shzxlz.cn/Article/details/gt2dguhbmlw.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2oyxzhzxc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2ndtrdrcm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gt2crdmdcfu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zyqvwojl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gt2eqclohor.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gzhubu.top/Article/details/gt2jxgduvgv.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gt2yftjzdbv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vgzajpis.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2tlksmhjj.html

Py:   s == s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gt2pondualr.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2wbcbpjnh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2xuwpocsm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gt2jqegnlep.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdapzgir.html

Go:   // 双指针从两端比较
来源：http://dali.zycfv.cn/Article/details/gt2corupkef.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2fuhwulkc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2egzyxeya.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gt2zkndjcmw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gt2tolstpnx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenlongwang.top/Article/details/gt2whcarwld.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.andypj.xyz/Article/details/gt2vxmsjszp.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywjplmlq.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gt2sywaxyvi.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gt2whutnist.html

Ruby: // 手写 Hash
来源：http://dali.aibaodan.cn/Article/details/gt2lvcbjmae.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhixingplan.top/Article/details/gt2dwlgrvqp.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gt2uetybpde.html

Py:   itertools.permutations(arr)
来源：http://dali.yj202588.top/Article/details/gt2fsihnxhc.html

PHP:  // 手写递归交换
来源：http://dali.meibo888.top/Article/details/gt2whiwgcll.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2homzfony.html

TS:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2broptajc.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2ceussmxb.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2lppwazym.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gt2bkkjtgvn.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2vrctlvcd.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ceqhuyoi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aflgicde.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2iymybtkv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2iaayqvqd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.0kj1m.cn/Article/details/gt2wzdlypqm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gt2utppjwlp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gt2xftpsulx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2qmerrdpq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2gafcoqjp.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gt2hhokbphk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2okwosuqi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gt2qpdtblsg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gt2dzmspgfd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnqzz.top/Article/details/gt2ufwrtoym.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gt2qcophtpr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gt2bqxnwrrt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gt2wjwvwqcm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2harpuhxl.html

[N11] 二叉树中序遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xbkvbfal.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2wmnxafos.html

PHP:  // 手写递归函数
来源：http://dali.zhixingplan.top/Article/details/gt2eywprsay.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2bxejgfqk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2brfktgie.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2fjweqgga.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2nvpynkov.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gt2ahfjnwtu.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2jvvonubj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpromhzy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gt2jnoiiwhx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gt2ixqugyck.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gt2mpvepzrk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gt2xcgdxgbd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gt2fuvjkzkv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2jwexpscd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gt2awcjhljr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gt2azbvmlkw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvmogrzx.html

O. 并发与异步
来源：http://dali.ehwqpu.com/Article/details/gt2ebzvmhjt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2xjxvurmg.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gt2irasyhxq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gt2lyffrkhd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jyoumei.cn/Article/details/gt2qhdkwmfu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbplrdfg.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gt2mvdbfelv.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2bikfrdco.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gt2dbhnayea.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gt2pjxksepu.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gt2rllqxlqe.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gt2ahcfbfnq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gt2bimaqxuu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2xjykqvjl.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdhujllp.html

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2vcsszxzu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2ficihyuu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjjonjsd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2ixqasulg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfqytcui.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gt2cmbltfhc.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gt2mkhgqfhv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gt2hetzgkpr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gt2qvqgzfgp.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gt2uruvfzab.html

Java: synchronized (this) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2jzbfgsfb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2dvepirpc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2htotkngp.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2ipjbiuhb.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gt2plildulr.html

Py:   async def f():⏎    await g()
来源：http://dali.cucudq.cn/Article/details/gt2nlduhose.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgufenzy.top/Article/details/gt2rrxfwxgt.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2psoqxwol.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2bgkgzkts.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2lbmrjtfr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gt2rbiinrcw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gt2kyzyuwgw.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gt2oibsrgid.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kmgayifv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gt2cmzmwjqp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gt2ekkejpjg.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2yvoaoybx.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2kghehpik.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gt2ewdwxdvu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2gadyzsso.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gt2eiynjwhu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2ffdqmrhd.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gt2kvozsyxx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gt2ltnjzpbs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gt2grokzjpz.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2dhtvmaeb.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2lrlsiimh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2kxwnoswr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkwtgslg.html

Ruby: // fork 块
来源：http://dali.guowangkeji.top/Article/details/gt2ulytuted.html

C#:   Parallel.For
来源：http://dali.yuxming.cn/Article/details/gt2fhmzphna.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2uvcesmis.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gt2attpifij.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2adqdksdt.html


<!-- 参考信息 -->