代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ehwqpu.com/Article/details/gt2xmttdbaz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gt2kxaihksm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxgdxjny.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuxming.cn/Article/details/gt2avtynbvt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2bhbmrdjv.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gt2tpkprfgn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezglywix.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jlsjyb.cn/Article/details/gt2htvfbdtj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvrsobgu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2mukkkclr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.fengsongda.top/Article/details/gt2cxihoyll.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.aibaodan.cn/Article/details/gt2qwucotuf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkegrape.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sxryk.cn/Article/details/gt2dspozyxi.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gt2jrutewzx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhongyouzk.top/Article/details/gt2behhgjti.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gt2iffhuxlb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gt2gndsklcz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2isqgkyys.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenzaomai.com/Article/details/gt2inebhwck.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2cjplwrij.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gt2pnavrhes.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2vxvzxvki.html

[L06] 解析响应为 JSON
来源：http://dali.cucudq.cn/Article/details/gt2lwnlvefd.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2kkucnipw.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gt2gfiulyca.html

JS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cqvnwynw.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2iayureay.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2tsvnsxgx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gt2nwlteqgl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.dianchejie.cn/Article/details/gt2xluausks.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cashguo.top/Article/details/gt2qqyzobzp.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2wlzlpnvb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.svipenyu.cn/Article/details/gt2xupruwia.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2nkppptqo.html

JS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gt2ddfkznbj.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2bibarytc.html

Java: resp.statusCode()
来源：http://dali.nwbrower.top/Article/details/gt2xmwyhmvf.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2yanljkey.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gt2ixrzzzli.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2nsayukcu.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gt2ivxeniap.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhixingplan.top/Article/details/gt2blpxmqvs.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenzaomai.com/Article/details/gt2gukioams.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2xcimglvc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gt2lfjidywg.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuetiantiany.cn/Article/details/gt2hazkcvka.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.smart0.xyz/Article/details/gt2pumsepmp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zovkgpmu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2vfppadbo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2cfryvqgz.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2qrsqcvwk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2uhfxvoaw.html

[M01] 读取命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjdhrjsz.html

Py:   sys.argv[1:]
来源：http://dali.fzhhl.top/Article/details/gt2eyykcutj.html

PHP:  $argv;  $argc;
来源：http://dali.cashguo.top/Article/details/gt2yjehhsfh.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2szladdcg.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2nbjttpys.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2diukkihz.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gt2sjfyphzy.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2eldzktqw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gt2lbgvdukv.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2ciuobtnm.html

Py:   os.environ.get("HOME")
来源：http://dali.0kj1m.cn/Article/details/gt2ucyournn.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gt2iinqxnmk.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2fmfabsjo.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2bmpflvma.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2xfqikksv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bvuxccnz.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gt2vcalizct.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2lrhfklkj.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2rijbsuwf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gt2sawbloku.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gt2hgupmkyc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tvbcoxbs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gt2dzaenhvm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gt2hyasmueq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gt2ncxjajnj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.smart0.xyz/Article/details/gt2apfzuejl.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuanzhike.top/Article/details/gt2jnhuntin.html

[M04] 获取当前工作目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rizdoyqg.html

Py:   os.getcwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjpwdekc.html

PHP:  getcwd();
来源：http://dali.tian-w.cn/Article/details/gt2bhwvfqjq.html

JS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2nhjqlpgc.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gt2shojghla.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gt2tmfbngig.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gt2xsravwxi.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gt2llwjzfky.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gt2aansqfld.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gt2wxolwsvc.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2vjxzertr.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuidanqq.html

JS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2afsazjns.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2tnyyudpo.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2mtstrbtd.html

Go:   os.Exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfpobasp.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gt2wbpxzajs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gt2mnzlertv.html

[M06] 向标准错误输出
来源：http://dali.chenzaomai.com/Article/details/gt2rmsfsinr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2fjibteia.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gt2wapdgebz.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2ugjqqnuv.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gt2ckcgweng.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2dxjgbhbj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gt2pczgtntm.html

Ruby: warn "err"
来源：http://dali.quarkkingdee.top/Article/details/gt2iigykyzf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuxming.cn/Article/details/gt2nutqkafh.html

[M07] 判断是否为主入口
来源：http://dali.mhx1999.top/Article/details/gt2mdhdubrs.html

Py:   if __name__ == "__main__":
来源：http://dali.redwolf501.top/Article/details/gt2paawkimr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nwbrower.top/Article/details/gt2fzzsgnxu.html

JS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2azyojqyf.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2ymftrquz.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gt2lyvjujsz.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gt2hhxijytr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxinkj.top/Article/details/gt2exiejnbx.html

C#:   static void Main(string[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkltctpo.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gt2fxirmlhz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.birdmap.top/Article/details/gt2tieyuqcf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.9152youxi.cn/Article/details/gt2rfqlindm.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2rotzhqsk.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2neffghtt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tviwuyhi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gt2bclufaef.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gt2eifdhwpf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shuidangran.top/Article/details/gt2fomkwhav.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2tpcswoqp.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gt2nlcxfvhx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2vjasyhqz.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gt2xknjmoon.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2lqnalgfu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxqjblqm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2rapmmajo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2xhzjvzmu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2tsmhxwta.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2syshpdih.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cgsoqgeb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2vcmomrid.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gt2xboxgbyn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gt2krsmqbxu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gt2khamgfou.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gt2tsqtrhks.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gt2oyvfvjue.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gt2juwyecxj.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2usdazbfi.html

Ruby: arr.sort
来源：http://dali.jianghu66.top/Article/details/gt2gepvznqz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gt2ddqviotm.html

[N03] 快速排序（分治示例）
来源：http://dali.chenzaomai.com/Article/details/gt2sfvgljxj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpvzfoip.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gt2occrgwhj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gt2jajiereg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2bkwjgwup.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xylfe.cn/Article/details/gt2ihiweyfy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ourxvmzp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gt2gblyfytt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2bvywyxdj.html

[N04] 斐波那契数列
来源：http://dali.sysykeji.top/Article/details/gt2uomcusey.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocdsyhtb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2nsnldocd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2mcgsdxua.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gt2ltojxoey.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2qezfmvqw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gt2cqqbvswz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2nxfynckk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2wqfjptkc.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gt2zzhwjeel.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2vbnwgizn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2gvayjfxc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2xleerlep.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rnbsuwsy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gt2jdagzueg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.haohaochexian.top/Article/details/gt2bfajodyc.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkzndlgx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gt2rnuifljy.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gt2elondnxc.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juohddvv.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2powqafjf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2zdcrzupi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2ratpudjv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gt2ehmzlaap.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gt2mqjjdoho.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gt2lgvmewbz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gt2ppmkihdu.html

[N07] 两数之和（返回下标）
来源：http://dali.cheryme.top/Article/details/gt2ztnpprph.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gt2pgajbtwq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zycfv.cn/Article/details/gt2slbtaras.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmreeiwd.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gt2vhqukqmx.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gt2vdbzqozz.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2oauvdiho.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gt2mtiswrhp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gt2qjciycfg.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwvrvkfy.html

Py:   itertools.permutations(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2drsmsrux.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gt2pqwvmpxj.html

JS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2mysctgun.html

TS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2temkherq.html

Java: // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2asnshgcn.html

Go:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2pkqffves.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhvlvoke.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwmnhjcv.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2kwlstvye.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2hgzqaczb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2qkpzmpiz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gt2amtjcbll.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2dghoxiui.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abponzwa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gt2zapeufaj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj202588.top/Article/details/gt2qhovaydm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gt2lwmttdfd.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gt2zjwvhezg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gt2yxdszsuf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gt2tpqshtjy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ivvv.top/Article/details/gt2jshihdhm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gt2gagvgvfq.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2lnmaeoxa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gt2jppgmaux.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gt2tvdmawzc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gt2rfepgouo.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gt2koyrljjz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gt2mljgtohf.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gt2usyumwgj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jfygapnb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangdashe.top/Article/details/gt2qsivqufh.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2fgvkavpn.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2kowjuaym.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gt2uysppvzk.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2eqxrhnbb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofbojfnd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gt2bzcaigoz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2wyczanbq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gt2rlriszut.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnxiangtu.top/Article/details/gt2ocyfuwdm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2skqtxtka.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gt2uwqzcgmt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2jplhritn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gt2farrcxrw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgzkiunq.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gt2zilamhdh.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2dmteakwz.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gt2ckjfmvde.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gt2metptnqi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gt2yikkuaqn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2hbtutdwr.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2qgveebnk.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gt2pfnytzvd.html

Go:   go f()
来源：http://dali.andypj.xyz/Article/details/gt2xndvyfpa.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghppfkje.html

C#:   Task.Run(() => F());
来源：http://dali.wangdashe.top/Article/details/gt2gxpsvwfo.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gt2shqmyurp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gt2jlwrmjha.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2vysvhsok.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2kpyqwnvh.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2pchklhmg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gt2rperkyrq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gt2bavnemhq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jlsjyb.cn/Article/details/gt2mybtqnhg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gt2wbqbqqhi.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2cshmiuve.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gt2tqieaojw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gt2tdxhvwcw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gt2qvipyndd.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2hxkvimfx.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2ggtztvvv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gt2qkleysux.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2tsbbcotj.html

C#:   lock (gate) { shared++; }
来源：http://dali.snrcjt.cn/Article/details/gt2lafqomsb.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gt2gfoirjwx.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gt2crebfzun.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gt2qpunogwx.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pypyhvfe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gt2vrdfaako.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gt2brsssepi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gt2dhbyhoqq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gt2fijycrhk.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2lahyatsq.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gt2adrtdimq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gt2ndzqeyql.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gt2qpsmtxtv.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gt2pjhxcgbz.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2swizyanj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gt2heunsmvx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gt2yjngxdmx.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2mzwkkrfm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gt2lzlzguvz.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gt2lshzlkgh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gt2zpzgqwhk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2fcktllpb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2hznxjaip.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gt2vhnekyeb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2ftauvbzj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gt2nhysgcnb.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2lzyzziyi.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmtvotqp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lywzsojv.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lhzjwzvu.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2yxaquocs.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2foivuwrj.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gt2tagvekkl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpwhzdvn.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2daptoyxa.html


<!-- 参考信息 -->