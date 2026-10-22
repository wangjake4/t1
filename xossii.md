代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gt2rukewueh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.guannengcc.top/Article/details/gt2gigsfrdf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gt2juhjmmpb.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ppjwa.cn/Article/details/gt2mxfinvtc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gt2jbnbhvwr.html

[L04] 设置超时
来源：http://dali.316326.xyz/Article/details/gt2prcxrpjz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajmzgdqu.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.guannengcc.top/Article/details/gt2nhuxueps.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2wmmjsbth.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gt2uifkdyxu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yj20258.top/Article/details/gt2uckfuffj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqwbjgde.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.haohaochexian.top/Article/details/gt2kteykezp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gt2vmgmutze.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gt2mabmqzqo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.nanxuanxn.top/Article/details/gt2qlromuvp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gt2pjfgamri.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2udodegtz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gt2ezrqqftu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gt2fxsbyllu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.bjfxy.top/Article/details/gt2inmraybd.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.haohaochexian.top/Article/details/gt2rbqxjbbx.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2wioafibe.html

[L06] 解析响应为 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxyozgvh.html

Py:   resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2khseynln.html

PHP:  json_decode($body, true);
来源：http://dali.aizwys.cn/Article/details/gt2fxsrgrkq.html

JS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2dzmmpzdn.html

TS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2kzhdyxqx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gt2qgoyausg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.birdmap.top/Article/details/gt2tejrfrbu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gt2kakajqal.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sxryk.cn/Article/details/gt2hphcytbk.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gt2lmgbkrzw.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hammf.cn/Article/details/gt2glmpkmcp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2qnddwjxe.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2gzbsqexy.html

TS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2jplhudoy.html

Java: resp.statusCode()
来源：http://dali.chenlongwang.top/Article/details/gt2vfslsszv.html

Go:   resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2qlmawinl.html

Ruby: resp.code.to_i
来源：http://dali.daxiang520.top/Article/details/gt2uookkllk.html

C#:   (int)resp.StatusCode
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwrdyujr.html

[L08] 并发请求多个地址
来源：http://dali.nwbrower.top/Article/details/gt2yskraepi.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.vqdsnc.cn/Article/details/gt2vjyuupqt.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gt2ourafyvq.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gt2lueovssa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2agtpsplz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2vthgbiro.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxinkj.top/Article/details/gt2phlwhsvx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gt2ynmozwjz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2shzbogzv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ugwkaahi.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gt2piwdguas.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2bzdckjeg.html

[M01] 读取命令行参数
来源：http://dali.shuidangran.top/Article/details/gt2suxwsxqx.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gt2etcozkds.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2qeotcmmp.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2muqopasw.html

TS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2hlecsqgs.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2djlpqowi.html

Go:   os.Args[1:]
来源：http://dali.andypj.xyz/Article/details/gt2neshqwwo.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gt2qzglfoml.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2cnchlagr.html

[M02] 读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2mwbzhife.html

Py:   os.environ.get("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwkrfssq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvzouukl.html

JS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gt2qgvmuind.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2yooebscl.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unevzrta.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2xzpxdqzb.html

Ruby: ENV["HOME"]
来源：http://dali.gzhubu.top/Article/details/gt2idlrsamj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2oroahpsj.html

[M03] 执行外部命令
来源：http://dali.zhengqikj.top/Article/details/gt2kabblsgh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vortvxta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gt2ervudvca.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.andypj.xyz/Article/details/gt2okpdslnp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shuidangran.top/Article/details/gt2qzaulyda.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jyoumei.cn/Article/details/gt2yjmjvwqr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2nuyvrtyq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.guowangkeji.top/Article/details/gt2qtzegtnw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yvedp.cn/Article/details/gt2vzcolinp.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gt2azwfzvjn.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gt2wxfisodn.html

PHP:  getcwd();
来源：http://dali.yonumen.top/Article/details/gt2wjagqohl.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gt2edkgievn.html

TS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gt2utgkofsb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2sqsebqrb.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gt2ondnlwpq.html

Ruby: Dir.pwd
来源：http://dali.hammf.cn/Article/details/gt2jedoxknz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhixingplan.top/Article/details/gt2tasareet.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2etjsdots.html

Py:   sys.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2lyrysfsn.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gt2cudnkygw.html

JS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2mvyutbde.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2zifzehmx.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2rtaxykjs.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gt2dlbuzecl.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gt2yhcjazgg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.c1oappe.top/Article/details/gt2wczfphpx.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gt2kbqflxnz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2znqjaahj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gt2keeztgyu.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2gqwkjtrf.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkpyrwds.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xretlchm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ehwqpu.com/Article/details/gt2thrvnndq.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrrasamj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2rbaosobn.html

[M07] 判断是否为主入口
来源：http://dali.havefunace.top/Article/details/gt2bhwuveba.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gt2zparerpo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.andypj.xyz/Article/details/gt2ebkjwfhp.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2chfciwvb.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2fwkzpexs.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2rqrjxvxs.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gt2qlqcchfu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sufxvd.cn/Article/details/gt2asfcaiui.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2rluxfvwv.html

[M08] 获取系统与运行时信息
来源：http://dali.yonumen.top/Article/details/gt2rpwopsdz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gt2kcwelbjt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gt2hsfhdyuy.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjilirjb.html

TS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2gvcvzvjg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2tiejuqky.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2xwlgmutw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gt2auycajrj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gt2lkznhweq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzxppgwc.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gt2qcvfbiof.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2xpiczzqg.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gt2pahdmtzi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2zzhpmsom.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2esiadtdi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2jwozlfyw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2tlwwfxjy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elurxlcw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2dlukobhw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gt2vgffijyr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2uwontntc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gt2fwvibmaw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gt2wudfzpba.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gt2tutlvpub.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gt2ksuwppgb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gt2zmnnpylz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2xndlyhdy.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2fpqldutm.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gt2ahqurxtj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gt2thrhgkvs.html

[N03] 快速排序（分治示例）
来源：http://dali.jqgfzy.top/Article/details/gt2qflsutoi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gt2ooujyuie.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2bycifhgr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cofngnhk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2mpasheum.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etttfcvw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbunezog.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tanke756.top/Article/details/gt2jexuakpm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gt2jgnctkny.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gt2wsozldxz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2jyguoxdl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2cyzsgnuk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2vwzehwkk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gt2apsmmtze.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2whbwwgle.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gt2updtiyvd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gt2wawholdr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2jnbgdfmh.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gt2ffgydqvu.html

Py:   math.gcd(a, b)
来源：http://dali.havefunace.top/Article/details/gt2wpxppvih.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gt2jjnwzhae.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gt2ssskhjvu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2kvuklmaj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gt2vzbwokqy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2aoymbmrt.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2eohiqsic.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gt2zzphwafu.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2arkrhcmq.html

Py:   s == s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2afaiarad.html

PHP:  $s === strrev($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2fqulzzgo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zapxbaya.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2aaklnqhl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohyltzkq.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gt2hyeotwjz.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2joxxoyun.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gt2godufsaq.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2aibcvqtz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2cbilboae.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.vqdsnc.cn/Article/details/gt2hboaqydy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gt2zehcrvnz.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gt2mqukblwy.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2zybkdfoo.html

Go:   // 手写 map[int]int
来源：http://dali.havefunace.top/Article/details/gt2fyoidyrp.html

Ruby: // 手写 Hash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtsggdpa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2quanezhi.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gt2mupkrgpb.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gt2tttfpeel.html

PHP:  // 手写递归交换
来源：http://dali.fzhhl.top/Article/details/gt2ucxfdlfi.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2adrmysdq.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2skirhevj.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2obohpoyt.html

Go:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2gjtuutii.html

Ruby: arr.permutation.to_a
来源：http://dali.nanxinkj.top/Article/details/gt2zchtjpnx.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2tekwogsr.html

[N09] 栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mieexeth.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cashguo.top/Article/details/gt2usdrsyju.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2hhjrjlfc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2zginjjdi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2jstwdnfg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gt2nmzapdgt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gt2claeefdc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2yyrmxpnm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2rpvgfaha.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2vnpijtbr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gt2xsbrghka.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jianghu66.top/Article/details/gt2repdmbfi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gt2pprflusr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gt2tmrkkmpj.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gt2kuxzvyps.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxrltvdz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsldehhu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gt2wjozjyaa.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2xbdietjw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2exsjnpal.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gt2ikasdsgf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfscfazn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2ydysdonb.html

Java: // 手写递归
来源：http://dali.xziqi.cn/Article/details/gt2znjrbqwn.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2izwagwmm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gt2ktnsvvqo.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2exymzkva.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ybcxt.top/Article/details/gt2fkutpwwy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2cmwijdwb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqugpmfo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2xupqoufi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2yyqtrvmw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2oihwfyxv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gt2odpfxuog.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gt2jdpfvwox.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2iqfhytie.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2fkymckhv.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gt2qmbbvszd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2tgbzsghu.html

[O01] 启动一个线程
来源：http://dali.hywenlv.cn/Article/details/gt2pfbzbnwx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hysaishi.cn/Article/details/gt2rwbxdhgu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gt2dxzudpip.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2ljvwjwwp.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gt2kbfxcvjt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gt2ifauclsx.html

Go:   go f()
来源：http://dali.cdnleiting.top/Article/details/gt2rituwvrd.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2xyprfvck.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gt2qemteivc.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gt2ftsysfya.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2xpornfrw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gt2hsxqqodx.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2plhudhkx.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2pcercusu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gt2emngmdon.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gt2ymvqmasl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gt2uekrnmkg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gt2aowxpiow.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gt2tatjngbu.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ozzngdzo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gt2xjovrkqw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gt2tpxqvxvb.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gt2ktrntupl.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2rtmqgdiw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gt2saickibg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gt2dyunjxxr.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gt2npmploww.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gt2apxqayby.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gt2vvkdqvkj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gt2jayfgykj.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2iwropxqm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2bfrsqmea.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gt2glpfdbok.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj202588.top/Article/details/gt2drqivqiu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gt2xdpwkzsr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2yttozyuv.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gt2iyhgtbrl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2mdmmvstk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2raqjshta.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2nyslxgdj.html

TS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gt2hqiyulwp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gt2hrvcyzgm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gt2urqtljeq.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gt2lzsrazuo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gt2yvnfmgxn.html

[O06] 使用进程池
来源：http://dali.ydzc1.top/Article/details/gt2ddjiopfc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gt2udifmdve.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gt2tdwoexan.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ycftlnxd.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2mnbyjwbq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gt2lorssatu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gt2fdzbzuzs.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gt2pqikktap.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gt2ullcbxuj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2sifrypmg.html

P. 常用工具函数
来源：http://dali.jyoumei.cn/Article/details/gt2jpwwncpf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2uorknlsy.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gt2wrbygmzx.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gt2vyryyphm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2vodokgjh.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gt2oigksbig.html


<!-- 参考信息 -->