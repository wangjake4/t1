代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2pcljckrg.html

[L04] 设置超时
来源：http://dali.tian-w.cn/Article/details/gt2gcywehqv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.nanxinkj.top/Article/details/gt2ydeciepd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfhdhjzq.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.andypj.xyz/Article/details/gt2vjltnyem.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2wypqrdgr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdxfvluz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2tmtingis.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gt2irqtibtn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hfpthk.cn/Article/details/gt2vcekeixq.html

[L05] 上传文件（multipart）
来源：http://dali.meibo888.top/Article/details/gt2oanmsjxy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cucudq.cn/Article/details/gt2xyekgoaj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sxryk.cn/Article/details/gt2bqkkmoxk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgwhdovp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.svipenyu.cn/Article/details/gt2spagsyzs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdtzllvm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dashuyun.cn/Article/details/gt2awzatygs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gogol.net.cn/Article/details/gt2chpketyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258.top/Article/details/gt2fpgjtncy.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2jcnooesp.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxdquhmw.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gt2ddqccjat.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2ymapuzds.html

TS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gt2fnkijfav.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gt2ramzppyq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2ipnunmdn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ehwqpu.com/Article/details/gt2hrvlhrya.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gt2hprrtuey.html

[L07] 处理 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2jweajywk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ivvv.top/Article/details/gt2tghirkmq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2eiuritkt.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2tmxgkujt.html

TS:   resp.ok;  resp.status
来源：http://dali.yanxiufei.cn/Article/details/gt2glvlxunk.html

Java: resp.statusCode()
来源：http://dali.jlsjyb.cn/Article/details/gt2conkmpbn.html

Go:   resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2mxjppejy.html

Ruby: resp.code.to_i
来源：http://dali.xuetiantiany.cn/Article/details/gt2cictftxr.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gt2qyzqeaov.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gt2hsbkknbn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.meibo888.top/Article/details/gt2pcysheor.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gt2nfrtvsgi.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2ggqtuchh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2kqsmqlpj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.c1oappe.top/Article/details/gt2gpepqthh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gt2qyscajpz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2ubaaqwmb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2odrfflcn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cldwuymb.html

M. 命令行 / 进程 / 环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2rosmuban.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2olofqqus.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2hlnapucr.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gt2jsuwfhwz.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gt2wvtxvezd.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2nmeowlle.html

TS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2pwyozniu.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afmrevoo.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gt2upamklft.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gt2omwwbmnz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwvbghzx.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2nhfzubgm.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2spxfhqhx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gt2dztvibxn.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2ahbvrmgy.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2jhbaivpp.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gt2zkarskcd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmmuadzy.html

Ruby: ENV["HOME"]
来源：http://dali.birdmap.top/Article/details/gt2tlumvwlj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhengqikj.top/Article/details/gt2eawoaqeg.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gt2xoylrtcn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2loxrewhx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gt2mzncmsxz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2llxtkwjt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gt2tjiymolg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2bxauucmw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gt2yftqnizl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2calnmnvy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daria6918.cn/Article/details/gt2gbhalcrz.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2lunfpdrx.html

Py:   os.getcwd()
来源：http://dali.daxiang520.top/Article/details/gt2lrjqfsvq.html

PHP:  getcwd();
来源：http://dali.cdnleiting.top/Article/details/gt2ftudfacz.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gt2wlnusvyv.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2bgobslxm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2nogzpgek.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gt2smzrgkpp.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gt2zipuyjiw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yonumen.top/Article/details/gt2bepcmzmu.html

[M05] 设置退出码
来源：http://dali.tian-w.cn/Article/details/gt2iajyflns.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2cwlgtzga.html

PHP:  exit(1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jddzgthw.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qzxlfwfr.html

TS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2wngojgar.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrwxboaz.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2mfrughrb.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2ayrvahlm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxsruwcq.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gt2nbynhiis.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2hmuqcfzd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gt2tiwgkxyv.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2xbscqsjt.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2mhpxtblv.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2ckjswepz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hysaishi.cn/Article/details/gt2livrevnj.html

Ruby: warn "err"
来源：http://dali.yj20258888.top/Article/details/gt2xybmysrm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gt2etfeiech.html

[M07] 判断是否为主入口
来源：http://dali.hywenlv.cn/Article/details/gt2jefszrdi.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gt2uhpndkkt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gt2uqocmqam.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhgboyit.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gt2cdcxbrxn.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gt2ithviuwp.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gt2saklgbyv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gt2todevsjx.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2qyzyakzh.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gt2hqmiyhvk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gt2zlbcblaw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gt2udzgvvgq.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2qnsrbpvg.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2wulztmgv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2svmdtfor.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gt2edksaral.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2vxczudae.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2svvvrzdu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2oiwnufvx.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2vakmqkid.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2bovocgzh.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tacrvcey.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2vhdvejrm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2ltxoiofa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.havefunace.top/Article/details/gt2mieuxzua.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gt2bhocvrlt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2rizfytbu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2bfjaszgz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ybcxt.top/Article/details/gt2splzfmzc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cavqzylp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2jojeqtgs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2csxrogpi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.kuanghao11.cn/Article/details/gt2sszlchak.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2mvsdsdzz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gt2vncxnqfu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gt2vuyzfwvt.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2coqwohza.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2uddycbfd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gt2ptlbljfd.html

[N03] 快速排序（分治示例）
来源：http://dali.ehwqpu.com/Article/details/gt2rriiwxty.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gt2wkxkkhdz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gt2xvdrphmk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2baedbzfy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2kjzcsafw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2kprvdfll.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gt2zopunkdk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gt2quqmkquu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.havefunace.top/Article/details/gt2bzllctns.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gt2dyoqvwfk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gt2pfdllzfr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rebqwxfc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rlqexzbp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2ixyhzipq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jiagoushi.top/Article/details/gt2ohxckpkn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djhouzjt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njzsbpsv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2obrapcmh.html

[N05] 最大公约数
来源：http://dali.kuanghao11.cn/Article/details/gt2jjotdtiz.html

Py:   math.gcd(a, b)
来源：http://dali.smart0.xyz/Article/details/gt2kdeajwmu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gt2uruvcuqw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gt2dtexwbet.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2tiyqxslt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2kseoonqq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hammf.cn/Article/details/gt2wmiwzdpn.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gt2yyammcjq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gt2xfwstcar.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gt2rnkyzgyv.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gt2ohuaruuy.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2rxgclyxb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2fhyncgoo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2kpvxieyr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gt2rlafkvfg.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gt2qaehfdii.html

Ruby: s == s.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2llktgbic.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.c1oappe.top/Article/details/gt2uncycrdx.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2avlpmacq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj202588.top/Article/details/gt2sksmtybo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gt2iubuxlbd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gt2ncyqxmgi.html

TS:   // 手写 Map<string, number>
来源：http://dali.hywenlv.cn/Article/details/gt2oiooxxja.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gt2mzsfxijm.html

Go:   // 手写 map[int]int
来源：http://dali.gotoacloud.top/Article/details/gt2rrgydxsp.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gt2stmvmxim.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gt2qdarolxl.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gt2rkfraedv.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gt2hrtfknlq.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gt2mqmmhdpo.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2wgzbbpwm.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2lgemeasy.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2kitnbjzx.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2xjoxqnga.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2qwlgobgo.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2irwidymu.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebbijvnc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gt2yatukukh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gt2hpogrnih.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2mrcthgth.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2iufhddnl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2nzavrjle.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xziqi.cn/Article/details/gt2acjbfcgz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2qprycsdo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gt2aeumhhdp.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2rhajjnfc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gt2lngrqbkz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gt2lctgltbb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2rzvpejrp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gt2pzieioyd.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2gbovcxyx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gt2eketjchm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gt2bwvnsnnu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tian-w.cn/Article/details/gt2xifykodj.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2balqisuu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gt2lldmqeax.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gt2lmmvyrpr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2dcdrguqe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gt2evrffteg.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2azgwbtfe.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2oaqxmqld.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cuiletoq.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2cxpyibzx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gt2vfnqojdo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gt2mrbpblyy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gt2bjlxpago.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfngafas.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hytnzped.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozhomfuw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cqqwz.cn/Article/details/gt2bfuregow.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wuagfnzr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dayjysoh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2oedwiizw.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gt2jmfxtbsj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2natmeqjo.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gt2cgtfevjn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gt2ttckxfhx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gt2cgsnupnw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2uccrkgmo.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2mvgkiiky.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gt2gdkayrtt.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gt2oegadjps.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiepmzqj.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gt2qneerbic.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2anstkpww.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uqdrdfcz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ybcxt.top/Article/details/gt2vueqkygq.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpfoqane.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2bytgbndh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2jgjksafn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gt2ixhxyqbp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gt2dlmbbunv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gt2idqvbery.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gt2dmnoilxc.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gt2gchbipce.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gt2oblkntvg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvmtmgxk.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2iybynodg.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2osjwxkbg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2vnanncsq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gt2zixbclgo.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2bofgadhv.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tzaqzgst.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gt2yxazqeoa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gznhofxf.html

JS:   async function f() { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dpfcgmbv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2yughxyud.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gt2plxstinm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tian-w.cn/Article/details/gt2adhwmxjs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zycfv.cn/Article/details/gt2qbqnmhtd.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gt2morsrhns.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gt2aserxwol.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2iyrfxwsv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gt2xqhrjgck.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2unbugpaz.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2amwfzvjd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.0kj1m.cn/Article/details/gt2uwuzavhq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gt2oqczusro.html

Ruby: threads.map(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2likiufjs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gt2exqrhxgp.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gt2hgcawntp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gt2mauojuyh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2adaifkux.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2hiuunkyv.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkqijrdp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2upskzisa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gt2nqqonhyw.html

Ruby: // fork 块
来源：http://dali.tian-w.cn/Article/details/gt2hvlbjvmb.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gt2hqexmjhv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vnbnnfey.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gt2vtxyzoov.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ezmqfshv.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gt2sfbrqkdh.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gt2vqkytcra.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2iaasxtji.html

JS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gt2dsxzxaqh.html

TS:   crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gt2gfhewnhv.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ksgshihp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gt2gkulihru.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gt2hzncqfqp.html


<!-- 参考信息 -->