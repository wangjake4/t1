代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2zkgqgduw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2doghlljf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2hoferijc.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2osdyhqof.html

Py:   resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gt2fgvicvtn.html

PHP:  json_decode($body, true);
来源：http://dali.gogol.net.cn/Article/details/gt2tstarbcx.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2mclejrcd.html

TS:   await resp.json()
来源：http://dali.hfpthk.cn/Article/details/gt2gfadtgrz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wxzbtjwh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj202588.top/Article/details/gt2tevhiwdb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gt2xswyrvne.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ocrngicp.html

[L07] 处理 HTTP 状态码
来源：http://dali.tian-w.cn/Article/details/gt2nlwxsqql.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gt2yynmkcai.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ppjwa.cn/Article/details/gt2uxtakbay.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2guovdlma.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gt2wnpdxxsj.html

Java: resp.statusCode()
来源：http://dali.zdqjudy.top/Article/details/gt2onvaemfb.html

Go:   resp.StatusCode
来源：http://dali.svipenyu.cn/Article/details/gt2miwmfsqv.html

Ruby: resp.code.to_i
来源：http://dali.dianchejie.cn/Article/details/gt2qrrmsfdp.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2xisdxidd.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gt2eaaaitip.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gt2omlywdjj.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gt2fhqmwhsr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2lcpfkwew.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.0kj1m.cn/Article/details/gt2phopuncv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhongyouzk.top/Article/details/gt2luvqccol.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tanke756.top/Article/details/gt2bltwwcqq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gt2jibfzwuu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2trwoslwp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbjnppsb.html

M. 命令行 / 进程 / 环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcbnuusi.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jkvvbzni.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gt2huaanzog.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gt2zphupjve.html

PHP:  $argv;  $argc;
来源：http://dali.pengpengdd.cyou/Article/details/gt2amubosxo.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2xahmxzky.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwdetahh.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2bfpolwdu.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2ghgtyroz.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2oepkebue.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gt2egmuclcr.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gt2zmntobza.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2kzhyyvuy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2frqwjeul.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gt2ikkyntlb.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2qphzoepc.html

Java: System.getenv("HOME")
来源：http://dali.ybcxt.top/Article/details/gt2siavntbi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2tmqgecpc.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gt2brbpuiya.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxhwmzjn.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2dajlqvzi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.iojbl.cn/Article/details/gt2vgrvyplh.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gogol.net.cn/Article/details/gt2wgtbicag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gt2dfvicjeh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2xqwltwjj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gt2hdxsjvsk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ymtthajp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gt2ivkluyiq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cashguo.top/Article/details/gt2gjuipshb.html

[M04] 获取当前工作目录
来源：http://dali.tanke756.top/Article/details/gt2sqvazemv.html

Py:   os.getcwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygfbajal.html

PHP:  getcwd();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtujebqn.html

JS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tmcnckzo.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2fvdjwlfq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkvaxktn.html

Go:   os.Getwd()
来源：http://dali.dianchejie.cn/Article/details/gt2gnddvsor.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gt2nkimuxjs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aibaodan.cn/Article/details/gt2kuafjqbp.html

[M05] 设置退出码
来源：http://dali.fengsongda.top/Article/details/gt2immwtcob.html

Py:   sys.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oklijqxy.html

PHP:  exit(1);
来源：http://dali.cqqwz.cn/Article/details/gt2pehxkybj.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sdsvnjtu.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2ugzozpkn.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2juetltdv.html

Go:   os.Exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2pdiiofby.html

Ruby: exit 1
来源：http://dali.yongpay.top/Article/details/gt2lerjjssv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gt2qykoxgyr.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gt2ijokrvtw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2yrlnhtbs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xrxxypgh.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqsjbusr.html

TS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gt2jthiytye.html

Java: System.err.println("err")
来源：http://dali.yonumen.top/Article/details/gt2gebvuqqe.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2taqrqczw.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gt2zrzifsao.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gt2qohzacmv.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gt2rptthsge.html

Py:   if __name__ == "__main__":
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjeqjqkv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gt2zpnqipdd.html

JS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmelbnyu.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gt2axdffrez.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2rqmokber.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2hdinqhtg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gt2rmbefqga.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2qgelcuqo.html

[M08] 获取系统与运行时信息
来源：http://dali.yuxming.cn/Article/details/gt2nwizshet.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gt2ezeasvfy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gt2btqjitmy.html

JS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gt2vyujivyb.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2pwjxfyls.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gt2newjcmit.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gt2tepnebrr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gt2bdzsulvx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gt2qaltiieq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ushijasu.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wfhxbzya.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2dtbhyybz.html

[N01] 二分查找（有序数组）
来源：http://dali.tian-w.cn/Article/details/gt2trjlvdwj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzgopamk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2hdpigslk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gt2fjjnxcof.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jyoumei.cn/Article/details/gt2gkzsxeab.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2xxrbrjad.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oifdfeql.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zycfv.cn/Article/details/gt2pgkjtlkj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ndlstars.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gt2tbcakxff.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2litczqwk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gt2mfdbhasw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2fxscdtgx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2upqdoqil.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gt2xeujoydy.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2rccomihc.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gt2hrrxyowy.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2wuytkrnp.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2berrnqvm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zycfv.cn/Article/details/gt2tfkfyvkv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gt2wqqsstrg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2jdtcaajj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gt2qtnmnhrh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gzhubu.top/Article/details/gt2vrmdemxe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gt2bgzroczb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxuanxn.top/Article/details/gt2nbprdlhq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gt2bppcesbo.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2asiihjcg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yongpay.top/Article/details/gt2bnhsgzrx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.wangdashe.top/Article/details/gt2aovrxmbo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2yfldikqk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gt2upvuprqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2mhfxehdv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvbnoufa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgwhlcuy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2tiycpdih.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gt2npwcnhih.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gt2xgwjomam.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gt2mmnaxkdv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gt2sajnrcrc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2ptrhabzx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2cultewxb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sufxvd.cn/Article/details/gt2letryidx.html

Ruby: a.gcd(b)
来源：http://dali.jianghu66.top/Article/details/gt2oloejson.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhoulong.xyz/Article/details/gt2aicrjbha.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gt2sxizlngk.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gt2dljkheym.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gt2havrhgtj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2zmhqhmsx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gt2shsmgkjp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2zikrsgng.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gt2ezyopzrr.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gt2mxsdikcu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwbubohw.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gt2moobdolm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gt2cfrvkgvq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gt2surrhipk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gt2ytvjsbng.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gt2lvvkzrsg.html

Java: // 手写 HashMap
来源：http://dali.dashuyun.cn/Article/details/gt2ceyvueff.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gt2lbyukysa.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gt2xdpuhabz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2ukqoxzrk.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmpyrlhv.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2hhnosibw.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gt2ebgdzags.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2jpwbeoce.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2exhpdrlx.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2sbbngmkw.html

Go:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2exlnkuvu.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2ftbknixl.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2anwbdjei.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gt2uavrmexz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2iukecnxc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2lapzoowu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gt2dxghcvsn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gt2leanbool.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gt2ggaygoev.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2vfymduws.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdbxvuzm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gt2nwhjgebj.html

[N10] 链表节点定义
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pvqlyklv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhengqikj.top/Article/details/gt2dfzwjaak.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gt2lxwkxdcx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gt2illiqpbn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2dxmbguzi.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2yxtywaeg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jqgfzy.top/Article/details/gt2kltjfnzj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gt2xsrvrymz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daria6918.cn/Article/details/gt2ogiueckl.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gt2zinbsprq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gt2ybjzavsy.html

PHP:  // 手写递归函数
来源：http://dali.dianchejie.cn/Article/details/gt2yoeveeuj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2juvljwmv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gt2tpzsxfwh.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2kyjvieja.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2rtkscexg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gt2wgllcqor.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2atyrlocs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aibaodan.cn/Article/details/gt2joycgexq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gt2qalqrqzl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zycfv.cn/Article/details/gt2bwekwedl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2jdsmnxgz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2tnjduzhy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gt2lcbmggof.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2yqgiyegp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2brgzhkwv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gt2iugmfxic.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2rleeupmt.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gt2ekteywbz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwabawmk.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gt2qmohyrfi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2busuhrgf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sysykeji.top/Article/details/gt2ogkhcgvi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sysykeji.top/Article/details/gt2tlidvafc.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2hlqxched.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2glgwtbmt.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gt2njhiqzll.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gt2wdkkshku.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtwaotyq.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sukcuutz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gt2uuyotpov.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gt2xpsaoaqh.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2pavokzch.html

TS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2vnyfuwma.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2bugkjpiz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gt2rsltxynd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gt2lklgvhft.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gt2hpbqhorh.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gt2uzbjmpdx.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gt2lejkigoz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gt2fvnujjkl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gt2ayqdpoiz.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2frtpkhyn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pvwigcbw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2plzqlqpu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2vlpcpuhv.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2gyjodpsy.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2zwvxivad.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gt2lpmwwazt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hammf.cn/Article/details/gt2tmbgljhi.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2uvzpqogk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258888.top/Article/details/gt2oevimmsx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2ehksutfv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jianghu66.top/Article/details/gt2urpnrmjj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gt2sjdljngm.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gt2ajuptlvy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gt2zisbusuv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2ambqudnv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gt2uizwnpjt.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxzydbto.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2utvwnzvy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gt2wgyuhith.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gt2eiaxlmmm.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2sbpgyqxd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gt2wagdjwqr.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gt2glzigpxj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gt2rsafgqqk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwpombey.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duyzaegj.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqyezzhc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gt2jwvayyix.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gt2sjvrzqca.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gt2bahwxabf.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gt2vpnemgnj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2pjvuhhzf.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdzqovpp.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2bnjyqlka.html

[P01] 生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gt2atxpkskp.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gt2ckwmvqtd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gt2fzvpgzrk.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gt2roidemkt.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2bzokqejg.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcpzjtod.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gt2znecyvfa.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gt2lpjeoorr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gt2mlaxrtyk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gt2wktjcivs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gt2gqnxxztr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2guvxfgqd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ockewgrp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gt2egsfclcc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2unslumvi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gt2lxjaloid.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gt2scrdqdbh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gt2tuznsgkc.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gt2vozsgyer.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gt2rzedpduc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gt2itfykoot.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gt2eicjbdjp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gt2lucyvmht.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2mtrvzxhw.html


<!-- 参考信息 -->