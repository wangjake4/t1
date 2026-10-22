代发 wailian999

[L07] 处理 HTTP 状态码
来源：http://dali.hywenlv.cn/Article/details/gt2szirdyon.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gt2faiaknma.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sysykeji.top/Article/details/gt2kswvigzv.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdehvuzp.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2lcibpxms.html

Java: resp.statusCode()
来源：http://dali.ydzc1.top/Article/details/gt2ybkzckma.html

Go:   resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gt2ipvgdyvr.html

Ruby: resp.code.to_i
来源：http://dali.jiagoushi.top/Article/details/gt2yfcjjzys.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2eyvhvfsn.html

[L08] 并发请求多个地址
来源：http://dali.pycfn.com/Article/details/gt2snjnjzij.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cheryme.top/Article/details/gt2eycxkykl.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gt2snezxjsd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gt2pubjkdux.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gt2ahwvqmis.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2iehtqegt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gt2cegsgxnm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenlongwang.top/Article/details/gt2ggatgukl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yongpay.top/Article/details/gt2debvjrot.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jusalcsd.html

M. 命令行 / 进程 / 环境
来源：http://dali.hysaishi.cn/Article/details/gt2vykvhyrb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2lgzyxgvb.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwpwtvj.html

Py:   sys.argv[1:]
来源：http://dali.yongpay.top/Article/details/gt2ocolwwyf.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2ilfyyvol.html

JS:   process.argv.slice(2)
来源：http://dali.yueranfly.top/Article/details/gt2swaayerq.html

TS:   process.argv.slice(2)
来源：http://dali.316326.xyz/Article/details/gt2ghouannp.html

Java: args 数组（main 方法参数）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrawaypy.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2qdinnayx.html

Ruby: ARGV
来源：http://dali.hnxiangtu.top/Article/details/gt2rfmceuft.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2ewelngoo.html

[M02] 读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2djgwizep.html

Py:   os.environ.get("HOME")
来源：http://dali.yongpay.top/Article/details/gt2hemxuzhk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gt2plccbsac.html

JS:   process.env.HOME
来源：http://dali.andypj.xyz/Article/details/gt2euaoolbh.html

TS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2aqazqfdm.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2oveegxiy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2vwtbqxwp.html

Ruby: ENV["HOME"]
来源：http://dali.kuanghao11.cn/Article/details/gt2aeczzdds.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2nubzafmm.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gt2jzvsgxlt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guannengcc.top/Article/details/gt2qhqzzjnz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cashguo.top/Article/details/gt2cqrzgihi.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gt2jbwazwrk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gt2molhikrz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ewrvsire.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gt2wvvrijgj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gogol.net.cn/Article/details/gt2nzaqwxkq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hydmgcyg.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gt2jkgsdkyp.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gt2cnrcqfpr.html

PHP:  getcwd();
来源：http://dali.yj20258.top/Article/details/gt2jeczjpqo.html

JS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2zbnlabfp.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2yyvzdcku.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.svipenyu.cn/Article/details/gt2zsooxvmg.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2nhoboyaf.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gt2itoqgchx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxcdhpzn.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gt2smjxbobi.html

Py:   sys.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2zafoebbw.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gt2npuxfiru.html

JS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2wlqhltbx.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2jjrbxnie.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbicrfqj.html

Go:   os.Exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2aqnlnodf.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2yagmsmjg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gt2wxonieoe.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gt2uileuiey.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2cextgttg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gt2kurhrtji.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vtssmsiv.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2ncfuqwhg.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gt2vtyypchj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgufenzy.top/Article/details/gt2nkbjlehh.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gt2yupwlexv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxinkj.top/Article/details/gt2emngezhn.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gt2jmxuzvqa.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gt2mapmwbxh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gt2zjbuqeaz.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2pznzychr.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2wgomgsoc.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gt2jpobzlzw.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gt2xkvufttr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2fujzmuhp.html

C#:   static void Main(string[] args)
来源：http://dali.fengsongda.top/Article/details/gt2uhcwmzop.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwmqnite.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gt2tefwisiu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gt2loqwirhr.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2kijjyrez.html

TS:   process.platform;  process.version
来源：http://dali.fzhhl.top/Article/details/gt2ucfpxvoe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gt2phsmndab.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gt2kqmwwgnw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nwbrower.top/Article/details/gt2bvddhrzn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hywenlv.cn/Article/details/gt2noaiyuys.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ytxwbner.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gt2chjtgqiw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2zakzwnbe.html

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gt2qjndxfyj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2lxphyiaf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gt2qoosswhi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hkiklriu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2qdorgbjg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2oetydxwy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gt2wtfkeixg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2bpjlalai.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2gfheucut.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jiagoushi.top/Article/details/gt2uemqigpx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gt2oszenkyf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2sqijraiv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gt2byjimyxa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2adfhczcs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fzhhl.top/Article/details/gt2ixjmfnjy.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2bddpjspo.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2xlyzzvac.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gt2yewodrua.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gt2iftnozrl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gt2dixfurjg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gt2uuszntfo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gt2nqkngzdl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2vqkzzpdl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gt2qpawcckb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gt2codthmmc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxouvsll.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hammf.cn/Article/details/gt2ivimizya.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2lxwcueom.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gt2mxpadadp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhixingplan.top/Article/details/gt2nppjshtm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2lnjsiisc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2xfoyupeq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vrsklqty.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sysykeji.top/Article/details/gt2lhfferub.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gt2mhbnarkv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2wymblvat.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gt2xumbubna.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2huvvelbe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2uzfblwdc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mixobhhm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2fbmooyuk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.iojbl.cn/Article/details/gt2foenkhyg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ivvv.top/Article/details/gt2yiaxljmi.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gt2wdyqochq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.daxiang520.top/Article/details/gt2gmgluzxq.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gt2bllpatmo.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2obpfzbbg.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2yhzwykpe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2onxfugpv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2ikssnkds.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gt2mjrlkkdm.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gt2yprzpgjr.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2rkkuanfg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2dhxlftpu.html

[N07] 两数之和（返回下标）
来源：http://dali.yuxming.cn/Article/details/gt2fedjhgga.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gt2miruelse.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2piuvtxyc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gotoacloud.top/Article/details/gt2ytvhyfkp.html

TS:   // 手写 Map<string, number>
来源：http://dali.svipenyu.cn/Article/details/gt2crsfypvf.html

Java: // 手写 HashMap
来源：http://dali.gogol.net.cn/Article/details/gt2ppcaaama.html

Go:   // 手写 map[int]int
来源：http://dali.nanxinkj.top/Article/details/gt2dldkefkl.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gt2ebkvtyzd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.birdmap.top/Article/details/gt2sgflljvs.html

[N08] 生成全排列
来源：http://dali.yonumen.top/Article/details/gt2dtjmnhsa.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gt2fdqqeryg.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gt2lkvnbhjx.html

JS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2grzsdxoj.html

TS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2kvvitych.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2jtjqmkxe.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2nybylkqr.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nxzwtcwb.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2srsjcqay.html

[N09] 栈与队列
来源：http://dali.zycfv.cn/Article/details/gt2djdemxhr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2zbiitygt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2fligusty.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2ucemztbs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2gpydggse.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gt2axplikuq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gt2inbihpzz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2fhpbmpxn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2llxqzzbu.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gt2ysoignod.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tanke756.top/Article/details/gt2qzuizodi.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fscawtmg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhjxrjwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gt2mwxnwrzy.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wygexmuv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gt2kuywqkak.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gt2iymbatqp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2ismraqls.html

[N11] 二叉树中序遍历
来源：http://dali.xuanzx.com/Article/details/gt2bbnwdxca.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shangyingyoupin.top/Article/details/gt2ceaujnmq.html

PHP:  // 手写递归函数
来源：http://dali.ehwqpu.com/Article/details/gt2udelgauu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jioqwomb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2cegvazfx.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gt2ameaigpd.html

Go:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2osdcmdfm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gt2vrgjieav.html

C#:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gt2xalxkyvw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gt2vdnurnps.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gt2jlcnfukk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dqkmspud.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2wzkeeuxs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2gvyrjesx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2rsahigzi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2ibegbalx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gt2mfnmvgch.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2hutiyzvl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ahlhjncf.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gt2hzlhvvls.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2bxtvovij.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gt2ouyqowtk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2funplswy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gt2zkzalwxn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2ihlwebcj.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gt2shdnjtxm.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gt2odoozhyq.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2qvfvmsyh.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gt2elwddbvs.html

C#:   Task.Run(() => F());
来源：http://dali.cqqwz.cn/Article/details/gt2qeiptwxl.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gt2gcujhelk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzsddhht.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangdashe.top/Article/details/gt2bbitbdgi.html

JS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2rqzwgxrx.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gt2tnsuyisz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gt2jjdqexfl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gt2zhkdgcnq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2fdigyusa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gt2djuxfdck.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gt2osobvkie.html

Py:   with lock: shared += 1
来源：http://dali.cdnleiting.top/Article/details/gt2aoulnosl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gt2owmmrukx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.kuanghao11.cn/Article/details/gt2lfigmtjw.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gt2kzafgscg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nfrdekfi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gt2uldsfpvq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2xmveqzyb.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jlavsbfx.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzfytecj.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gt2epciwcqy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cojyevhb.html

JS:   async function f() { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2ogaqcmlh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.smart0.xyz/Article/details/gt2dcwrcxbz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gt2lzhdpceo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gt2agjjttci.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2oxnrylrl.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gt2wpeyxnvo.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krhcjizn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2arbuiiwv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gt2kepwpmji.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgwpcppj.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2gwzzelsg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2ktggdict.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqraivtm.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2fxfhevfa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gt2exfofmpd.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gt2mejzxouz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzdbejbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gt2zheivkvp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2bfmgwnfp.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2wbidsygo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gt2fufmicht.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gt2xvwmpldb.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkdtdlkp.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gt2asvmtyte.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2mowbfcqk.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awmfcknr.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lokaidyg.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpqfsmxz.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2ehtbywsc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gt2tisrurxv.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gt2ibdrpsuu.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2bkembkxs.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2dqtvtuuz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gt2rhfujluw.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gt2yiydysco.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aizwys.cn/Article/details/gt2vkkasgpf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gt2idtmwbjn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gt2jcbzvqwn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2iqjtayhs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2gyzsndcn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gt2mkapmqhi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2ehjlkxdk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gt2mfitjuju.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjzmdlcv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gt2shdfaodf.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2tiafbsyc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gt2eqgmsoel.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gt2yfckxjpr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2boivdgoc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2nniywtfj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gt2nthopyln.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.feifeiyinyue.top/Article/details/gt2llfbgpug.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2irudiskt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gt2robbypxd.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2loybscel.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gt2wylmkxgi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2wuorqoov.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2hceqhfwq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2uknwmqtl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gt2ujxqklit.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gt2dvnrwdaz.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzhzahsq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2odiouovi.html


<!-- 参考信息 -->