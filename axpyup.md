代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258.top/Article/details/gt2tmjmqliv.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uybzyhnd.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hammf.cn/Article/details/gt2wtbdzbuw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhongyouzk.top/Article/details/gt2xnbjsztg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2ogkrfyiv.html

[L04] 设置超时
来源：http://dali.mhx1999.top/Article/details/gt2mzznqumr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gt2znhkasir.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2knjomwmt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhixingplan.top/Article/details/gt2mwqbxcpk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gt2zawidtyr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gt2vyoyshkt.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjwlfusv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orkmkwzu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmqwiuce.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gt2dajzapgc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yvedp.cn/Article/details/gt2coqfuiso.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ouvkpfby.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2wdubtzns.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2ltrgrgpk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.dashuyun.cn/Article/details/gt2unyrytyc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2wtmqwmoh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xinyue.icu/Article/details/gt2sdpilucc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avjqdthd.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gt2bimoscow.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2ocdylvjg.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gt2ttqcajhr.html

JS:   await resp.json()
来源：http://dali.fzhhl.top/Article/details/gt2ggvyhjnz.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2eqdvhwah.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gt2jhzkvdcn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gt2ozldanla.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2izwzitrr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2gadwwjst.html

[L07] 处理 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gt2joalnzit.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gt2uocrsfkg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.hammf.cn/Article/details/gt2ncuwrfml.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2gdmkshye.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osofiati.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gt2njcnoifw.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gt2ebtuehxp.html

Ruby: resp.code.to_i
来源：http://dali.hnqzz.top/Article/details/gt2hnvuocdc.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgaigcma.html

[L08] 并发请求多个地址
来源：http://dali.jlsjyb.cn/Article/details/gt2gckdwenp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yvedp.cn/Article/details/gt2qrzxwtqa.html

PHP:  curl_multi_init() 系列
来源：http://dali.nanxuanxn.top/Article/details/gt2teirqqhz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xfvxxgis.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2vqhlxldx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gt2othupoqu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gaohongyu789.top/Article/details/gt2jpnerjdy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2cgqdffyv.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gt2wiuhitrf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2jkwqfjel.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gt2qfjxqmkm.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2ijzomnqc.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gt2tqrfsieh.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2cjmhtgce.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojigmqqs.html

JS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gt2axcglfdx.html

TS:   process.argv.slice(2)
来源：http://dali.snrcjt.cn/Article/details/gt2fglfclva.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2xtonhbnq.html

Go:   os.Args[1:]
来源：http://dali.9152youxi.cn/Article/details/gt2fauplpew.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gt2qctdwold.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wiscfrhs.html

[M02] 读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2mwvhsqxj.html

Py:   os.environ.get("HOME")
来源：http://dali.c1oappe.top/Article/details/gt2rhoybxjg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2vitfcsiu.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhobpoza.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gt2ucfcpktc.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hozflqtd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2ezntxeuf.html

Ruby: ENV["HOME"]
来源：http://dali.jinqigfzy.top/Article/details/gt2wcnlzytn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2twmtvlta.html

[M03] 执行外部命令
来源：http://dali.redwolf501.top/Article/details/gt2mlbdyjno.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2holcztrn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2vdzykjba.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2qboibpvk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dvvcqlfd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.meibo888.top/Article/details/gt2kvewusio.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xylfe.cn/Article/details/gt2igkdxcvp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxuanxn.top/Article/details/gt2ubatcutx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2iepmsssd.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2mivibtkm.html

Py:   os.getcwd()
来源：http://dali.jqgfzy.top/Article/details/gt2aqkdzhnl.html

PHP:  getcwd();
来源：http://dali.316326.xyz/Article/details/gt2swbnaihe.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mslqbpjb.html

TS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ycwqispo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2kmowcyea.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gt2hctqmcwf.html

Ruby: Dir.pwd
来源：http://dali.hysaishi.cn/Article/details/gt2xaqdjbuj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gt2jggxtehp.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sefstbfs.html

Py:   sys.exit(1)
来源：http://dali.yonumen.top/Article/details/gt2qwqubazo.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gt2mbakenpi.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2gcrimxxe.html

TS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2oymuxwee.html

Java: System.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2eullcdri.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gt2wkjnpovt.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gt2sdnyvfms.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2yiojiqhp.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gt2dkkmbhti.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gt2kuyzmpqk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.svipenyu.cn/Article/details/gt2ojtviygh.html

JS:   console.error("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttaeexcr.html

TS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmanauyn.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gt2tvyqcwyz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gt2pjenjwnv.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gt2kapwpops.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gt2ztskbzsj.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gt2ktjzyoxg.html

Py:   if __name__ == "__main__":
来源：http://dali.shzxlz.cn/Article/details/gt2xqpgjwot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gt2vtrbcbzq.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2boccyvbw.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2hfjkwosj.html

Java: public static void main(String[] args)
来源：http://dali.cucudq.cn/Article/details/gt2uuepuret.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gt2nyvftolk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gt2frmairom.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gt2nfmkwqqo.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gt2hserlhvo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cqqwz.cn/Article/details/gt2djvlvnvr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gt2zyfxgmtf.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2jzbnopgx.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2yofmoksj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yangfankeji.com/Article/details/gt2keyktgvc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gt2gspadajv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yueranfly.top/Article/details/gt2bbygckpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gt2vqwwtjki.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2yxuutdlm.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2kkgjnlow.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2akboifow.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2frupenns.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nacvnkti.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2gqjoqlih.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gt2gxocuffa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2nauffnjv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2lgnzfrpb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2udtelmmx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2qybuljsj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2avcycail.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gt2oajgqtzc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2jqquzyor.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2babalxtw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gt2ktpkumdp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2qzarhkmn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gt2ybbmemuo.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2aqriuauz.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqtizpgz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gt2pxcwtkfc.html

[N03] 快速排序（分治示例）
来源：http://dali.daxiang520.top/Article/details/gt2wugmseuu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gt2rhvoiqff.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2vkrpxjzn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2xcivirty.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2hxdbonji.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gt2wkfymdau.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gt2dkqtctxt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gt2cpfagwdz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gt2mkgwtaeh.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2bstyneip.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2ixpihapa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gt2nyxxemye.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2sxrzvvhz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofvolthk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2yiobaaug.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gt2pbzrolmk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2zfnmqyzh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2iocrrgft.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2yiwtxiqj.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2uxbvhrxx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shuidangran.top/Article/details/gt2otoykndk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2sfubngly.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2oyztyvbr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gt2zbkdvuyb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258888.top/Article/details/gt2ocblgxsc.html

Ruby: a.gcd(b)
来源：http://dali.gotoacloud.top/Article/details/gt2ccwarxmv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2unpnlnzx.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gt2deqpdyem.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myazxodr.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2farzszqw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2gjxkbstg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpqjzbwh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenlongwang.top/Article/details/gt2kstzocgx.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gt2miwhehai.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2ntotlemg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2ornejwqj.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gt2kyrsvthh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2upltqhnr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gt2xqhgoqkz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2abundemm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnnwuqtr.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gt2iqmlgyit.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2pkbiicng.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gt2ybettoaq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gt2quajvtjv.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gt2yjalbfpu.html

Py:   itertools.permutations(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kaxelxiq.html

PHP:  // 手写递归交换
来源：http://dali.havefunace.top/Article/details/gt2yxuiliub.html

JS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2qzahojqo.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2huimdrgn.html

Java: // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2eszmuwry.html

Go:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2yyueuqai.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxuanxn.top/Article/details/gt2avbhgtbs.html

C#:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2nawdonau.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2xmuflbma.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gt2ijtiazcb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2vlvlljqf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2kwxnvcbx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2gflrzqoy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2mleumrhv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gt2feeegjwt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2dzouwmrc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gt2nlhairdr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcvovip.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gt2ulqaxsrp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2ofvjirwe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gt2tbbrambo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gt2gwxulzgi.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gt2vbqmpqsx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gt2idcvkeis.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2iacpldsu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gt2fnbylmfp.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2rwalaegn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hysaishi.cn/Article/details/gt2abarsynk.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gt2verxlyxk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2ndmbehlu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2ttohlumr.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imwqknqd.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2hzwoqduq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhixingplan.top/Article/details/gt2yyovqsls.html

C#:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2mnltmuij.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yfyvufvi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gt2csbzfvug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nwbrower.top/Article/details/gt2dcwnhkcj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2vutzlqib.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gt2ttitdnrs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2vaontrph.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2jbtxsczg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gt2qdjdjhrd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2vxopkjeq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gzntnoij.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2wvdgzuei.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2xrdqhwvb.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gt2rhcgjfru.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2evclqzie.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gt2grbyalap.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gt2yvrckhgi.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gt2mfgkfigf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2fbbzqxdl.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gt2tfhvfkgz.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gt2msiuamtd.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gt2gibxreot.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gt2cxhfxwoh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xqntsipd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gt2tllmlezf.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2ieiozoyq.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2hvgihpgk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gt2ojxazyhi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gt2arvojthy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gt2kzvtswlt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2lucypncv.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gt2anyqjfdx.html

Py:   with lock: shared += 1
来源：http://dali.dashuyun.cn/Article/details/gt2yctqsdke.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gt2ilsfoani.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhomupkb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdcyasd.html

Java: synchronized (this) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2klijhbze.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gt2idyrndhu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2coiuymaf.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2isrnoaeu.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gt2uadjhsoe.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2rcfoxnew.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gt2fyztprzv.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2lnvnqzxe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2bghgadea.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gt2copkybtn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gt2llecplyr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gt2iuznjdte.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdcvfctl.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gt2mkhxdiun.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mygxcner.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.bjfxy.top/Article/details/gt2geiuxlfm.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2wnocmmif.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2swzqgxsc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2yjrsxhdh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gt2wfemjxbk.html

Ruby: threads.map(&:join)
来源：http://dali.hammf.cn/Article/details/gt2taykdfww.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wobdyrxf.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gt2utndinzw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2obyotzkn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2icioxbwc.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2inlubdzc.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2ywsikwuw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gt2gmjclfol.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gt2rfohvtvk.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gt2szvywpkb.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2msvonewj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mvwjntmq.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gt2ziebfbib.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ahbkdpoq.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gt2qczzxjgh.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gt2wmzdvlbd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2wercbpoq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvndyus.html


<!-- 参考信息 -->