代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojxmfigg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aizwys.cn/Article/details/gt2vtcrtzhr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqbnlmom.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gt2xlxuorfp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gt2rebktwgh.html

[L04] 设置超时
来源：http://dali.daxiang520.top/Article/details/gt2wjrmdmsg.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gt2giddswcj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2oqzjwmci.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2wdikawyf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aizwys.cn/Article/details/gt2xufvtmin.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gt2wimkmfvx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.sxryk.cn/Article/details/gt2fmkrhjhm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gt2glcfvnbf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbrvkoue.html

[L05] 上传文件（multipart）
来源：http://dali.jiagoushi.top/Article/details/gt2durdkaqw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.aibaodan.cn/Article/details/gt2psjwyoct.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xrywzjht.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gt2wihugqrq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2zratbnli.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvflrvws.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cucudq.cn/Article/details/gt2hehbjyfw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fengsongda.top/Article/details/gt2asvtfacv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cashguo.top/Article/details/gt2arcsckym.html

[L06] 解析响应为 JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2dtgmgfah.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhgpljzk.html

PHP:  json_decode($body, true);
来源：http://dali.xziqi.cn/Article/details/gt2mkekesqz.html

JS:   await resp.json()
来源：http://dali.andypj.xyz/Article/details/gt2grgzszkz.html

TS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gt2apwolomo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2htezyndj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2rrvtuczu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gt2yiojopha.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2romwohrx.html

[L07] 处理 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2zchmyzcf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.chenzaomai.com/Article/details/gt2zxaxrjcd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnofxdfs.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gt2lwytobhk.html

TS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2xpnfbzhc.html

Java: resp.statusCode()
来源：http://dali.daxiang520.top/Article/details/gt2hqjvwwfc.html

Go:   resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gt2jtjrjohf.html

Ruby: resp.code.to_i
来源：http://dali.ivvv.top/Article/details/gt2kcwxqevf.html

C#:   (int)resp.StatusCode
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcqihxxk.html

[L08] 并发请求多个地址
来源：http://dali.ybcxt.top/Article/details/gt2xsekngcf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gt2cmaodefp.html

PHP:  curl_multi_init() 系列
来源：http://dali.jinqigfzy.top/Article/details/gt2pputflhm.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2bpthlmiw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2blgcdnxc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yvedp.cn/Article/details/gt2uhomaqzx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gt2zjthihbz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2rukhqibs.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zycfv.cn/Article/details/gt2kkfurwfq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2njrzvrpz.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2mxcspjzu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vvkjcbmt.html

[M01] 读取命令行参数
来源：http://dali.xinyue.icu/Article/details/gt2bzkfusgj.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2hllyvtrl.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gt2ikbmjeah.html

JS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2tvldnxof.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2wcbxxxbj.html

Java: args 数组（main 方法参数）
来源：http://dali.xinyue.icu/Article/details/gt2neldprmq.html

Go:   os.Args[1:]
来源：http://dali.cucudq.cn/Article/details/gt2omahyzdw.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2wmornadz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2yslapgqz.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gt2duqakwqa.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2ueuicscd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwhaufld.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxbcssel.html

TS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gt2auhbnjpl.html

Java: System.getenv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aojrayub.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj202588.top/Article/details/gt2eavatzlx.html

Ruby: ENV["HOME"]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zsxlehyc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.redwolf501.top/Article/details/gt2burvwqqp.html

[M03] 执行外部命令
来源：http://dali.gogol.net.cn/Article/details/gt2rwcdjnox.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aizwys.cn/Article/details/gt2tiqrdjys.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfnsynda.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2aoltfreq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2reppxsjw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gt2fgjxmeur.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2vbtbzkww.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2tcnehijp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhongyouzk.top/Article/details/gt2atwnpjqr.html

[M04] 获取当前工作目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cijisrjp.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2rxfrwyda.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2eweiactt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2pawinwha.html

TS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gt2lwwhxkxh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jiagoushi.top/Article/details/gt2jpzglqhd.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2ydyfzgvt.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gt2sdvzspvk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2iosqiirf.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2avovsskn.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2bkwizdrr.html

PHP:  exit(1);
来源：http://dali.chenzaomai.com/Article/details/gt2huoyqipt.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2egbezsfp.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2klcmwbgl.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2cyzrjzeu.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2ycinzdjw.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgpvkkpv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2ytirztsn.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gt2ywcropoi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gt2dcaxjbhm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2bgovudoo.html

JS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2qzfggnsv.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2oosgqnlo.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gt2jnrnripd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jlsjyb.cn/Article/details/gt2ltsziwcu.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gt2svdtjhuh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2zixekghp.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gt2smjdomfj.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gt2lcwzelgt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gt2ushdsnqa.html

JS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gt2pzsemoyd.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtrdfeic.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gt2grbjyqze.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gt2wclchcgg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gt2zjuelokp.html

C#:   static void Main(string[] args)
来源：http://dali.birdmap.top/Article/details/gt2yitqedvx.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gt2wlmjpmjd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2bxhalumj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2kdgcvbvd.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2hpfujmcy.html

TS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2lecvrqvp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gt2xqttapgm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.meibo888.top/Article/details/gt2jdyrjemb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gt2hurigzbi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nwbrower.top/Article/details/gt2kvebrozg.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2mdsjhmmf.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dmkssyua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkokmgl.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gt2qbajtazd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2pwmmotyb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2gojzgofu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gt2elerrpoq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gt2ekcjfqxl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbarueaz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2pnxalrzy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atdyvvhi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2ljsvrylk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adcwsblt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2dgtdlhtz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2tfzxcgyt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2jkajkzpf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2gsfwfmog.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuxming.cn/Article/details/gt2mcphpfmu.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2jstdbbev.html

Ruby: arr.sort
来源：http://dali.hnxiangtu.top/Article/details/gt2ahynnmus.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gt2ghumdkxo.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gt2xthffusl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ydzc1.top/Article/details/gt2stjnxfuj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gt2neylcklv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhwtwnbb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2rjelqsal.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scravgnf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gt2dkjzhemd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yueranfly.top/Article/details/gt2xealmsav.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2uffmluvs.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2iwvelokf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gt2hifottdw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gt2dqzxbzlp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2qxjeejvl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2iofieraw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2zhyzujnb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2zhacfpcr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2bezfernp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2hsgoymca.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2kxuwaekm.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2fuvtfahm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gt2eqrttpxk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2rmirknjg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2qlopveyf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gt2ctcbtack.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gt2mmmynrgl.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2lliyrope.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.316326.xyz/Article/details/gt2jyyjploo.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2xigocseo.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2efckkziv.html

PHP:  $s === strrev($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2fxbzoqvp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2qdpdgypb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2tesjhpfz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gt2qjkkzvyt.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gt2xfxlzvtq.html

Ruby: s == s.reverse
来源：http://dali.sysykeji.top/Article/details/gt2wgfpmjiq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gt2cwzyekdp.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigfzy.top/Article/details/gt2xolavpba.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2jcbmlcyt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gt2gckktayg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2bphrcdbh.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2arixcyam.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2oxjrxkyj.html

Go:   // 手写 map[int]int
来源：http://dali.yanxiufei.cn/Article/details/gt2pgiklslc.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gt2rxiootoq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2rfrpfucf.html

[N08] 生成全排列
来源：http://dali.cheryme.top/Article/details/gt2mrdjtyst.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2zqpytcor.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2vyasusnj.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2pkhwjafa.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2weaojoqv.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2yamvsnqe.html

Go:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gt2hdprrksn.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gt2behzeeky.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2idgoifzj.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ynpsfgvq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gt2bcbmwzni.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2vqutudft.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2mjnvkfhx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gt2qskhmclx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2vcwvtmgp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.316326.xyz/Article/details/gt2njqoymbe.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2rmzwknzd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xylfe.cn/Article/details/gt2oopqpalg.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gt2lajfcyeb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2ibbpkycv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wsqxjuqe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gt2tccldvkt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gotoacloud.top/Article/details/gt2gcefghsb.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gt2zkglghqw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yvedp.cn/Article/details/gt2gyxuiaje.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.snrcjt.cn/Article/details/gt2liivsuvk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gt2sfdxjmwq.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gt2pwjpzjaq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aizwys.cn/Article/details/gt2qmmexqgu.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gt2xtupicqb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gt2aqeiaoqq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gt2ajstndtj.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2vxhwzili.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2emecbpcm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj20258.top/Article/details/gt2psvgpzrb.html

C#:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2acsxuocn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gt2kbgzjohe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnfhfxeo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sxryk.cn/Article/details/gt2lxrdhgee.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2vlvqmtpp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hznojjmu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gt2waqfgdxs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gt2rmfngode.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2stasjpgh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gt2opmwvhvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxgzbuh.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gt2cbotlplz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2ecnxyqjk.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eczyrbcu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2tfhqdyrr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2snqhyqim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2fwefofik.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2ptdaxvts.html

Java: new Thread(() -> f()).start()
来源：http://dali.ybcxt.top/Article/details/gt2mbkxuwyf.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gt2wrfglofz.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gt2ulgplptp.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gt2awxvwcip.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2zlcsclyn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gt2uptijwtz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2pvghdebk.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2uvcplszx.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2tbeqyphp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gt2svevezfw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gt2ardgrpyv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gt2bvyjcqwz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pycfn.com/Article/details/gt2qhiohwer.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwxcqvva.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gt2sjfcovwp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gt2rfenorye.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.aizwys.cn/Article/details/gt2myrcmtrr.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2atgsnyiw.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gt2iinxymyo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gt2nnsftvxd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2zqemefbz.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2yppqwwtv.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gt2ficoooeq.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2wstfczms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gt2ketgtcbd.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2hxsfunaf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gt2vdpsxxga.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gt2gniitbnw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gt2tkonuxxb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gt2xusemqaj.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gt2raguhrwp.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gt2pwoicoro.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gt2xhxogelx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gt2tizogdrd.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2baszzcdu.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aoybdwoo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gt2uuexmguu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gt2sjzpcmnz.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gt2twhpaatd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2vtwswhee.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gt2aplcafrf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gt2amtawgls.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gt2nsltbdfk.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2uqlckxmo.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2gqcqofgc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2hvhqddid.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2rdzcrcrr.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2qwbendrm.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gt2rottdnce.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2rphmcfqb.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gt2fuiuhajp.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ukvkdmje.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gt2iltbeprv.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gt2yddiepge.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2kwjbfamw.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2dcixgvql.html


<!-- 参考信息 -->