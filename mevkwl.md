代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2fdzfzqbo.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnxiangtu.top/Article/details/gt2tropnoga.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gotoacloud.top/Article/details/gt2bphfjyiy.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuetiantiany.cn/Article/details/gt2timyicon.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gt2ymaguecb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hjpdjcqt.html

[L05] 上传文件（multipart）
来源：http://dali.hnqzz.top/Article/details/gt2rkykgitu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cheryme.top/Article/details/gt2bmbwwtcq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yonumen.top/Article/details/gt2okdatvyo.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2zpavbxwn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2ogmewlpe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhoulong.xyz/Article/details/gt2kgoxetwq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2diikxxvb.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.birdmap.top/Article/details/gt2mafladec.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2apyvroda.html

[L06] 解析响应为 JSON
来源：http://dali.haohaochexian.top/Article/details/gt2jdrekxer.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2mrnpmqbp.html

PHP:  json_decode($body, true);
来源：http://dali.tanke756.top/Article/details/gt2jykokwxr.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2rbqcactd.html

TS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gt2mhgkcrjn.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2jisiopyc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2daxtccgz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xuanzx.com/Article/details/gt2asexeejv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2dldyxnmo.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwdyrewf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258.top/Article/details/gt2dxegahss.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.havefunace.top/Article/details/gt2gnboyvbq.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gt2rdsoavqh.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2ihhqazue.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2hdwvnors.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gt2rondpsfm.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gt2jsshowcz.html

C#:   (int)resp.StatusCode
来源：http://dali.316326.xyz/Article/details/gt2yvveqowi.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2nmsgqugs.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.redwolf501.top/Article/details/gt2yacvxqhl.html

PHP:  curl_multi_init() 系列
来源：http://dali.yj202588.top/Article/details/gt2ayxsrtwv.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gt2lxmnbbak.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2eqjockfv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gt2iqmqliuq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gt2afjmsjem.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2tpmsgixy.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2rcznonmc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2vtjvjpcp.html

M. 命令行 / 进程 / 环境
来源：http://dali.meibo888.top/Article/details/gt2rmtwlwnk.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2gzcemgtg.html

[M01] 读取命令行参数
来源：http://dali.dianchejie.cn/Article/details/gt2kuohljie.html

Py:   sys.argv[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2nzlshixk.html

PHP:  $argv;  $argc;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hubtfxxn.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cysakapf.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qaloihbz.html

Java: args 数组（main 方法参数）
来源：http://dali.xziqi.cn/Article/details/gt2tjtiqpzc.html

Go:   os.Args[1:]
来源：http://dali.shuidangran.top/Article/details/gt2cptdxlls.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gt2ghiinmhw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2ucvafksn.html

[M02] 读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gt2krctfhny.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2lxehiulp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrpqicoz.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2dbjopdnd.html

TS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2kabwqbwx.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gt2tiwceixi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnfqppbp.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gt2dkszjlfh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gt2hzmzwkoc.html

[M03] 执行外部命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gbmtbydg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.9152youxi.cn/Article/details/gt2bwmtgbvy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinqigfzy.top/Article/details/gt2pfitppgc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangdashe.top/Article/details/gt2smgyoqpz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gt2qevumout.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sufxvd.cn/Article/details/gt2yjknwjkw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hnxiangtu.top/Article/details/gt2pfpvtfoa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2pzhufgiu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gt2andtxkxp.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gt2tbhrddqk.html

Py:   os.getcwd()
来源：http://dali.cashguo.top/Article/details/gt2usqctvka.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gt2lmqbhfji.html

JS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gt2hhgiihgn.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gt2zhgdfepq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gt2rpcbvyvc.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2tmcgfdur.html

Ruby: Dir.pwd
来源：http://dali.cdnleiting.top/Article/details/gt2jkcqxdjg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnxiangtu.top/Article/details/gt2ovotnqsl.html

[M05] 设置退出码
来源：http://dali.316326.xyz/Article/details/gt2xlccauyg.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2ojoeeeuv.html

PHP:  exit(1);
来源：http://dali.sxryk.cn/Article/details/gt2wyiinobq.html

JS:   process.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gt2hngagebo.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2vpbrbxbe.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlfahosh.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbiqkoaf.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2pnlcejdb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gt2tlozfhyn.html

[M06] 向标准错误输出
来源：http://dali.aizwys.cn/Article/details/gt2ylmmxjlp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ppjwa.cn/Article/details/gt2figrisbr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gt2hgwgzjxz.html

JS:   console.error("err")
来源：http://dali.yuxming.cn/Article/details/gt2comkelag.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2iwjpjtul.html

Java: System.err.println("err")
来源：http://dali.haohaochexian.top/Article/details/gt2xsagytus.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gt2xuhdukzz.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqhjpmgf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gt2jnolwcai.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2mvbzqshk.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gt2ddzffdac.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gt2xetcvsbe.html

JS:   require.main === module
来源：http://dali.jqgfzy.top/Article/details/gt2cfywvazu.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2aorbyqxx.html

Java: public static void main(String[] args)
来源：http://dali.iojbl.cn/Article/details/gt2qooeifif.html

Go:   func main()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzswuigt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkfnbkfg.html

C#:   static void Main(string[] args)
来源：http://dali.fzhhl.top/Article/details/gt2iwodvsws.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gt2vapmhebc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gt2fbwmstfy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2ylpujjyy.html

JS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2tealmsys.html

TS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2uhngnyin.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258888.top/Article/details/gt2zbaegqcs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2aerduuiy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gt2trukwkcw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gt2nlkzqdef.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2tozgxrps.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gt2hmaycefu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2pkoyrpyg.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkxajjxb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2quxxzbve.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gt2adyuzpbe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjklxabo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2blyvynjb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2syeqivet.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2xjrcbgwi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gt2sffsyckf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhjrmccz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gt2syimrroc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zriiaagp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gt2uqjsteyk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gt2drwknkzd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2vjrliukl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yvedp.cn/Article/details/gt2kdrgersb.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2yyhxuaxi.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gt2ednpflmc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gt2simyzukj.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gt2pqsvzipt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2mgxixmnz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gt2vgkpnctx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2jwtxjcmu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2mvihevwd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gt2cfahanid.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gt2pgkqorgh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jianghu66.top/Article/details/gt2xsyzkncg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpkpisey.html

[N04] 斐波那契数列
来源：http://dali.kuanghao11.cn/Article/details/gt2ououqvck.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2iadzrgoy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yongpay.top/Article/details/gt2kiohukmd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2snwkdqck.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2kihjheby.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2tvvhbieo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zdqjudy.top/Article/details/gt2nbejvtmf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2dkvszcuk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2gpnygtki.html

[N05] 最大公约数
来源：http://dali.jinqigufen.top/Article/details/gt2awxicfrg.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2yxeuicmt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gt2opjepkja.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2dpsxavyh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2dqtdshmk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gt2pxsgxjhv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gt2jtbaavxu.html

Ruby: a.gcd(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nruudyve.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkbvnljg.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2twfetejm.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2ilpsnvnu.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2jnvoezfq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2ukbgxvos.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2xgxyjnuh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gt2yumtqvtu.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gt2mplebahu.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2wgdwxgka.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2vkxakmcp.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gt2ejvjlbly.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jlsjyb.cn/Article/details/gt2iizuvwcc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gt2cblruwhg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gt2rcoyctsf.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenzaomai.com/Article/details/gt2kepustxf.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gt2jtxwqywf.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2xlxerqzf.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gt2ipkrfwrx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhoulong.xyz/Article/details/gt2ochkecod.html

[N08] 生成全排列
来源：http://dali.snrcjt.cn/Article/details/gt2yakrznfo.html

Py:   itertools.permutations(arr)
来源：http://dali.shuidangran.top/Article/details/gt2ncmmuogw.html

PHP:  // 手写递归交换
来源：http://dali.bjfxy.top/Article/details/gt2zevkdfnr.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2odioetuw.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gt2oyenptsa.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpkkmljx.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2vmxnthyt.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gt2kdfwstjt.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2shosdlhf.html

[N09] 栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2qdukqsok.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gt2sworupyh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2fbpxkoyd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gt2zqpvlrjf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gt2xnfbbgor.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2hofjipeb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gt2ukgxnmki.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gt2kfydyara.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gt2ijmdtxwm.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gt2pgfidoyc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2umxrbxyu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkjzjzlo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2rnjaqwdy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhixingplan.top/Article/details/gt2kbrgdcwe.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gt2ahcbffot.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2kfyasonz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cqqwz.cn/Article/details/gt2ennajuee.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2nlywvgyw.html

[N11] 二叉树中序遍历
来源：http://dali.gotoacloud.top/Article/details/gt2ijginyip.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjafmhjb.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gt2rjthghmx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2xtxbqheb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvezlxpo.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2xafifsmn.html

Go:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2ssnytrow.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gt2xpqbadvz.html

C#:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2rachaktq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gt2ryabyicb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhoulong.xyz/Article/details/gt2hurbspfo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gt2ngnvqmdu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2iccakzln.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2hsexfste.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gt2rwgridaj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2zcfalxfj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2bkhxprhs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2wdwdlpss.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ynwkiwgi.html

O. 并发与异步
来源：http://dali.pycfn.com/Article/details/gt2ontcwwiw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ostlolnc.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trpauzsr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2czwnhsxf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gt2xqcqtipj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hammf.cn/Article/details/gt2ermaavms.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gt2pnhilnmr.html

Java: new Thread(() -> f()).start()
来源：http://dali.mhx1999.top/Article/details/gt2dwobvgea.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gt2gopqvhxv.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gt2olkmejij.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gt2tvdhcuff.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gt2sujbnhbi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjnzpkav.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gt2jfdgtobq.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2pamurcoj.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2wttalnwr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzycthil.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2gyvunqip.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjruvifl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hywenlv.cn/Article/details/gt2bmsbucjp.html

[O03] 加锁保护共享数据
来源：http://dali.bjfxy.top/Article/details/gt2onpzwkfc.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2kxcfwvvi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gt2crbxsmzq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gt2wgyoxbvu.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2plupdolv.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcrrvday.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gt2paxitfzb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pftlwsqa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lajsyhgw.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gt2xobxmiko.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aaskhetp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gt2waoljtci.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2avelezpi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfdzmnhr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gt2cpemooiw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gt2ovxorhvt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gt2viwmzzks.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2sspophmg.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gt2ljeblkyb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gt2ivsfedzt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2ewaqftcw.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2idmirnei.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2bmfhrzvt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gt2mgzrvtee.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gt2wpkhgphk.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gt2wupxbubd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258.top/Article/details/gt2yusaepkz.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gt2qhdwikgp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gt2hdvhacou.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2jomuwurp.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2uhlhcpli.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2gbpdurvn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gt2dsyhfjqx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gt2ikidfcpd.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gt2piuvlmdb.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gt2vkwlqaus.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2sdgufydd.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2awvkwznj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2yyvnutrg.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2dvgmsger.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gt2icciujcn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2cjpkirxi.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2uepcapcv.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gt2xjafdjzp.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vncrwdge.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gt2lqphxqdh.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2qdqcnjfc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2wyktwvse.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gt2sbuwjgqr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gt2zcvyctil.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2cqdeaolk.html


<!-- 参考信息 -->