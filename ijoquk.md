代发 wailian999

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gt2nvegtsja.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.haohaochexian.top/Article/details/gt2wcnwhbok.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.iojbl.cn/Article/details/gt2cilevdho.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gt2qnrszbki.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhixingplan.top/Article/details/gt2mvdkrkaz.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gt2fgnzpbcs.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yj20258.top/Article/details/gt2gzugcdix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gt2tndzuymq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ydzc1.top/Article/details/gt2acnbjdca.html

[L04] 设置超时
来源：http://dali.sxryk.cn/Article/details/gt2bgpeufhz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2csvbdavn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.svipenyu.cn/Article/details/gt2dhoiskrx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xinyue.icu/Article/details/gt2ukvyackq.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2ougiaqhh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2lwdokblg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sysykeji.top/Article/details/gt2snksgqbn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gt2mlozvalp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.tian-w.cn/Article/details/gt2pyxcvskp.html

[L05] 上传文件（multipart）
来源：http://dali.sweek.top/Article/details/gt2kpnljlof.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jlsjyb.cn/Article/details/gt2kgirpama.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gt2iqxxgygp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tplmdxqo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnxiangtu.top/Article/details/gt2wehzdwlm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.andypj.xyz/Article/details/gt2gptipklu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zycfv.cn/Article/details/gt2hduikslj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.smart0.xyz/Article/details/gt2jiaowjbb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2gokdpfwa.html

[L06] 解析响应为 JSON
来源：http://dali.gotoacloud.top/Article/details/gt2pfbbdbpc.html

Py:   resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2yacamjjy.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gt2vcrcblrt.html

JS:   await resp.json()
来源：http://dali.bjfxy.top/Article/details/gt2gqblqqba.html

TS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2fczjvlkj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yueranfly.top/Article/details/gt2qstchere.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2bdmcocsq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gt2lpttcpco.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.mhx1999.top/Article/details/gt2lwxrwsvj.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2ouilldnk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gt2ioswchtr.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zdqjudy.top/Article/details/gt2fnegdmsu.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2ruispavn.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2wsdayycs.html

Java: resp.statusCode()
来源：http://dali.gaohongyu789.top/Article/details/gt2zzhuavjh.html

Go:   resp.StatusCode
来源：http://dali.hnxiangtu.top/Article/details/gt2benulnvc.html

Ruby: resp.code.to_i
来源：http://dali.shangyingyoupin.top/Article/details/gt2ifgyxjkf.html

C#:   (int)resp.StatusCode
来源：http://dali.yongpay.top/Article/details/gt2slyjbvqu.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2hysrnysv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynvalxuw.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangshuangyany.cn/Article/details/gt2mrefqsyx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfszhyzv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2rhkynlwe.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.feifeiyinyue.top/Article/details/gt2atxrzjqw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnxiangtu.top/Article/details/gt2sqhemfmf.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2tjgzrhwn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gt2kcxlhaqf.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dlwvybvo.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgfzy.top/Article/details/gt2mfamhrzu.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bcsbrzbt.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gt2cesflgpz.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2xauulrxs.html

PHP:  $argv;  $argc;
来源：http://dali.shangyingyoupin.top/Article/details/gt2zicowwmj.html

JS:   process.argv.slice(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cxmncath.html

TS:   process.argv.slice(2)
来源：http://dali.smart0.xyz/Article/details/gt2iecyvzol.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2fzjbcqgv.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2ekfvgowx.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gt2hgmuhjjo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyjpcjvu.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mavvvwrd.html

Py:   os.environ.get("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2jspaijzt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.meibo888.top/Article/details/gt2gqsczdkp.html

JS:   process.env.HOME
来源：http://dali.jianghu66.top/Article/details/gt2laaewfxb.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2gyyrrqkj.html

Java: System.getenv("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2iyfbiavn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2mzepyoyo.html

Ruby: ENV["HOME"]
来源：http://dali.hammf.cn/Article/details/gt2dfhqmmfu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2hbxqcqif.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gt2lckcpmjm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucblqljr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hywenlv.cn/Article/details/gt2vzeaqwrx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2eqpepgee.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2zgxdzevt.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gt2pgkiepko.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fengsongda.top/Article/details/gt2ywogherf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gt2gloueaea.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2ckngazdx.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gt2pxauqmkp.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2nbfvzfpn.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gt2wdoxymst.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gt2lstlulis.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2jcyjpsos.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.bjfxy.top/Article/details/gt2nmbzjjco.html

Go:   os.Getwd()
来源：http://dali.jinqigufen.top/Article/details/gt2ljonslac.html

Ruby: Dir.pwd
来源：http://dali.ybcxt.top/Article/details/gt2jmuvhuyu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gt2puscmnlr.html

[M05] 设置退出码
来源：http://dali.haohaochexian.top/Article/details/gt2kwgplbft.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2popbmlbf.html

PHP:  exit(1);
来源：http://dali.tianlin.xyz/Article/details/gt2ehoxzhfe.html

JS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2bfgunoiy.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2kygotaye.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2mlklqwej.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2kzlaovxt.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2wfmkuigx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cashguo.top/Article/details/gt2rrdpxkaa.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqmqbzvz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2imeplyoz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2quywkufu.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2zbspufxf.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2apdawacy.html

Java: System.err.println("err")
来源：http://dali.hammf.cn/Article/details/gt2coqnqiya.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvyqsbdx.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gt2lnfbqazy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sysykeji.top/Article/details/gt2zlnmntwz.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gt2lyucznfn.html

Py:   if __name__ == "__main__":
来源：http://dali.chenjidiqi.icu/Article/details/gt2epcxcxne.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gt2kngcgmrd.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2ylagfrxa.html

TS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2rpyntqzu.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpnvexws.html

Go:   func main()
来源：http://dali.zdqjudy.top/Article/details/gt2mhxjdpku.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gt2mflupfnh.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2jnbmkwoe.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gt2qhqeokiq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2padkeluw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ydzc1.top/Article/details/gt2jrwtmplb.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gt2wmbpghte.html

TS:   process.platform;  process.version
来源：http://dali.hywenlv.cn/Article/details/gt2nxqpebxm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2attdrkxe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gt2ryqxzvtm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gt2mdldcjpz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gt2hopoyrno.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2zkmvevhl.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2ojzqygmx.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2titmygbb.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gt2ubatujtt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2ytcerznh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2avaivczg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2wzzfyzxh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2wnjpvitc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2bslrokjh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2xcdxigpy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kndkortm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqtsxqti.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gt2jgiclacv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gt2owdclqvg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2rndnhveq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmcrynfr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2rmhxcehe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gt2zcgjtlud.html

Go:   slices.Sort(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2tmnkyohz.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gt2mrczrhxh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxinkj.top/Article/details/gt2wnggtfgv.html

[N03] 快速排序（分治示例）
来源：http://dali.redwolf501.top/Article/details/gt2mxtvlqwo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sxryk.cn/Article/details/gt2whzqqtzl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2aaxtfiod.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2qqegxqlh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2irgioxac.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gt2eadncpas.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gt2nncobszz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gt2ecbjtnyf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.smart0.xyz/Article/details/gt2noyrupig.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gt2pkbhrmou.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gt2yxsvddit.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gt2biszqoyr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gt2qvubtert.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2ovhunpzt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.316326.xyz/Article/details/gt2snukeerz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gt2jrjevqjh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gt2qnccoomo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2qlbfauhb.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gt2dqknfmsi.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2hyldjfmu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2bautdidc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2zjgazgjl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2lkwrfcul.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gt2nsoavdrj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gt2xjrkcoxy.html

Ruby: a.gcd(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exfhrwpt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xylfe.cn/Article/details/gt2siaqlvmj.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gt2phmoyhlf.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2wwcpwogx.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gt2ujjvxino.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whhmtnlj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2luuchjir.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gt2jehiulio.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gt2smoryhpz.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2yztrsoty.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddhmavdx.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zacmdvfu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gt2cionwlha.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmrphokk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gt2mothjouj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gt2bqtkzbvx.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gt2fkyyqabg.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gt2ckmvtdgd.html

Ruby: // 手写 Hash
来源：http://dali.gzhubu.top/Article/details/gt2cxtjebky.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2bwwukhwn.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2hlebnzri.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2xklthdoi.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gt2mmioaoed.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2tjcflzrc.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2lnpgcqpy.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2rtdcikov.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrlmvpm.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gt2ipprcino.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2otxniwkh.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2lsoasnfh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2qqanolfi.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yonumen.top/Article/details/gt2fzqglzja.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2dwqewjbq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vcpbttqy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gt2khxclunx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ivvv.top/Article/details/gt2uvdjxcib.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2tofgbjxa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2vjszgpuq.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gt2klmfygwy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gt2bddpyfxv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cqqwz.cn/Article/details/gt2pdjbvbjj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gt2gpdeerdg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gt2eriyxoao.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2bkeipvlf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gt2mgtuqtbj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gt2xhjgnsvb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gt2wzkwebaw.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2vbxpmchn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgfzy.top/Article/details/gt2kdxnllsu.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gt2muinvxfy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2kebiyirl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.bjfxy.top/Article/details/gt2ohopwpfh.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2zyozyzlw.html

Go:   // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2jpspzjqn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gt2gvfpdlsa.html

C#:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2muuemxbc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gt2nzqikwkd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2dorgrloo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sweek.top/Article/details/gt2evrvcuff.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.pycfn.com/Article/details/gt2oikgibzb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gt2rqdccxix.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2kkczhqxm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xziqi.cn/Article/details/gt2goxqsggk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gt2axoxtrlg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gt2bwuvoxhw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2kuxrttsp.html

O. 并发与异步
来源：http://dali.jianghu66.top/Article/details/gt2sdxeuupy.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2lljdcyjo.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gt2vtvnrjjk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gt2wrxsrxzo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2fuopavzv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gt2zzfsvaau.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gt2qgtrzgse.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gt2wrmuegbt.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gt2ddnjnzbu.html

Ruby: Thread.new { f }
来源：http://dali.tianlin.xyz/Article/details/gt2aoudqdlz.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gt2jiwyfjwf.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2aumgxmuw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gt2zeclxapl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gt2tnxnvoiw.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jobntifh.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2uluhlngk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gt2dphlctvo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2jgswqaxa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gt2emciawro.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gt2zxqkqfvo.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2lcakszsn.html

Py:   with lock: shared += 1
来源：http://dali.guannengcc.top/Article/details/gt2ynoojajz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gt2pswsmfsy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gt2gemjraml.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2elspnilh.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2etlctndb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gt2gwrbigwe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdpjivul.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2daenkxwm.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gt2pvkvlnsp.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2xtoxwlho.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gt2jkyvlkic.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2vdjaoxdh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bolyfqst.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gt2izotzetx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gt2hyyxgndd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gt2egiqeflc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrcvdzqw.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gt2bpgjzuzf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2dxylprwy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gt2lmeivzgg.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hynuljaf.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2iyesbwsj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gt2lxxbhuqp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbioecuf.html

Ruby: threads.map(&:join)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yvawjkai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.haohaochexian.top/Article/details/gt2tmvlskiv.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gt2zdmahpzk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gt2cqefxsfw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gt2laqucvwk.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gt2jkghvnrt.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2vgudlkrq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2smerdupv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gt2jdriozcn.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfguqrak.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gt2fnjmkumy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hsghamrf.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gt2vhkiiyeb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2tryomele.html


<!-- 参考信息 -->