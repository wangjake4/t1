代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxxjwgni.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.wangdashe.top/Article/details/gt2vnqmzuko.html

[L05] 上传文件（multipart）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghdhbesu.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbsgdypk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2iamzenfn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpyzandb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shzxlz.cn/Article/details/gt2hgpaiwan.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.svipenyu.cn/Article/details/gt2koixciiw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ydzc1.top/Article/details/gt2lvhtzskx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2kerxqshv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2qyvtfcig.html

[L06] 解析响应为 JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2llqpvcrk.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2qolotyrg.html

PHP:  json_decode($body, true);
来源：http://dali.zdqjudy.top/Article/details/gt2xmqamldc.html

JS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gt2hzpoptoo.html

TS:   await resp.json()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uuzsxget.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yuanzhike.top/Article/details/gt2wmshyajy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2wykcusfi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gt2krfwdgvp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gt2lpibexxd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuueivd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xinyue.icu/Article/details/gt2syfulmpw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xuanzx.com/Article/details/gt2fxkjxuwb.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gt2rjogngwa.html

TS:   resp.ok;  resp.status
来源：http://dali.gotoacloud.top/Article/details/gt2ulvgudgg.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikfwahjh.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2twztvrfy.html

Ruby: resp.code.to_i
来源：http://dali.jinqigfzy.top/Article/details/gt2ezdrwsmz.html

C#:   (int)resp.StatusCode
来源：http://dali.snrcjt.cn/Article/details/gt2zbcmctig.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gt2tmhfmqff.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jgvglqhd.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieueqtpr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gt2apyzcixw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2vhppordi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.haohaochexian.top/Article/details/gt2vtbhzwly.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhengqikj.top/Article/details/gt2yygxiplb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xziqi.cn/Article/details/gt2ngukdrxo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2ruixxjzt.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2zngjgxly.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozwlhcas.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2efivvdsp.html

[M01] 读取命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruqpqjnk.html

Py:   sys.argv[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2rzpkeomb.html

PHP:  $argv;  $argc;
来源：http://dali.mhx1999.top/Article/details/gt2ynjnfrzz.html

JS:   process.argv.slice(2)
来源：http://dali.yuanzhike.top/Article/details/gt2rrwkkzju.html

TS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2tqqehtof.html

Java: args 数组（main 方法参数）
来源：http://dali.nanxuanxn.top/Article/details/gt2egjrfcse.html

Go:   os.Args[1:]
来源：http://dali.fengsongda.top/Article/details/gt2wgbynqvm.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gt2rftvajkb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yuxming.cn/Article/details/gt2abnzaeus.html

[M02] 读取环境变量
来源：http://dali.fengsongda.top/Article/details/gt2zfnqtpdw.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2zywknjqb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2txxfqphw.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gt2kemgolzm.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2gygvmulo.html

Java: System.getenv("HOME")
来源：http://dali.fzhhl.top/Article/details/gt2iudhugjh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2wbvubxya.html

Ruby: ENV["HOME"]
来源：http://dali.jqgufenzy.top/Article/details/gt2gmmijfux.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zkdvwblw.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbkoldyj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kfhtkkvq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jlsjyb.cn/Article/details/gt2aoxkawuv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aibaodan.cn/Article/details/gt2paqxwiuf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2kxmvzbmq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.0kj1m.cn/Article/details/gt2cyspijxv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenlongwang.top/Article/details/gt2qhglydli.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.nanxinkj.top/Article/details/gt2hkqpzqle.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jyoumei.cn/Article/details/gt2igsmkypx.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gt2butsmkhs.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gt2btlujhcp.html

PHP:  getcwd();
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkaknnkh.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2duysjehm.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2bzkbhvus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.aizwys.cn/Article/details/gt2xldtwzdj.html

Go:   os.Getwd()
来源：http://dali.pycfn.com/Article/details/gt2flruohvm.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gt2yoxhdztl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenlongwang.top/Article/details/gt2ykpwlcqz.html

[M05] 设置退出码
来源：http://dali.guowangkeji.top/Article/details/gt2ueaftsqw.html

Py:   sys.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2adlregih.html

PHP:  exit(1);
来源：http://dali.gotoacloud.top/Article/details/gt2qrntwuid.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2hltorelz.html

TS:   process.exit(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuvrqctp.html

Java: System.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2dhkkqlqp.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryxkinej.html

Ruby: exit 1
来源：http://dali.aibaodan.cn/Article/details/gt2wljygslw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gt2evxhkslr.html

[M06] 向标准错误输出
来源：http://dali.fengsongda.top/Article/details/gt2sihimktr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2seefghce.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gt2zzwltsic.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2ktoylgca.html

TS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gt2msiicrkr.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gt2urritwgs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2nxxfqidd.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gt2mfkbanqn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gt2drqbiulr.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vuraloeg.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gt2frdzonxu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2raipckop.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2emugdpuc.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2enymgmtp.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gt2htzktypf.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcxdvfgz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gt2gglfhxog.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gt2zhzayxjm.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jankxbza.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2szdnhviq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2qtbmgmqn.html

JS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqlkayyq.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gt2hqorutcw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gt2ozsnskwj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gt2kevmychr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gt2iumfvcow.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2qljkuutb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gyksbijz.html

N. 数据结构与算法
来源：http://dali.iojbl.cn/Article/details/gt2hqowjuqm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoiwqcvt.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gt2qfwwbfmo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2uojxmtha.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2ogofumwf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2tinrrtzv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2qkirqnmi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gt2gplgklin.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2knfvdhhx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhceisoi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gt2jiqkoawc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jianghu66.top/Article/details/gt2ocgtpvah.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2ugvkbjia.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2lomwqcle.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2vdzgvheo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2iwwjvxjl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxuanxn.top/Article/details/gt2yikdqgnf.html

Go:   slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2nvzukgjd.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2pjaohjxf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gt2upmhmske.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gt2zwcnmkym.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gt2tfzjxbvw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gt2ghcqivba.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjeytzuu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2rbbetnfl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfcntdni.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gotoacloud.top/Article/details/gt2ygoruije.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gt2nbibobtc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gt2rdcldjxx.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2krpoxkxq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2mlfedgtg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gt2wkkkphpy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2ippejxhd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2zzgpzqgi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2rqfcgkos.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gt2eknyzvkz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jyoumei.cn/Article/details/gt2zbsyrocc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2jwkzgzwl.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gt2ibbxhhub.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2yvxjktys.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2urcruxxx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2kcmlccga.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vqiktclb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gt2qxajdtvc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsechsjy.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gt2noyycwba.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cqqwz.cn/Article/details/gt2kengzfps.html

[N06] 判断回文字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2echlsaly.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2jaamszbo.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2nhhufmof.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gt2wuaaeyfw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2rvlxpmur.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2umymlqri.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvjekqwi.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2hqplyptf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2ztswkgrl.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtvjbrzc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2gyyovhkc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2urpuknee.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2jqfobjhv.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2vvbmajko.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gt2mejsmzvc.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slpklxtv.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gt2aejrvuvc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gt2kyfceoks.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gt2bqtksjes.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gt2lwogqjat.html

PHP:  // 手写递归交换
来源：http://dali.chenzaomai.com/Article/details/gt2rcahfkaq.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2fuxhcpii.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2vthcmhlf.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2fnfgadgk.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2qgkcjeoc.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2zfdyptfb.html

C#:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2yulnadxk.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gt2zvoekgoe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2rtcmnwpa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2nqkvjheu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2tteiadcs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gt2vlwcklgw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2urvlacdm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2byihmzyi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.mhx1999.top/Article/details/gt2mmbcjhxd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tian-w.cn/Article/details/gt2klgrcznh.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aflngnqh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnkpdhhk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gt2rvkwhqyb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gt2jxqrpwvw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gt2nttgwyob.html

Java: class Node { int v; Node next; }
来源：http://dali.ybcxt.top/Article/details/gt2iwftbevm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gt2txpskkka.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mthxzwsn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gt2azwosqen.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzzebeck.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2bdhwvxqo.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gt2uxwaosty.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gt2djyywesp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2bnfbrszp.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gt2hkloruqo.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2nbxrezmo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2foimplco.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gt2qnrmdzef.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gt2bzugyqev.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gt2yexiucbo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gt2ttioqwix.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2pnfnntto.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2olhcxnff.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2gjhdvtvm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gt2umzrgafz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gt2kxsulayp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2pjqgwqcy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2mojvibnb.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gt2duufnnbu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ippvxjms.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gt2dlineknx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2bguiizgk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gt2tjklasaf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gt2mgiaweko.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpptldiz.html

Java: new Thread(() -> f()).start()
来源：http://dali.daxiang520.top/Article/details/gt2lygysitt.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gt2vuympcsi.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2zbumemdt.html

C#:   Task.Run(() => F());
来源：http://dali.yuanzhike.top/Article/details/gt2ppfnzojs.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2naocjhbp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gt2njhufctu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gt2biobghse.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gt2bftyzcgb.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rmwhxyjx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gt2zvgboftr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2kanimivm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gt2szosjseh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gt2fddmmnrs.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulgefufa.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vynuqpqi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.vqdsnc.cn/Article/details/gt2paqijcll.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gt2nbfhhwur.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2vwlvaavp.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2dieklqrz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gt2vufrxfzc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2hvzvqjmb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gt2letwifel.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gt2jryftotf.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gt2cwjjtnce.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mqqcrsna.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2ltjjhksa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zefhvmah.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gt2iguuklcf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gt2hcjkkydi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gt2bhxyflvd.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2brlytwpc.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gt2wvnmyvlt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gt2vmaedlgo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gt2qobeqbkk.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2bkbpdnsz.html

TS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gt2mvywmmfh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wykxggzn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvarrnxw.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2pmolhgsr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2gwxwwnil.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gt2nadrllzy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gt2zerydreb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gt2dsrnkezp.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gt2ieksbhzi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gt2lsdyhtxq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gt2ynhurqst.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gt2xxtyhycv.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzotnezi.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gt2skbbwrli.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2rzmyipnn.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gt2pqqoaftc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hlldpvcg.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gt2teabecxt.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gt2mrzvtbku.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gt2fvrdrcgc.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2ajwwcoqc.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2apsapwgt.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gt2mqaeqimg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2pxqebjos.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gt2ccmsexga.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2czodyqar.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gt2bkxxfgfu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gt2gsxtiktz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fosonqhn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hviboyxn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2nywwnope.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gt2jhxfwxlw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gt2kdkrxfyi.html


<!-- 参考信息 -->