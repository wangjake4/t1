代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gt2dshomnug.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhengqikj.top/Article/details/gt2pusgathy.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gt2dxhqxllq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gt2rklnfsau.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gt2ljuvzrij.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gzhubu.top/Article/details/gt2mxhokncn.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gt2qmfjocpm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2eibeybfz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuanzhike.top/Article/details/gt2dpzkvayx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2flwoffoc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yonumen.top/Article/details/gt2lphlcuvs.html

[L06] 解析响应为 JSON
来源：http://dali.xuanzx.com/Article/details/gt2ukqgsqui.html

Py:   resp.json()
来源：http://dali.yueranfly.top/Article/details/gt2jeasnwel.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rxdtolda.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2ydfpwlfb.html

TS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2ctyonhvc.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2jhtaiado.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.quarkkingdee.top/Article/details/gt2lqvugkyy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.andypj.xyz/Article/details/gt2epduxdyx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2titlkrus.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2pstzsdgf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2zamherac.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.redwolf501.top/Article/details/gt2kqgjczgm.html

JS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gt2svwaioat.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2oopjfoxd.html

Java: resp.statusCode()
来源：http://dali.meibo888.top/Article/details/gt2ruxxflsc.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gt2kivjomwi.html

Ruby: resp.code.to_i
来源：http://dali.xuanzx.com/Article/details/gt2hwrqwepb.html

C#:   (int)resp.StatusCode
来源：http://dali.hfpthk.cn/Article/details/gt2giuwwufz.html

[L08] 并发请求多个地址
来源：http://dali.tian-w.cn/Article/details/gt2mmtlvynm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hywenlv.cn/Article/details/gt2ugmucizf.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gt2bzwpqdva.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jlsjyb.cn/Article/details/gt2kyyfonco.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpimzrsb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.bjfxy.top/Article/details/gt2zqbwnwrc.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yanxiufei.cn/Article/details/gt2uhvvypgq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2xjvrxawh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2jrjqamaf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2gqstikmf.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gt2dbwfcxaa.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pwhwdhqv.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gt2sumsqdfp.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gt2jdxfiupf.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gt2xlfizdgg.html

JS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gt2mbamuarc.html

TS:   process.argv.slice(2)
来源：http://dali.yj20258.top/Article/details/gt2ynvmafyz.html

Java: args 数组（main 方法参数）
来源：http://dali.cdnleiting.top/Article/details/gt2qfvijtxl.html

Go:   os.Args[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2ayavinii.html

Ruby: ARGV
来源：http://dali.yueranfly.top/Article/details/gt2jyzlsocg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2dxwttonz.html

[M02] 读取环境变量
来源：http://dali.redwolf501.top/Article/details/gt2vywhmxhk.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2yclcgcbt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gt2qmwkxzui.html

JS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2usqsjdbt.html

TS:   process.env.HOME
来源：http://dali.zhixingplan.top/Article/details/gt2tnnhqzsz.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gt2kejbwkgj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2gvjzeuco.html

Ruby: ENV["HOME"]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pjlncbpb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2ietfvefy.html

[M03] 执行外部命令
来源：http://dali.shzxlz.cn/Article/details/gt2brqqaddi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2flpjfdfs.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cheryme.top/Article/details/gt2qsvvisvr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2dpumiiui.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.havefunace.top/Article/details/gt2mppbcexk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gt2neoudbaa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj20258888.top/Article/details/gt2iuysupph.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyntchnw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gt2ipxyvmqc.html

[M04] 获取当前工作目录
来源：http://dali.zhixingplan.top/Article/details/gt2jqviupst.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylymtcpb.html

PHP:  getcwd();
来源：http://dali.zhongyouzk.top/Article/details/gt2rcdiwbkf.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2oykuaikv.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2peaiazyk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hysaishi.cn/Article/details/gt2ymeptuoe.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gt2efidprcw.html

Ruby: Dir.pwd
来源：http://dali.bjfxy.top/Article/details/gt2wxgeamtx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gt2zaeplplj.html

[M05] 设置退出码
来源：http://dali.hammf.cn/Article/details/gt2gjmdrgmn.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2kpxhnhym.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlgtgofv.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2pftbkqso.html

TS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2ieymjhtt.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gt2incngwqk.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2vcixpnzf.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gt2gcdjqdps.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gt2zjptwwgu.html

[M06] 向标准错误输出
来源：http://dali.bjfxy.top/Article/details/gt2knxfhudy.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2hgezpafs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dianchejie.cn/Article/details/gt2hloddkja.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2xbrxtjkw.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2leoqymyc.html

Java: System.err.println("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xquoqhqj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gt2jmzkxyed.html

Ruby: warn "err"
来源：http://dali.cdnleiting.top/Article/details/gt2eywtjqjd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gt2mwuergxv.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gt2vahiqzsw.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gt2xxoygoac.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2axxphggq.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gt2kdztmskg.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gt2jmvcgioe.html

Java: public static void main(String[] args)
来源：http://dali.cashguo.top/Article/details/gt2ccpitbrp.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysldtmbq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.svipenyu.cn/Article/details/gt2axfqqinv.html

C#:   static void Main(string[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2xduundvn.html

[M08] 获取系统与运行时信息
来源：http://dali.yj202588.top/Article/details/gt2bnssrekp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuanzx.com/Article/details/gt2xbefigwc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.guannengcc.top/Article/details/gt2bxlufvyk.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2gppifnbd.html

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2mfbwryxf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.316326.xyz/Article/details/gt2bfpmfmji.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2vakryvda.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2xbhsnvbm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kajhzeuk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2akioseix.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2pqyqzboi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2gljllbqw.html

[N01] 二分查找（有序数组）
来源：http://dali.316326.xyz/Article/details/gt2ofqlgnpg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2pikafcdr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuxming.cn/Article/details/gt2njugeuls.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2svvywuev.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gt2dltznkdt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uoliiwvs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gt2bbjimhug.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gt2ykukbohd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2ywqinnwp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gt2qhfndsrb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vziqkohu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qfrmndkx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2iaatvyjf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gt2vpegqeia.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cheryme.top/Article/details/gt2fiuyrzwi.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2vwgsugto.html

Ruby: arr.sort
来源：http://dali.yueranfly.top/Article/details/gt2ujnzvcxu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gt2dnjkklio.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gt2cxjghhmc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zlqiyanx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gt2ilfdvskd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2dqmlmagj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gt2ixppxyhp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gt2iruypqqx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gt2mkuamcvh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gt2lrcjwhrs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tianlin.xyz/Article/details/gt2imlqvbuy.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gt2qwxctowr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gt2rwhkcgrm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2bsfosqdz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2mhzrwkue.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2gxlshrpo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gt2irbfdnpm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsojtwob.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gt2ymujvjzt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gt2wdkswvii.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gt2vwwcmvyb.html

Py:   math.gcd(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2sxtoxowo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izvsytxo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gt2jagpzser.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcumqxjn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2rtfsmyeu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivirqjyb.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gt2mcselyzf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gt2thulolqc.html

[N06] 判断回文字符串
来源：http://dali.jianghu66.top/Article/details/gt2ieabtdax.html

Py:   s == s[::-1]
来源：http://dali.xziqi.cn/Article/details/gt2yymvrfdk.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2qhdojadu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2qfdegtbr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2pdlrfppf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gt2lkheimib.html

Go:   // 双指针从两端比较
来源：http://dali.0kj1m.cn/Article/details/gt2imgscaog.html

Ruby: s == s.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pupntots.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daria6918.cn/Article/details/gt2slihvmjo.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gt2aewccyku.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gt2dbxveies.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gt2kkhogspo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2regzcoue.html

TS:   // 手写 Map<string, number>
来源：http://dali.aibaodan.cn/Article/details/gt2pszktoqv.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gt2jslnqqxy.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gt2qoscluas.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gt2ijpewllb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yonumen.top/Article/details/gt2lwquqlcs.html

[N08] 生成全排列
来源：http://dali.zhixingplan.top/Article/details/gt2xtkslfvc.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gt2pzjxihvs.html

PHP:  // 手写递归交换
来源：http://dali.hysaishi.cn/Article/details/gt2sggawmek.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2ajacnepc.html

TS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2ldssmult.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2cikmimpe.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2bsrhblgi.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gt2sekzecjv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oigdtiee.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2xccyzevd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2ikmertke.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2msoqbqld.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2frwisdby.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gt2tkgyakqm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2rjyfulww.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gt2ixypeqhc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2omwgwpyl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jiagoushi.top/Article/details/gt2ixvagdmr.html

[N10] 链表节点定义
来源：http://dali.havefunace.top/Article/details/gt2mpnigkof.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.smart0.xyz/Article/details/gt2lhaovhnv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gt2oapjxzdk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gt2twhtchgt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gt2pwexkgxw.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gt2mgtyngcl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jyoumei.cn/Article/details/gt2rxghorce.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gt2oimmltvd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gt2rypycwxj.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gt2yzqyehuo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2nxcgopvs.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gt2iszcufuc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2plohqfah.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bqdkbcth.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gt2arbpdkfg.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gt2wtwekvoo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pdcwqhob.html

C#:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2zwhpfroi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gt2vysjccbn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fzhhl.top/Article/details/gt2zwxtlqdi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gt2jcywyvmh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2jekbqdoj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2nlwwkovz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2ukgrzqmd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2zpnnkpag.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwkzefpw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2mwkwexmj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2arrvuhdv.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gt2sscchdxr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2tipqqzmv.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syuixvdk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cqqwz.cn/Article/details/gt2jtgfiewc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gt2oxuxnmly.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gt2qqkwhpwa.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2kulkggny.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gt2pccbqfbq.html

Go:   go f()
来源：http://dali.gaohongyu789.top/Article/details/gt2uppdxqon.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2fpmejrcs.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2pftqwflo.html

[O02] 使用线程池
来源：http://dali.c1oappe.top/Article/details/gt2occunwjb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gt2azhgfvtw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2dcojuxie.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2qccnbmtt.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gt2bzifxcop.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2rvyizvlm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2fryvtvtk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gt2mkdfmvty.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fpmtlwbq.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gt2aawgivtx.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2cuslixak.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2agbtihsx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gt2gypvfvom.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2bryccosl.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2wbjptzyr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gt2aaybzbod.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuanzhike.top/Article/details/gt2wznavcgr.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2akuwosbj.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gt2yohzebla.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gt2snwrhctm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gt2jumgjeii.html

JS:   async function f() { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2tmiruzay.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2mnrtekhl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gt2mkxhegnw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upufddss.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2bfdjvtrd.html

C#:   async Task F() { await G(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ktbgoehx.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gt2exkyndjn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gt2cwdmcjiw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gt2jpfbmqpm.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gt2aripcofz.html

TS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2xsidexfe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zdqjudy.top/Article/details/gt2qulkpwgs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2uhxqmegy.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2sejxdpbi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2pyjxslpy.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qumlkukv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gt2qgqooeyb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvmfyqmv.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2hsdmpxyn.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2fqgbnphj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gt2ptqanpmg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gt2rlfoxcqs.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gt2lcrqmrlo.html

C#:   Parallel.For
来源：http://dali.jqgufenzy.top/Article/details/gt2ymizkeod.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kjbjgxrd.html

P. 常用工具函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2dgjmuaic.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlllmnlz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fpebzbzu.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2cajwkizm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gt2hsolbbwm.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gt2xbahnrdu.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2ctrausdq.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gt2cvdkomdn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gt2ipndxfmb.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2okrcvojv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gt2miyoscmp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gt2cmkpstjp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gt2zufyhzyp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2laeewefo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gt2ndljpwim.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2uwkoypps.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2fmlkeobo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gt2wnibcxgr.html


<!-- 参考信息 -->