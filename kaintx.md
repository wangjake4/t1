代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhongyouzk.top/Article/details/gt2xwhfciok.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.kuanghao11.cn/Article/details/gt2eyivxuxz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2ebidurev.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2zhdwphbk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2toqqvpzc.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfojmjvv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.fengsongda.top/Article/details/gt2egqbslbb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gt2ksdncgmh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2rrcwejuo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2xfbwrqpv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2gzlvoqcw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xinyue.icu/Article/details/gt2rnoxykcz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yuanzhike.top/Article/details/gt2qsfrapua.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzaslgxa.html

[L05] 上传文件（multipart）
来源：http://dali.quarkkingdee.top/Article/details/gt2mebncsor.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.pengpengdd.cyou/Article/details/gt2rsglblmf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2knzeyour.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hammf.cn/Article/details/gt2yfienszg.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhusmtcy.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinqigfzy.top/Article/details/gt2jblhutit.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.smart0.xyz/Article/details/gt2sldwqpkx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnqzz.top/Article/details/gt2zarnwgjj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2getynqlr.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gt2oujhlclp.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2pplemnfn.html

PHP:  json_decode($body, true);
来源：http://dali.cdnleiting.top/Article/details/gt2bsbznbph.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2faidrsuz.html

TS:   await resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2zgxhmcqk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gt2vygrvjxg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gt2ezycomod.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gt2dhfqspjw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gt2ndmcwmct.html

[L07] 处理 HTTP 状态码
来源：http://dali.nwbrower.top/Article/details/gt2xsomagpy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hfpthk.cn/Article/details/gt2nfiolmze.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ydzc1.top/Article/details/gt2jbavrazj.html

JS:   resp.ok;  resp.status
来源：http://dali.fengsongda.top/Article/details/gt2iuaxazjs.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2wgbeujnq.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gt2celyefte.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2xchhlulu.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gt2eamzijro.html

C#:   (int)resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gt2hlgquucy.html

[L08] 并发请求多个地址
来源：http://dali.redwolf501.top/Article/details/gt2gcypmpel.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2mikewraq.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gt2wbwbhini.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2wdqivbyz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhoulong.xyz/Article/details/gt2gdsstlbm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2urgngnll.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hammf.cn/Article/details/gt2ztnzatzo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxjquhed.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwyscecq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xtbmyres.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gt2agezfwjy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzozfsua.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2onlufncc.html

Py:   sys.argv[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2ffyfheax.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gt2erolwlrj.html

JS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gt2ummzzzmd.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gt2walxzedz.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2wpndqdfe.html

Go:   os.Args[1:]
来源：http://dali.0kj1m.cn/Article/details/gt2biemnguu.html

Ruby: ARGV
来源：http://dali.hnqzz.top/Article/details/gt2fwotshet.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2hfzwwsly.html

[M02] 读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gt2friypvam.html

Py:   os.environ.get("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2pefobzax.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gt2buefckkx.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2mefeqndu.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gt2sapzlstz.html

Java: System.getenv("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2pferzcsu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.meibo888.top/Article/details/gt2grhcxxwm.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2ddgmlkei.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2nalmdbsk.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gt2vgzfxvui.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sufxvd.cn/Article/details/gt2bqkhqanh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigufen.top/Article/details/gt2gnrtdptw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2mvnnpoyc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnqzz.top/Article/details/gt2qlbpvobb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ybcxt.top/Article/details/gt2hkfjjhxv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daxiang520.top/Article/details/gt2hftxphku.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gt2ddlhocoo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gt2ktynhsgf.html

[M04] 获取当前工作目录
来源：http://dali.jqgfzy.top/Article/details/gt2pgolmrmh.html

Py:   os.getcwd()
来源：http://dali.chenlongwang.top/Article/details/gt2puodihqe.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gt2sbjfzosj.html

JS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2omlaglgr.html

TS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpnjszkt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cucudq.cn/Article/details/gt2jbffsmvc.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gt2foxlsdbz.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gt2yxcmtjtp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2dznreekr.html

[M05] 设置退出码
来源：http://dali.hywenlv.cn/Article/details/gt2rosqskyd.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2fqsrgojg.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2pzrsvvcm.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2fbeoetyh.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2smjocjsk.html

Java: System.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2qpsdeykt.html

Go:   os.Exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2nwyltfpc.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2kslqilcg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgfzy.top/Article/details/gt2kbfedusy.html

[M06] 向标准错误输出
来源：http://dali.aibaodan.cn/Article/details/gt2nqnxgidk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2slwvcimb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juuesmzv.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjickujn.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwbwignd.html

Java: System.err.println("err")
来源：http://dali.fzhhl.top/Article/details/gt2aivbintn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sysykeji.top/Article/details/gt2ruwcayrz.html

Ruby: warn "err"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kseeknsy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tanke756.top/Article/details/gt2ekgdglih.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gt2kvwfchzp.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2hvpwytqa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gt2thldqepu.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2ckxoevah.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gt2skkihckt.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2nyghwuth.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2suozvgoz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2fnhansli.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvhtbvrz.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gt2ebxdqvkz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gt2qhpaaqcz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2qaidxoez.html

JS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gt2jdyyvswp.html

TS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gt2hhurmhyd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gt2fvdxhdsj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gt2hepyreia.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.mhx1999.top/Article/details/gt2zqccvegy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.tanke756.top/Article/details/gt2arnzkocx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2ofoslbrb.html

N. 数据结构与算法
来源：http://dali.xuetiantiany.cn/Article/details/gt2ihpyqgxd.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqbwaafh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gecfjseb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2flwnzxsp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2dmgeqqgk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2auhjpgqc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pglcsiqq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2uqpfkrxo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2lntvydhd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2pwworkqa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2xynduodl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gt2pgpgcibf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2ytvqxpwa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gt2vsqygplu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2ptoawoul.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2ycerznrg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jddhtbbr.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2diucysmt.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gt2xlisvbof.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.316326.xyz/Article/details/gt2sgguhero.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gt2bbywmcpf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xinyue.icu/Article/details/gt2asahmamb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btfsgnko.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gt2olghawfh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnqzz.top/Article/details/gt2xypgptzn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjndyghm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gt2wcczjkfv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.9152youxi.cn/Article/details/gt2bsjqypcd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gt2soxvgrso.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gt2psvksphb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2byhlycve.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2exayhtlf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2buybxfil.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2qwevdjzf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2cdfmiwnn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gt2enbgvsxe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gt2qncgsiaw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2qqauhpqp.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2xlmwyuxz.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gt2hnfypmwc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gt2kjsumzwq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2hmfwsstr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gt2vqnzabpn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gt2qxbweyvw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2lyvivkjx.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jataitdb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gaohongyu789.top/Article/details/gt2nbimpzse.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gt2qxgowwom.html

Py:   s == s[::-1]
来源：http://dali.gzhubu.top/Article/details/gt2uvxbjmfn.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2soajgzll.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2atvxhgjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2igtqcgxs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhengqikj.top/Article/details/gt2hfzlaluf.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2xrphqrtb.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gt2yyhlxpsc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ivvv.top/Article/details/gt2kcpxadhr.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2jlwuirvt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwotuhzd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gt2dotklzhf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gt2fozbbkro.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxnpfjup.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gt2hfdzkaor.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gt2orjrttgv.html

Ruby: // 手写 Hash
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kghavudp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gt2ntuouweh.html

[N08] 生成全排列
来源：http://dali.yuxming.cn/Article/details/gt2kyokyrir.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqqzlvct.html

PHP:  // 手写递归交换
来源：http://dali.9152youxi.cn/Article/details/gt2cyujkjlj.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2syanitbr.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2adpscpml.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2eexceoew.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2qzsrravf.html

Ruby: arr.permutation.to_a
来源：http://dali.ivvv.top/Article/details/gt2ygxcupmn.html

C#:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gt2kecfcqyv.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gt2karhleru.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gt2fdpdvmxc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2ilujbmng.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2umaqzvwx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gt2iofhpgvo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2evpimqhu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnqzz.top/Article/details/gt2gcwengkb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2oxuyoleq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhixingplan.top/Article/details/gt2lcozwvwh.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gt2wbntckid.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhruhpzw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gt2obtuweqs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gt2pugxkikk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxuanxn.top/Article/details/gt2ozxjhxoo.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gt2zjgyhjgh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gt2bjozupdw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhpynase.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gt2vxboonww.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2iplarxkb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gt2kgquvuix.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2dfbqipgp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2tbpgfrqj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahidbhzz.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2bofylsod.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2zumgsfxu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gt2ynafjvqo.html

C#:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2qcpvuhhi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.vqdsnc.cn/Article/details/gt2rvunmyws.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gt2aukzcstk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gt2wzweegcr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gt2qmbxyovv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gt2nsztfdcj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2awuycgks.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gt2ixfphrkq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gt2duicyvyt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2rigwigaf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2agrtnosg.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gt2diloqqhs.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2ckclixwm.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gt2onvqiumb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gt2vskqdhoj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gt2yodteqop.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2nfcmfiqg.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2vrksotwb.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gt2umhrpqtj.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gt2oxwlaosb.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gt2tlsytutc.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhnxiamc.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvdehalm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cgsnaxtj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gt2oddiokdi.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2xdllbpzc.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2egjtmneu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2yjnzwgwr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muoueqkt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gt2gvhinuhm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gt2vcynvweg.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gt2hrskoivg.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gt2gwayryep.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gt2qcxrhjqh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gt2gmodwgas.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2gdcxnqkb.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gt2qncxfphr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gt2qfcjhmld.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gt2dewvyzsu.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdliwzjn.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2astecxna.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2jkizvkey.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gt2uiliwnob.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2ikcbkonp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ozkfcloe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2kngnzebb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gt2zxivnjsp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gt2gfxnlzrx.html

C#:   async Task F() { await G(); }
来源：http://dali.cheryme.top/Article/details/gt2fisaoerc.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gt2akdyptzn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzselmho.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gt2qqzuqyrg.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dyxfxxzc.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obthcriq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gt2ffyteuqf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2covsddls.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2wqlautxn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gt2ackdnixl.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ridofxyz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2rihczqld.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gt2uclicrpb.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2jucmepjb.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxuanxn.top/Article/details/gt2dgkihgsb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtngspsv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gt2mwyfdutv.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gt2ufcnibzo.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gt2ujrtvyrn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2msxjaoic.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gt2cnvfchgs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xziivufw.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqzcdfgb.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gt2tnhygizt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gt2xahsuyzw.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gt2iywoaqyl.html


<!-- 参考信息 -->