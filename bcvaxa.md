代发 wailian999

TS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdvitlqu.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2opnabxpp.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2cuuaptji.html

Ruby: resp.code.to_i
来源：http://dali.iojbl.cn/Article/details/gt2rkigeytz.html

C#:   (int)resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gt2izwlytlx.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gt2efmwtnbm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gt2zrtjzgis.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gt2expjcucw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gt2uipdhdnj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gt2rzduntfn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wshuhzdl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.guannengcc.top/Article/details/gt2nlorjicr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gt2kbvszmdw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2hcathkpg.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxiluiep.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj202588.top/Article/details/gt2ousymqgn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zpraeira.html

[M01] 读取命令行参数
来源：http://dali.sweek.top/Article/details/gt2infhqoej.html

Py:   sys.argv[1:]
来源：http://dali.iojbl.cn/Article/details/gt2dhgcnudg.html

PHP:  $argv;  $argc;
来源：http://dali.xylfe.cn/Article/details/gt2uwmnbagr.html

JS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2kcltaysj.html

TS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2eatmzach.html

Java: args 数组（main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gt2wropppsu.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gt2xkubhoqr.html

Ruby: ARGV
来源：http://dali.jianghu66.top/Article/details/gt2zfiweyqz.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ydzc1.top/Article/details/gt2jaspymsv.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2jyefrchl.html

Py:   os.environ.get("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gt2uuorlcro.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2rvylanje.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2pghbeqhn.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2hkzfsdqo.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2gnkfgnhu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2ipocdlum.html

Ruby: ENV["HOME"]
来源：http://dali.xylfe.cn/Article/details/gt2qlkwebqn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.smart0.xyz/Article/details/gt2webdnxpn.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2zlkwbfph.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hysaishi.cn/Article/details/gt2sryfcyhj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gt2evohpbgx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gt2vyjbjgto.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2bnkjrbtm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gt2xkdraozl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gt2tjokhukt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.bjfxy.top/Article/details/gt2tzyhdpav.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvjdnwub.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gt2nbtgnigh.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gt2odgzizoq.html

PHP:  getcwd();
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxoruygu.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2igafhlgg.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2macpcrmc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gt2lfvhrrry.html

Go:   os.Getwd()
来源：http://dali.gzhubu.top/Article/details/gt2zoirsslb.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2glfmgyyp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tianlin.xyz/Article/details/gt2fxdlstpo.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gt2gakzflie.html

Py:   sys.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abidvxex.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2nnwftcsw.html

JS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2xtdbctse.html

TS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfoybmsh.html

Java: System.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2jjlntfgv.html

Go:   os.Exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odieixeu.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gt2wkpnsznp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gt2dsmljtqj.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrxfuser.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2kwedfcgg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ppjwa.cn/Article/details/gt2ueflvfao.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2xemzsvfi.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2mgddxtdg.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gt2necxktrl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eirkbmvi.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2ofvwwolq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gt2ebehjmuy.html

[M07] 判断是否为主入口
来源：http://dali.sufxvd.cn/Article/details/gt2ienyplxn.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2evlzjyvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2dkjcmijq.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gt2exfbxdhe.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gt2hwjwufmx.html

Java: public static void main(String[] args)
来源：http://dali.hammf.cn/Article/details/gt2kcxnpbuk.html

Go:   func main()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xuflwxtb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gt2eploucvg.html

C#:   static void Main(string[] args)
来源：http://dali.hnqzz.top/Article/details/gt2rwtlhpul.html

[M08] 获取系统与运行时信息
来源：http://dali.yanxiufei.cn/Article/details/gt2wmcyzqwy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258.top/Article/details/gt2wigsijme.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gt2kndmsscw.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gt2fxgyaugb.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2grgfoash.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nwbrower.top/Article/details/gt2czqocpxb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuxming.cn/Article/details/gt2llzkroqd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gt2lcfrbfat.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.feifeiyinyue.top/Article/details/gt2pgncmnir.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mekeolnv.html

N. 数据结构与算法
来源：http://dali.xinyue.icu/Article/details/gt2tqslopyi.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrmcbabh.html

[N01] 二分查找（有序数组）
来源：http://dali.gaohongyu789.top/Article/details/gt2esgammen.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2iqrievas.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2oedggzdl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2mshaihus.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2pbovxmsc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2hheguwvj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rezjyefi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rthgoayp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2gnsdfejj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gt2hjwwzkgm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zdqjudy.top/Article/details/gt2ppgyujxu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gt2htcjpzgp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2lggjskyf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gt2fsobhfhq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gt2xtqqqulu.html

Go:   slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2ygcfwmnk.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2xxgzmmtf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sweek.top/Article/details/gt2uwzdegvq.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gt2txqgpxpr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hfpthk.cn/Article/details/gt2fnwxpmij.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gt2isroxydw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gt2lhyzrvgy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2disbvhvq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.redwolf501.top/Article/details/gt2xizhrmmm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssvvznpd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zueqrfvc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xinyue.icu/Article/details/gt2wbeeoszm.html

[N04] 斐波那契数列
来源：http://dali.316326.xyz/Article/details/gt2xdennsvu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2veashctz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sufxvd.cn/Article/details/gt2kdlpbnsd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2cesyzggp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2ujxzjros.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gt2jxducizy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gt2evoleopw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gt2iheugdfw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2vqvhzztu.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gt2yazliqtf.html

Py:   math.gcd(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2cqdznleb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2arxcsvbw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gt2aekhppax.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2vrowdsft.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gt2knvmkrpi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gt2ljfygcii.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkoncua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yj20258888.top/Article/details/gt2wcwaukof.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gt2ebudjpwm.html

Py:   s == s[::-1]
来源：http://dali.shuidangran.top/Article/details/gt2fawwrrvi.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqsdihxb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2smlgdgou.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gt2okqhrhvi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gt2uvgkxfur.html

Go:   // 双指针从两端比较
来源：http://dali.snrcjt.cn/Article/details/gt2aqctctjd.html

Ruby: s == s.reverse
来源：http://dali.zdqjudy.top/Article/details/gt2trwhonnm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gt2xhnbaisr.html

[N07] 两数之和（返回下标）
来源：http://dali.gaohongyu789.top/Article/details/gt2yygcfevn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gt2odlpyfsr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmnfvxiu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.nanxuanxn.top/Article/details/gt2ycdrkgno.html

TS:   // 手写 Map<string, number>
来源：http://dali.hongshengwenyu.top/Article/details/gt2abdkmqad.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wonjfzmh.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gt2qndwverv.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gt2ntefsdfg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2snrmwhdd.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gt2tusvzcbt.html

Py:   itertools.permutations(arr)
来源：http://dali.andypj.xyz/Article/details/gt2nhvcwurx.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gt2aevvwgef.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2rhlvnoos.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2ocefutxh.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gt2foauucvt.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2ihdpsfxn.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2otieaunu.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2jjeyhwlq.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gt2xnxshcyo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gt2rpqadgtq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2zaukfvsi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2plvhcrpe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gt2kqrlwqal.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2dezgusqa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sxryk.cn/Article/details/gt2tpxlirsk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gt2jnavkuzs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gt2qycayvqy.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2orsdhcwc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yangfankeji.com/Article/details/gt2bagahbgq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yqymhqpp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gt2tmwyczgy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2ugotkush.html

Java: class Node { int v; Node next; }
来源：http://dali.gzhubu.top/Article/details/gt2ghkwhgtd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.andypj.xyz/Article/details/gt2kfgnlnen.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yueranfly.top/Article/details/gt2syjyahda.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gt2npyrjazx.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2wzsscdct.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.svipenyu.cn/Article/details/gt2lwhcwafn.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gt2bowzdbah.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2hprgixlz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsewkxvc.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2gnfftdou.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2wmnlvsjg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2vwjgvnjw.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2fthxbhph.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gt2svmztebj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gt2tjtjxcrw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.quarkkingdee.top/Article/details/gt2pemyeozk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gt2vpxqmldf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2uejoyzxl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ichljrcj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebhlwvyl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gt2jkhcmgsz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gt2voubgqsq.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2kovduiah.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gt2oqfgkgnm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsjrmtys.html

[O01] 启动一个线程
来源：http://dali.gogol.net.cn/Article/details/gt2ehoikigy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tanke756.top/Article/details/gt2fyqupcyd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gt2sjtytcdu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gt2acxoyijt.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2lufegdwa.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gt2osseobpw.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gt2urddrckk.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2vegamwal.html

C#:   Task.Run(() => F());
来源：http://dali.xuanzx.com/Article/details/gt2bqxjwiqi.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gt2zibnsgir.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2lszzyefd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gt2rgeflodr.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2flwyckxe.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2ngjwiswh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2ciztmtie.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gt2kcjjoktl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gt2dotmqbww.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gt2pjuychvx.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gt2xqjxnvsa.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gt2bsfrnlsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2sgxvyfxk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ehwqpu.com/Article/details/gt2nccdbztb.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2uzhwscqf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2jqpircmn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gt2nqbuefta.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gt2vlcgbsdi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2jeccllkc.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gt2nkwjapir.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2ptgrhxhi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gt2mdvahlga.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eawmfwwe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kaixlcfj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gt2xzvpfekh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gt2wefafdcq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncuezxyj.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gt2losfxpiw.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gt2xqvjwrgu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2hyvzuzfq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.meibo888.top/Article/details/gt2zaczbcaf.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2pcxgfegx.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gt2dvpuixtr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gt2qyxprdjm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcqicoel.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2ymwzbtog.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2xxkcrysf.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gt2tjyskzoa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gt2nxgszign.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2rhtdjbbm.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2cizvydvs.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gt2evmqmkvv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gqqscgtl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gt2odohzwrt.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gt2pdcmrtxw.html

C#:   Parallel.For
来源：http://dali.yueranfly.top/Article/details/gt2zbowrnqw.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2odpeugzt.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gt2fkbvyhsl.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uscdfgtu.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2jenxrrjs.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2btqawhil.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2qsbcczua.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2hdyyajsb.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gt2gsghoqus.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gt2iqemmeli.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gt2frkslpwp.html

Ruby: SecureRandom.uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2dfujrtgi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gt2godmnxfa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2xpqkbrdw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gt2yshtorfb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmensone.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2eotixtmy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swljizhi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2cbocsmxm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gt2nytdhmcd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gt2bidzfbpy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gt2rnjqltnu.html

[P03] 生成短随机字符串
来源：http://dali.hfpthk.cn/Article/details/gt2zmprycul.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcpwrju.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigfzy.top/Article/details/gt2aysjklis.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gt2ghyfcijp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2watjgxon.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gt2qgabntvm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gt2xbqeqynu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdplibol.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ztpeedwn.html

[P04] 求长度
来源：http://dali.chenlongwang.top/Article/details/gt2xcnqxlku.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odxrlcte.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2qumpshbu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2fqerpdfz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2ykmwsncq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gt2lbutgblh.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ikkkpiwd.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gt2lvmvxaik.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2klirepda.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gt2vkoxlznl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2athkquua.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gt2kbasxeud.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwfzzeye.html


<!-- 参考信息 -->