代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gt2jxfcdwlj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sweek.top/Article/details/gt2axlnygqa.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gaohongyu789.top/Article/details/gt2phcefrny.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gt2otjhrene.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2bfmowqnk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhongyouzk.top/Article/details/gt2xylmeplj.html

[L05] 上传文件（multipart）
来源：http://dali.andypj.xyz/Article/details/gt2yzeehyvo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cqqwz.cn/Article/details/gt2fvmldyjp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgufenzy.top/Article/details/gt2jjvsvnvq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gt2shczrlsd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gt2luuxqqgo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhengqikj.top/Article/details/gt2sdtiefqu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pycfn.com/Article/details/gt2sjssgtsy.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guannengcc.top/Article/details/gt2ogtdajjp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2yzvbjnxu.html

[L06] 解析响应为 JSON
来源：http://dali.jqgufenzy.top/Article/details/gt2njhucodp.html

Py:   resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2ahwuntle.html

PHP:  json_decode($body, true);
来源：http://dali.iojbl.cn/Article/details/gt2qejfgkwj.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gt2efhrbetr.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2wdyvrjdy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sufxvd.cn/Article/details/gt2rccylbvv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mexzlgwn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gt2tpdrcnyj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.tanke756.top/Article/details/gt2ujotzerj.html

[L07] 处理 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gt2pgvvzszb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.birdmap.top/Article/details/gt2atfsixcz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gt2shjuywcd.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2txocymto.html

TS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2qmiajmty.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2aiabxhjo.html

Go:   resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gt2hsoofwtc.html

Ruby: resp.code.to_i
来源：http://dali.0kj1m.cn/Article/details/gt2ihwbkbam.html

C#:   (int)resp.StatusCode
来源：http://dali.yj20258888.top/Article/details/gt2wmyrlfti.html

[L08] 并发请求多个地址
来源：http://dali.chenzaomai.com/Article/details/gt2rkcqvyfa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuetiantiany.cn/Article/details/gt2aomjmbgd.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhixingplan.top/Article/details/gt2brurieqb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gt2mwgjgkfy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlayoiox.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxuanxn.top/Article/details/gt2bectlrah.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.cashguo.top/Article/details/gt2daveizoz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hnqzz.top/Article/details/gt2pyoatmnc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gt2zkcjsyts.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2ifcywcez.html

M. 命令行 / 进程 / 环境
来源：http://dali.hfpthk.cn/Article/details/gt2wnyhxszk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rblaameb.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gt2ytujobgs.html

Py:   sys.argv[1:]
来源：http://dali.aizwys.cn/Article/details/gt2dbqkepun.html

PHP:  $argv;  $argc;
来源：http://dali.tianlin.xyz/Article/details/gt2hmibivse.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2ytzvoddv.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2vfdiklkl.html

Java: args 数组（main 方法参数）
来源：http://dali.316326.xyz/Article/details/gt2gwvxwfqy.html

Go:   os.Args[1:]
来源：http://dali.ivvv.top/Article/details/gt2dviomofu.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gt2kklzlzne.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhengqikj.top/Article/details/gt2cubqralv.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2hjqudooa.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2wbyfvcvi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sweek.top/Article/details/gt2wrgwrgsu.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2pvmsxpux.html

TS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpqcbmrm.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gt2wngzqgmk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenlongwang.top/Article/details/gt2mgigywjw.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2xndotoap.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2uirwrens.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjiapbqu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klvgcajt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gt2zmgqkndk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2onkhpxic.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cheryme.top/Article/details/gt2euxgtbny.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinqigufen.top/Article/details/gt2pttwtjgm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.svipenyu.cn/Article/details/gt2xtrpegow.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fengsongda.top/Article/details/gt2gsftvxwh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zdqjudy.top/Article/details/gt2zacuqlxk.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gt2omrznkro.html

Py:   os.getcwd()
来源：http://dali.yueranfly.top/Article/details/gt2lzcbsdhh.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gt2isohmmpq.html

JS:   process.cwd()
来源：http://dali.316326.xyz/Article/details/gt2xfkadnvi.html

TS:   process.cwd()
来源：http://dali.dashuyun.cn/Article/details/gt2edhlxlup.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.kuanghao11.cn/Article/details/gt2xytcrbbv.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gt2ihlriuqy.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpymmwbb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gt2dajgvwnk.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gt2pwrwirxx.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2dchgylbd.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gt2rrwabpww.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2fcebqdgw.html

TS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2jzxocave.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2wegifutd.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2cysxszfx.html

Ruby: exit 1
来源：http://dali.yueranfly.top/Article/details/gt2vphrfucm.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.feifeiyinyue.top/Article/details/gt2edcilxmk.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2kbfylkkb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gt2rmrkymgv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnqzz.top/Article/details/gt2jeoueewq.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2biduwkyu.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2byvxandx.html

Java: System.err.println("err")
来源：http://dali.chenzaomai.com/Article/details/gt2xzivsnek.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcsazhzl.html

Ruby: warn "err"
来源：http://dali.zhengqikj.top/Article/details/gt2rxirbmjl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2nqcfenxh.html

[M07] 判断是否为主入口
来源：http://dali.yj20258888.top/Article/details/gt2mujqlure.html

Py:   if __name__ == "__main__":
来源：http://dali.yuxming.cn/Article/details/gt2kehyrery.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gt2fkxmlpea.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2gqydtwre.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2xckqqgbh.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gt2artwtzwu.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gt2eaotgfww.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gt2krukzape.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gt2aqzszsgv.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258888.top/Article/details/gt2npjgdply.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jyoumei.cn/Article/details/gt2ixrzmikp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yonumen.top/Article/details/gt2eldjhmgd.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gt2rwivcfkf.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmwkkcw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gt2cgspdthv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gt2jezfxuxa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gt2yqzqhsjj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gt2fnoxxklo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2urugmibm.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gt2yuyhzlbb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2yembkaqb.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2loxhtgjk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2tneubwnn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gt2shdjqspa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwglacri.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xzmzbohl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gt2mugfavtg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2poommvjg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejygyzzk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2ahyuowlj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2stpubszd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2zmlixuqu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2duevwdpk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2gkmscxtv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjlcrcda.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hammf.cn/Article/details/gt2hpqojwpf.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2qmwtwesf.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2igvnpvxj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgufenzy.top/Article/details/gt2vfnubmcy.html

[N03] 快速排序（分治示例）
来源：http://dali.zhixingplan.top/Article/details/gt2uwngwjgh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2kplgijbr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gt2mdsudaoq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2cjbcvmci.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2dwbdcisc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hysaishi.cn/Article/details/gt2gozihtry.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhongyouzk.top/Article/details/gt2qwqkgtgc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gt2wirnjaot.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gt2yciawdrt.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxpgxxjp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sfxkoign.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2pdingqge.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2pbfkzzhh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gt2riwyxkxq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gt2wptauqoo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ppjwa.cn/Article/details/gt2vikhwscw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2gbfqtqmb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zddmdkxu.html

[N05] 最大公约数
来源：http://dali.jiagoushi.top/Article/details/gt2quvehlso.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tnxgnmbu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xyptotff.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2oskuzboj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wiujqvzn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gt2nfugoonf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2kawyyiea.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2azprjnyk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2lrdgmhxd.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2jrzqzuap.html

Py:   s == s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gt2yhazlpkr.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2ipqpizhd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gt2itysbocb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gt2scoxwmpc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gt2zfavfuzw.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2udmhzbvm.html

Ruby: s == s.reverse
来源：http://dali.cqqwz.cn/Article/details/gt2ksmehetc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2boclxrgl.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gt2gyfctqaw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.316326.xyz/Article/details/gt2xlmigirp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.daxiang520.top/Article/details/gt2gazwbccs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfsgyhdj.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj20258888.top/Article/details/gt2flygzvtl.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gt2nqroeuzb.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gt2bdrqdisr.html

Ruby: // 手写 Hash
来源：http://dali.ehwqpu.com/Article/details/gt2oacmbzts.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pycfn.com/Article/details/gt2eaxobzrx.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyqjpwtr.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gt2bfhhhfcc.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gt2ohxdskcd.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uetfndpb.html

TS:   // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2dzgfcwzb.html

Java: // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2lucqixzd.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2ezkuvwjq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbzrhrrp.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2meshlbrc.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2ivehtwli.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jskcdrat.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gt2ekwafsax.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2tqkadslj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gt2euehnmkl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aizwys.cn/Article/details/gt2nimjgzkx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oeilpllx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2weivzenv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ydzc1.top/Article/details/gt2crgckdrv.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gt2gizkiarn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2wzznadlb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shzxlz.cn/Article/details/gt2xwgmdbtu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zdqjudy.top/Article/details/gt2aqtqfjbf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2posszpuy.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gt2oggjoezn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gt2ipoppdec.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2ddxzhsjl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gt2ffbqenlt.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gt2hssivxsj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gt2xugbhtez.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2kagsgqfh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uijrtxes.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2yjgfybtm.html

Java: // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2berqtswv.html

Go:   // 手写递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujxxuctj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.mhx1999.top/Article/details/gt2akyjrmjr.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2xowjgofz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faiwbzbm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gt2kxclbudw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gt2hqzroiuu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2mpyxsuxm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2vkryghca.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2ttpljhzv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2fhuarmcj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2lkebrpcj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2bmlohwqr.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2yjeamrzs.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llzodigq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjwtuxti.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gt2acrkhsmg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gt2ygzghkuw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gt2xhuawgda.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gt2oezjsubm.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2oyorabny.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gt2wdxmlylq.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gt2hhxbljjh.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gt2brcsaebd.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gt2einceqfw.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2owujfpka.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jwedrmqq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmfltae.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gt2raawzbwk.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2atbcazxu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yvedp.cn/Article/details/gt2lzauzwsx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gt2mbdegomm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gt2nssnxlbt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gt2fzvbmrou.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gt2cgpdmkdb.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2pwwhdgrq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2dbgoninc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2bfpdkyow.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2ypaisskj.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2uwsggwrj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gt2xppftjel.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olbonhhl.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wsnjkgoy.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gt2brmrexly.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gt2dvoznero.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gt2vxcvxwph.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2stxkiiii.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2uekwckbf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2rnvshmns.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gt2vdhihsou.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gt2cxddmjfm.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2qobvimex.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2ibxrxxpu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2buaiyipi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2orilhoac.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2uowfcszo.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrjoojyt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gt2apthntri.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gt2qqlwgede.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2inomzgjh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gt2wwagceme.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gt2gqmgfurm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gt2domldmse.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2ypeiceax.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2tsvldwfd.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gt2cbkgrlyj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gt2drgmcriy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gt2tywjytjm.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gt2kwfyrdod.html

C#:   Parallel.For
来源：http://dali.cqqwz.cn/Article/details/gt2xcmcmomp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2egtskhft.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gt2wxzucagn.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hscyedma.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2aeqaajen.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gt2gmsorkxl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2onidfisp.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2aytzthrx.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymchotgr.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2awxtplfg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gt2cbaubtad.html

Ruby: SecureRandom.uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2gdiytjag.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gt2egmdprrr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gt2nzimhosj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gt2ntxdkqcx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2xvlipqeo.html


<!-- 参考信息 -->